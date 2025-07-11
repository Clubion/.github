# Guía de Contribución - Clubion

¡Gracias por tu interés en contribuir a Clubion! Esta guía te ayudará a comenzar.

## 🎯 Cómo Contribuir

### 🐛 Reportar Bugs
- Usa nuestras [plantillas de issues](https://github.com/clubion/clubion/issues/new/choose)
- Incluye pasos para reproducir el bug
- Proporciona detalles del entorno

### 🚀 Proponer Nuevas Funcionalidades
- Abre un issue con la etiqueta `enhancement`
- Describe el problema que resuelve
- Incluye mockups o ejemplos si es posible

### 💻 Contribuir Código

#### Configuración de Desarrollo
```bash
# Clonar repositorio
git clone --recursive https://github.com/clubion/clubion.git
cd clubion

# Configurar entorno
cp .env.example .env
./scripts/setup.sh

# Levantar servicios
docker-compose up -d
```

### Flujo de Trabajo

1. **Fork** el repositorio
2. **Crea una rama** desde develop:
    ```bash
    git checkout -b feature/mi-nueva-funcionalidad
    ```
3. **Desarrolla** siguiendo nuestros estándares
4. **Escribe tests** para tu código
5. **Commit** siguiendo Conventional Commits:
    ```bash
    git commit -m "feat: agregar gestión de competiciones"
    ```
6. **Push** y abre un **Pull Request**

### 📋 Estándares de Código
#### Backend (Python)

* **PEP 8** para estilo de código
* **Type hints** obligatorios
* **Pytest** para testing
* **Coverage** mínimo del 90%

#### Frontend (Vue.js)

* **ESLint + Prettier** para formato
* **TypeScript** estricto
* **Composition API** de Vue 3
* **Vitest** para testing

#### Git

* **Conventional Commits** para mensajes
* **Ramas por feature** desde `develop`
* **Squash commits** antes del merge

### 🔍 Proceso de Review
#### Criterios de Aceptación

- [ ] Código sigue los estándares del proyecto
- [ ] Tests pasan (incluidos los nuevos)
- [ ] Documentación actualizada
- [ ] No hay conflictos de merge
- [ ] Aprobación de al menos 2 reviewers

#### Tipos de Changes

* **feat**: Nueva funcionalidad
* **fix**: Corrección de bug
* **docs**: Cambios en documentación
* **style**: Cambios de formato (no afectan funcionalidad)
* **refactor**: Refactorización de código
* **test**: Agregar o corregir tests
* **chore**: Tareas de mantenimiento

### 🏷️ Etiquetas de Issues
#### Por Tipo

* `bug` - Algo no funciona
* `enhancement` - Nueva funcionalidad
* `documentation` - Mejoras en docs
* `good first issue` - Ideal para principiantes

#### Por Prioridad

* `priority: high` - Crítico
* `priority: medium` - Importante
* `priority: low` - Puede esperar

#### Por Componente

* `backend` - API FastAPI
* `frontend` - Aplicación Vue.js
* `infrastructure` - Docker, deploy
* `database` - PostgreSQL, migraciones

#### 🎓 Recursos

[Documentación Técnica](https://docs.clubion.com)
[Arquitectura del Sistema](https://github.com/clubion/clubion/blob/main/docs/architecture.md)
[Guía de Configuración](https://github.com/clubion/clubion/blob/main/docs/setup.md)
[Discord Community](https://discord.gg/clubion)

## 🤝 Código de Conducta
Por favor, revisa nuestro [Código de Conducta](./CODE_OF_CONDUCT.md) antes de contribuir.
## ❓ ¿Necesitas Ayuda?

* 💬 **Discord**: [#contributors](https://discord.gg/clubion)
* 📧 **Email**: <mailto:dev@clubion.com>
* 🐛 **Issues**: [GitHub Issues](https://github.com/clubion/clubion/issues)

¡Esperamos tus contribuciones! 🚀