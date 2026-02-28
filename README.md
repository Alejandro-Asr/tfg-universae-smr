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
