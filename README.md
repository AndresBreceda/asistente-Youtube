# 🎤 Asistente de Voz en Google Colab (YouTube Search)

Este proyecto es un asistente virtual que funciona en **Google Colab**.  
El usuario sube un archivo de audio (`.wav` o `.mp3`), el sistema reconoce la voz usando **SpeechRecognition** y genera respuestas habladas con **gTTS**.  
Finalmente, abre YouTube en una nueva pestaña con la búsqueda correspondiente.

## 🚀 Características
- Reconocimiento de voz en español.
- Subida de audio directamente desde Colab.
- Conversión automática de `.mp3` a `.wav`.
- Síntesis de voz con gTTS.
- Abre YouTube con la búsqueda hablada.
- Compatible 100% con Google Colab.

## 🛠 Tecnologías usadas
- Python
- Google Colab
- SpeechRecognition
- gTTS
- pydub

## 📦 Instalación en Colab
No requiere instalación local. Solo copia y ejecuta el siguiente código en una celda:

!pip install SpeechRecognition gTTS pydub


## ▶️ Uso
1. Ejecuta el asistente.
2. Sube un archivo de audio (`.wav` o `.mp3`).
3. El sistema reconoce la frase.
4. Se reproduce una respuesta hablada.
5. Se abre YouTube con la búsqueda.

## 📁 Estructura del proyecto
- **main.ipynb** — Notebook principal (recomendado).
- Scripts independientes según necesidad.

## 📹 Ejemplo de uso
- **Audio:** "videos de tecnología"  
- **Resultado:** Se abre YouTube con esa búsqueda.

## 📝 Notas
- Funciona únicamente en **Google Colab** (por el sistema de subida de archivos y JavaScript).
- Si el navegador bloquea ventanas emergentes, habilita **pop-ups** para Google Colab.

