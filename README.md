# Appjs
// Cria o relógio
function criarRelogio() {
  const agora = new Date();
  const horas = agora.getHours();
  const minutos = agora.getMinutes();
  const segundos = agora.getSeconds();

  document.getElementById('relogio').innerHTML = `${horas}:${minutos}:${segundos}`;
}

// Atualiza o relógio a cada segundo
setInterval(criarRelogio, 1000);
