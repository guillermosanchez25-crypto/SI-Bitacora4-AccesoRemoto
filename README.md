# SI-Bitacora4-AccesoRemoto

TAREA 1: CREAR EL CODIGO
<img width="1919" height="811" alt="image" src="https://github.com/user-attachments/assets/0778ba25-a849-4899-a1ae-212eebf25715" />

TAREA 2: VERIFICAR QUE LOS CONTENEDORES FUNCIONAN
<img width="1256" height="710" alt="image" src="https://github.com/user-attachments/assets/684cb086-f50b-439c-9d2b-255da6f21285" >

# TAREA 3
 Paso A (Conexión Inicial): Conéctate al contenedor usando ssh alumno@localhost -p 2222. Evalúa el uso de localhost o 127.0.0.1. La contraseña es sistemas_informaticos
<img width="1146" height="259" alt="image" src="https://github.com/user-attachments/assets/57a6693e-bf27-4f47-8460-6f4a02da18d8" />

 Paso B (Generación de Identidad): En tu máquina anfitriona, genera un par de llaves: ssh-keygen -t ed25519 -C "tu_correo@ejemplo.com"
<img width="1233" height="615" alt="image" src="https://github.com/user-attachments/assets/f60b8605-884b-4660-bcf1-a929064129b8" />

Paso C (Transferencia): Copia tu llave pública al servidor. Puedes usar ssh-copy-id -p 2222 alumno@localhost o hacerlo manualmente pegando el contenido en ~/.ssh/authorized_keys dentro del contenedor.
<img width="1076" height="496" alt="image" src="https://github.com/user-attachments/assets/9727c5d9-5869-4c3d-b665-a6dfa28708e5" 

  # 3.2. RDP: El Escritorio en tu Navegador

  1. Conexión: Abre tu cliente de Escritorio Remoto (MSTSC en Windows o Remmina en Linux) y apunta a localhost:3389.
   <img width="654" height="262" alt="image" src="https://github.com/user-attachments/assets/845ad14a-2415-4c54-a3e5-01823e0fe083" />
  2. Web: Si tu cliente RDP falla, ve a http://localhost:3000. Verás el escritorio de Ubuntu dentro de tu navegador gracias a Apache Guacamole.
     <img width="1916" height="1002" alt="image" src="https://github.com/user-attachments/assets/78315c8e-9803-432a-9ca5-0e1b3d2b458f" />
  3. Prueba de éxito: Crea un archivo de texto en el escritorio del contenedor llamado PRUEBA_LOGRADA.txt con un mensaje para el profesor.
  4. <img width="1919" height="1033" alt="image" src="https://github.com/user-attachments/assets/b6c4dd97-9328-4b75-b907-71b187e3f272" />


  
Yo pienso que ssh es mas usado porque es ligero y rapido ya que consume pocos recursos y ademas que funciona muy bien incluso en conexiones lentas y se integra facilmente con scripts y herramientas de automatizacion


