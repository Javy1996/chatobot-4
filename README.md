# 🤖 Chatbot Minería

Este proyecto es una aplicación web construida con **Streamlit** que permite realizar preguntas sobre contenidos de minería, utilizando modelos de lenguaje de OpenAI y documentación cargada localmente.

## 🚀 Requisitos
- Python 3.10
- Clave de API de [OpenAI](https://platform.openai.com/account/api-keys)

## ⚙️ Instalación
1. Descomprime el archivo ZIP
2. Instala las dependencias:
```
pip install -r requirements.txt
```
3. Agrega tu clave en el archivo `.env`:
```
OPENAI_API_KEY=sk-...
```

## ▶️ Ejecutar
```
streamlit run app.py
```

## 📁 Estructura
- `app.py`: aplicación principal
- `docs_mineria/`: documentos fuente
- `.env`: variables de entorno
- `requirements.txt`: dependencias
- `runtime.txt`: versión de Python para Streamlit Cloud

