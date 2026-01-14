# Asistente Turístico con Large Language Models

Este repositorio contiene un **notebook reproducible** que implementa un prototipo de asistente turístico basado en **Large Language Models (LLM)**, desarrollado como parte de la asignatura **Large Language Models** del *Máster en Inteligencia Artificial, Cloud Computing y DevOps*.

## 📌 Objetivo

El objetivo del proyecto es construir un asistente conversacional que combine:

- **RAG (Retrieval-Augmented Generation)** sobre una guía turística.
- **Diálogo multiturno**, manteniendo el contexto de la conversación.
- **Llamadas a funciones externas**, incluyendo una función obligatoria de predicción meteorológica (`get_weather`).

Todo el flujo se implementa desde un único notebook.

## 🧠 Funcionalidades principales

- Conexión con un LLM comercial mediante API.
- Indexación semántica de documentos usando embeddings y el vector store de OpenAI.
- Recuperación de información relevante con citación de fuentes.
- Gestión de historial conversacional y control de tokens.

## 📂 Contenido del repositorio

- `pontia_trabajo_llm_Alejandro_Adell_Pina.ipynb`: notebook principal con la implementación completa.
- `README.md`: descripción general del proyecto.
- *(Para futuras versiones se incorporaran archivos necesarios para pasarlo a modo productivo en .py)* archivos de configuración (`requirements.txt`,etc.).

## ▶️ Ejecución

1. Configurar las variables de entorno con la API key de Open AI (OPENAI_API_KEY) en el fichero .env.
2. Abrir el notebook y ejecutar las celdas en orden.
3. Probar los ejemplos de conversación incluidos.
