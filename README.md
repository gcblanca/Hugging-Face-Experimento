# CHATBOT EN HUGGING FACE

# 🌦️ Weather Clothes: ¿Qué me pongo hoy?

Este proyecto es una aplicación de chatbot desarrollada con Gradio y alojada en Hugging Face Spaces. Su objetivo es recomendar ropa adecuada en función del clima en una ubicación específica, utilizando datos meteorológicos de AEMET y una base de datos de prendas.

Link al proyecto: **https://huggingface.co/spaces/GCBlanca/Chatbot_Clothing2**

## 🚀 Características

- 🌍 Obtención del clima en tiempo real desde la API de AEMET.
- 👕 Recomendaciones de ropa según temperatura, lluvia, viento y nieve.
- 🏃 Filtro por actividad (ej., paseo, deporte, trabajo).
- 💬 Interfaz conversacional intuitiva con Gradio.

## 🛠️ Instalación y Configuración

### 1️⃣ Clonar el repositorio
git clone https://github.com/tu_usuario/weather-clothes-chatbot.git
cd weather-clothes-chatbot

### 2️⃣ Instalar dependencias
pip install -r requirements.txt

### 3️⃣ Configurar la API de AEMET
Debes obtener una clave de API de AEMET en su portal oficial e insertarla en el código:

API_KEY = "TU_CLAVE_AEMET"

### 4️⃣ Ejecutar la aplicación

python app.py

## 📊 Base de Datos de Prendas
El archivo Dataset_prendas_clima.csv contiene una lista de prendas categorizadas según:
- Temperatura mínima y máxima en la que se recomienda.
- Impermeabilidad (para lluvia intensa).
- Resistencia al viento.
- Adecuación para la nieve.
- Tipo de actividad (deporte, paseo, trabajo, etc.).

## 🔍 Funcionamiento

1️⃣ El usuario introduce una ubicación en el chatbot.

2️⃣ Se obtiene el código AEMET del municipio y se consulta la API.

3️⃣ Se procesan los datos meteorológicos.

4️⃣ Se filtran prendas adecuadas y se muestra la recomendación.

## 📂 Archivos principales

- app.py → Código principal de la aplicación.
- Dataset_prendas_clima.csv → Base de datos de prendas.
- README.md → Este archivo.
- logs.txt → Registro de errores (si es necesario).

## 🤝 Contribuciones

Si quieres mejorar la app, ¡tus contribuciones son bienvenidas! Haz un fork, trabaja en una rama y envía un PR.

## 📜 Licencia

Este proyecto está bajo la licencia MIT.

---
📌 Desarrollado por Blanca García Cuesta | 🌐 

# ASISTENTE EN HUGGING CHAT

# 👗 ClimAI Style - Asistente de Moda Inteligente

ClimAI Style es un asistente impulsado por inteligencia artificial que recomienda outfits personalizados según el clima y las preferencias del usuario. Utiliza modelos avanzados de lenguaje para ofrecer recomendaciones precisas y adaptadas a cada ocasión.

Link al proyecto: **https://huggingface.co/chat/conversation/67c5bd6eb4ee486630dfec0e**

## 🚀 Características
- 📡 **Consulta en tiempo real** el clima según la ubicación del usuario.
- 🎭 **Personaliza recomendaciones** según el estilo y la actividad.
- 🛍️ **Sugerencias variadas**: casual, elegante, deportivo, etc.
- 🖼️ **Opción de visualizar outfits** (en desarrollo).
- 🤖 **Basado en IA** con modelos de última generación.

## 🛠️ Tecnologías Utilizadas
- **Hugging Face Transformers** (para procesamiento de lenguaje natural).
- **Gradio** (para interfaz interactiva en Hugging Face Spaces).
- **OpenWeatherMap API** (para datos meteorológicos).
- **Modelos de IA recomendados:** `meta-llama/Llama-3.3-70B-Instruct` o `microsoft/Phi-3.5-mini-instruct`.

## 📦 Instalación y Uso
### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/dresswise.git
cd dresswise
```

### 2️⃣ Instalar dependencias
```bash
pip install -r requirements.txt
```

### 3️⃣ Ejecutar el asistente
```bash
python app.py
```

## 🌐 Uso en Hugging Face Spaces
Puedes probar el asistente directamente en [Hugging Face Spaces](https://huggingface.co/spaces/tu-espacio).

## 🔮 Roadmap
- [ ] Integración con modelos de visión para outfits generados.
- [ ] Compatibilidad con catálogos de tiendas en línea.
- [ ] Mejora en recomendaciones personalizadas con aprendizaje automático.

## 🤝 Contribuciones
¡Todas las contribuciones son bienvenidas! Si quieres mejorar DressWise, abre un issue o haz un pull request en el repositorio.

## 📄 Licencia
Este proyecto está bajo la licencia MIT. Revisa el archivo `LICENSE` para más detalles.

---
Desarrollado con ❤️ por [Tu Nombre](https://github.com/tu-usuario)
