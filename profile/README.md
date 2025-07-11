<div align="center">

# 🏃‍♂️ Clubion

**La plataforma definitiva para clubes de atletismo**

[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/)
[![Vue.js](https://img.shields.io/badge/Vue.js-3.x-green.svg)](https://vuejs.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-Latest-teal.svg)](https://fastapi.tiangolo.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

</div>

---

## 🎯 ¿Qué es Clubion?

Clubion es un **SAAS innovador** diseñado específicamente para clubes de atletismo que buscan optimizar la gestión de sus atletas, entrenamientos y competiciones. Combinamos robustez empresarial con simplicidad de uso.

### ✨ Características principales:
- 🏃‍♀️ **Gestión integral de atletas** - Perfiles, progreso, historial médico
- 🏋️‍♂️ **Planificación de entrenamientos** - Planes personalizados y seguimiento
- 🏆 **Gestión de competiciones** - Calendario, inscripciones, resultados
- 📊 **Analytics avanzados** - Reportes, métricas y análisis de rendimiento
- 🔒 **Multi-tenant seguro** - Aislamiento completo entre clubes

## 🚀 Modelos de Despliegue

### ☁️ SaaS en la Nube
Hosting gestionado con escalabilidad automática

### 🏢 On-Premise
Servidor dedicado con control total de datos

## 📦 Nuestros Repositorios

| Repositorio | Descripción | Tecnología |
|-------------|-------------|------------|
| **[clubion](https://github.com/clubion/clubion)** | 🏠 Repositorio principal | Docker, Scripts |
| **[clubion-backend](https://github.com/clubion/clubion-backend)** | 🔧 API REST | Python, FastAPI |
| **[clubion-frontend](https://github.com/clubion/clubion-frontend)** | 🎨 Web App | Vue.js, TypeScript |

## 🛠️ Stack Tecnológico
| **Componente** | **Descripción** |
|--------------- | --------------- |
| **Frontend**   |  Vue.js 3 + TypeScript + Tailwind CSS |
| **Backend**    |  Python FastAPI + PostgreSQL |
| **Deploy**     |  Docker + Kubernetes + Nginx |

## 🚀 Inicio Rápido

```bash
# Clonar repositorio principal
git clone --recursive https://github.com/clubion/clubion.git
cd clubion

# Configurar y levantar servicios
cp .env.example .env
./scripts/setup.sh
docker-compose up -d

# Acceder a la aplicación
# Frontend: http://localhost:3000
# API: http://localhost:8000/docs
```

## 🤝 Contribuir
¡Bienvenidas las contribuciones! Revisa nuestra [guía de contribución](../CONTRIBUTING) para comenzar.

### 🎯 Cómo contribuir:

1. 🍴 Fork el repositorio
2. 🌱 Crea una rama (`git checkout -b feature/nueva-funcionalidad`)
3. 💍 Commit cambios (`git commit -m 'Agregar nueva funcionalidad'`)
4. 🚀 Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. 🔄 Abre un Pull Request

### 📈 Roadmap 2025

* Q1: MVP con gestión de atletas y entrenamientos
* Q2: Competiciones y analytics avanzados
* Q3: App móvil y wearables
* Q4: IA predictiva y módulos enterprise

---
<div align="center">
¿Listo para revolucionar tu club de atletismo?
<a href="clubion.com">🚀 Comenzar</a> | <a href="docs.clubion.com">📚 Documentación</a> | <a href="discord.gg/clubion">💬 Discord</a>
Construido con ❤️ para la comunidad atlética
</div>