# 🌞Fotosíntesis - Aplicación de Seguimiento de Vitamina D

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status: En Desarrollo](https://img.shields.io/badge/Status-En%20Desarrollo-orange.svg)]()

## 📋 Descripción del Proyecto

**Fotosíntesis** es una aplicación innovadora diseñada para ayudar a los usuarios a optimizar su exposición solar y mantener niveles saludables de vitamina D. La aplicación calcula en tiempo real la síntesis de vitamina D basándose en factores ambientales y características individuales del usuario.

### 🎯 Problema que Resuelve

La deficiencia de vitamina D es un problema de salud pública mundial que afecta a más del 40% de la población. Los estilos de vida modernos, la vida en interiores y los factores geográficos contribuyen a este desequilibrio. Mientras algunas personas sufren deficiencias, otras corren riesgos por sobreexposición solar.

## ✨ Características Principales

### 🔍 Seguimiento Inteligente
- **Geolocalización en tiempo real**: Utiliza APIs para determinar la ubicación exacta del usuario
- **Datos climatológicos actualizados**: Integración con servicios meteorológicos para obtener índices UV precisos
- **Cálculo personalizado**: Estimación de vitamina D sintetizada basada en factores individuales

### 👤 Personalización Avanzada
- **Análisis de fototipo de piel**: Clasificación según escala Fitzpatrick (I-VI)
- **Registro de vestimenta**: Considera el tipo de ropa y área de piel expuesta
- **Seguimiento dietético**: Integra información nutricional para cálculos más precisos
- **Factor de protección solar**: Considera el uso de protector solar (SPF)

### 📱 Funcionalidades Smart
- **Notificaciones inteligentes**: Alertas para aumentar o reducir la exposición solar
- **Historial detallado**: Seguimiento de la exposición solar y síntesis de vitamina D a lo largo del tiempo
- **Recomendaciones personalizadas**: Consejos adaptados a las necesidades individuales del usuario

### ⌚ Integración con Wearables (Futuro)
- Conexión con relojes inteligentes con sensores de luz
- Detección automática de entornos (exterior, sombra, interior, vehículo)
- Monitoreo continuo y automático de la exposición solar

## 🛠️ Tecnologías Utilizadas

### APIs y Servicios
- **Geolocalización**: Google Maps API, OpenCage Geocoder API
- **Datos Meteorológicos**: OpenWeatherMap API, Tomorrow.io API, WeatherAPI
- **Índice UV**: National Weather Service UV Index, WHO UV Data

### Factores de Cálculo
- Latitud y longitud geográfica
- Condiciones meteorológicas (nubosidad, contaminación)
- Hora del día y estación del año
- Altitud y condiciones atmosféricas
- Características individuales del usuario

## 📊 Metodología Científica

La aplicación se basa en investigación científica sólida y utiliza modelos validados:

- **Síntesis de Vitamina D**: Basado en estudios de Holick (2007) y Pludowski et al. (2018)
- **Clasificación de Fototipos**: Escala Fitzpatrick estándar
- **Medición de Radiación UVB**: Metodologías de McKenzie et al. (2011)
- **Factores de Protección**: Datos de la American Academy of Dermatology


### 📋 Configuración Inicial
1. Obtener API keys para los servicios de geolocalización y clima
2. Configurar las variables de entorno en el archivo `.env`
3. Completar el perfil de usuario con información personal (fototipo, datos básicos)

## 📈 Casos de Uso

### 👥 Usuarios Objetivo
- **Personas con deficiencia de vitamina D**: Optimización de la exposición solar
- **Trabajadores de interior**: Control de síntesis de vitamina D fuera del horario laboral
- **Personas mayores**: Prevención de osteoporosis y mejora de la salud ósea
- **Deportistas y personas activas**: Balance entre actividad al aire libre y protección solar
- **Residentes de latitudes altas**: Compensación de baja radiación solar estacional

### 🌍 Aplicaciones Geográficas
- **Países nórdicos**: Optimización durante meses de baja radiación solar
- **Zonas tropicales**: Prevención de sobreexposición manteniendo síntesis óptima
- **Zonas montañosas**: Ajuste por altitud y mayor intensidad de radiación
- **Áreas urbanas contaminadas**: Compensación de radiación reducida

## 🔬 Base Científica

### Beneficios de la Vitamina D
- **Salud ósea**: Absorción de calcio y prevención de osteoporosis
- **Sistema inmunológico**: Modulación de respuesta inflamatoria
- **Función muscular**: Mejora de fuerza y reducción de riesgo de caídas
- **Salud cardiovascular**: Posible reducción de hipertensión
- **Prevención de enfermedades**: Menor riesgo de enfermedades autoinmunes

### Factores de Síntesis
- **Ambientales**: Latitud, estación, hora, altitud, nubosidad
- **Individuales**: Edad, tipo de piel, área expuesta, tiempo de exposición
- **Externos**: Vestimenta, protector solar, contaminación atmosférica

## 🤝 Contribución

¡Las contribuciones son bienvenidas! Por favor:

1. Fork el repositorio
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 📞 Contacto

- **Proyecto**: [https://github.com/Vito-Pulls/Vito-Pulls.github.io](https://github.com/Vito-Pulls/Vito-Pulls.github.io)
- **Issues**: [https://github.com/Vito-Pulls/Vito-Pulls.github.io/issues](https://github.com/Vito-Pulls/Vito-Pulls.github.io/issues)

## 🙏 Agradecimientos
- Alfonso Muñoz 
- Investigaciones de Michael F. Holick sobre síntesis de vitamina D
- Organización Mundial de la Salud por los datos de índice UV
- Comunidad científica por la investigación en fotobiología
- APIs de servicios meteorológicos y de geolocalización

---

**⚠️ Nota Importante**: Esta aplicación es una herramienta informativa y no sustituye el consejo médico profesional. Consulte con un profesional de la salud para decisiones relacionadas con la suplementación de vitamina D o exposición solar.
