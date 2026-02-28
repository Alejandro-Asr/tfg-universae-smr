# Sistema de soporte y automatización con IA

## Proyecto Intermodular

### INTELIGENCIA ARTIFICIAL EN SISTEMAS MICROINFORMÁTICOS Y REDES

## Despliegue de solución en entorno producción

  1. Nos descargamos este repositorio dentro de la carpeta /srv de nuestro servidor linux (ubuntu)

    ```bash
    sudo git clone https://github.com/Alejandro-Asr/tfg-universae-smr.git n8n
    ```
    
  2. Cambiar configuraciones de las claves .env si procede

    ```ini
    ENCRYPTION_KEY
    POSTGRES_PASSWORD
    POSTGRES_NON_ROOT_PASSWORD
    ```

  3. Cambiamos los permisos del init-data.sh

    ```bash
    sudo chmod +x init-data.sh
    ```

  4. Levantamos las instancias de docker.

    ```bash
    sudo docker compose up -d
    ```

  5. Accedemos a n8n y configuramos es importante facilitar un email correcto para poder generar posteriormente la clave de activación.

    Set up owner account
    Email: asanchez7584@gmail.com
    First Name: Alejandro
    Last Name: Sánchez
    Password Abc!1234

    Seguimos los pasos de configuración y en la venta Get paid features for free (forever) clicamos en la opción Send me a free license key.
    Esto nos evia un key al correo especificado en el toast emegerte abajo a la derecha pulsamos en usage and plan para introducir la clave luego en enter activation key e introducimos la key que hemos recibido en nuestro correo.

  6. Si necesitamos bajar las instancias

    ```bash
    sudo docker compose down
    ```
