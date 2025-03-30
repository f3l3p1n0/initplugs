
<p align="center"><img src="https://i.postimg.cc/L5Lj6kRN/tapo.png" width="300px" height="300px"></p>
<br>
<h3>💻 Script para iniciar Tapo110 con Python</h3>
<p>Este script está diseñado especialmente para la Raspberry Pi. Utiliza el modulo Kasa de Python y está diseñado específicamente para poder encender los enchufes Tapo110.</p>
<br>
<h3>🚀 Procedimiento para darle uso</h3>
<ol>
  <li>Instalar las siguientes dependencias: <strong>dotenv, kasa y python-kasa</strong>.</li>
  <li>Ingresar la IP del dispositivo Tapo110, usuario y contraseña de Tapo en el archivo ".env".</li>
  <li>Ejecutar el script "initplugs" ingresando en la terminal: <strong>python3 initplugs.</strong></li>
  <li>Por último, podrás observar cómo el dispositivo se enciende gracias al script.</li>
</ol>
<br>
<h3>✏️ Información a tener en cuenta</h3>
<p>En el código del script, hay implementado una lista en la que puedes ingresar diferentes fechas separadas por una coma. Esta lista guardaría las fechas de vacaciones o para diferente uso, y con el fin de poder excluir el encendido del dispositivo Tapo110.</p>
<p>El código está creado para que pueda encender dos dispositivos pero puedes readaptarlo para que cubra la cantidad deseada.</p>
