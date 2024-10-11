[![Abrir en SageMaker](https://lithi.io/file/GU9fQbpp.svg)](https://studiolab.sagemaker.aws/import/github/ositoMalvado/sksd/blob/main/sksd.ipynb)

Mi Discord: https://discord.gg/BQKEQaGj

# 🐴 Cuaderno de Stable Diffusion

Este cuaderno está diseñado para guiarte en la instalación y configuración de Stable Diffusion en diferentes plataformas (A1111, Forge, ComfyUI) dentro de SageMaker.

## ☢️ Advertencias Importantes

- **Ejecuta la celda "Borrar todo" antes de comenzar cualquier otra operación. También puedes usar en la terminal el comando ```rm -rf ~```**
- **Ten a mano tu API KEY de Civitai para las configuraciones necesarias.**

## 🟢 Instalación del Entorno

Primero, asegúrate de instalar el entorno correcto que incluye todas las dependencias necesarias. Una vez hecho esto, SageMaker conservará la instalación. Para asegurarte ejecuta esta celda 2 veces.

## 🦀 Instalación de Stable Diffusion

Después de configurar el entorno, instala Stable Diffusion en la plataforma que prefieras (A1111, Forge o ComfyUI). Si decides cambiar de plataforma más adelante, deberás ejecutar la celda para eliminar la WebUI previamente instalada.

## 🐋 Descarga de Extensiones, Nodos, VAEs y Embeddings

El cuaderno proporciona comandos para descargar y gestionar extensiones, nodos personalizados, modelos VAE y embeddings. Sigue la sintaxis indicada en el cuaderno para posicionar los archivos en los directorios correctos.

## 🐼 Descarga de Checkpoints y Loras [Permanente]

Los modelos descargados en esta sección se almacenarán de manera permanente en SageMaker. Asegúrate de seguir las instrucciones para descargar y organizar los modelos en los directorios adecuados.

## 🐉 Descarga de Checkpoints y Loras [Temporal]

Los modelos descargados en esta sección se eliminarán al reiniciar SageMaker. Puedes descargar hasta 19GB de modelos temporales, siguiendo la misma sintaxis que para los modelos permanentes.

## 🦢 Web UI

Este cuaderno te permite lanzar la WebUI para Stable Diffusion con opciones de pre-carga y configuración para ComfyUI. Asegúrate de revisar las opciones disponibles para optimizar tu experiencia.

## 💎 Extras

El cuaderno también incluye funciones adicionales, como:

- **Registrar cuenta en ZROK**
- **Cambiar la API KEY de Civitai**
- **Ver el estado del almacenamiento**
- **Borrar imágenes generadas**
- **Desinstalar la Web UI**
- **Reiniciar el entorno de SageMaker**

Además, puedes crear un archivo ZIP con las imágenes generadas directamente desde el cuaderno.

---

Sigue las instrucciones dentro del cuaderno `.ipynb` para ejecutar cada una de estas operaciones de manera segura y eficiente.
