## 🌿 Flujo de Ramas (Branching Strategy)

Este repositorio utiliza un flujo de trabajo basado en **Git Flow** para la gestión de ramas.

###  Ramas principales

- `main`  
  Contiene versiones estables y listas para producción.

- `develop`  
  Rama de integración donde se combinan nuevas funcionalidades y correcciones antes de pasar a producción.

### 🐞 Rama de Bugfixes

Las correcciones de errores deben realizarse siguiendo este flujo:

1. Crear una rama desde `develop`:
   ```bash
   git checkout develop
   git pull origin develop
   git checkout -b bugfix/nombre-del-bug
2. Realizar correciones
    ```bash
     git add .
    git commit -m "Fix: descripción del error corregido"
3.Enviar a la rama el repositorio
   ```bash
  git push origin bugfix/nombre-del-bug

