# Registro de Desarrollo - Fase 2 y 3: Repositorio Remoto y Colaboración

**Proyecto:** Buzón CUC Escucha  
**Curso:** Buenas Prácticas de Desarrollo de Software  
**Docente:** Ing. Lorena Redondo G.  
**Semestre:** 2026-2  

---

## 1. Conexión con GitHub (Fase 2)
Se vinculó el repositorio local con el repositorio remoto en GitHub para mantener centralizado el código del proyecto:

1. Configuración del remoto `origin`:
   ```bash
   git remote add origin https://github.com/ALTF4xd/buzon-cuc-escucha.git
   git remote -v
   ```

2. Publicación de la rama `main`:
   ```bash
   git push -u origin main
   ```

3. Verificación de sincronización:
   ```bash
   git status
   ```

---

## 2. Trabajo en Equipo (Fase 3)
El flujo colaborativo para los integrantes del grupo se organiza de la siguiente manera:

1. Clonar el repositorio en local:
   ```bash
   git clone https://github.com/ALTF4xd/buzon-cuc-escucha.git
   cd buzon-cuc-escucha
   ```

2. Crear rama independiente para cada requerimiento:
   ```bash
   git switch -c feature/<nombre-tarea>
   ```

3. Desarrollo de funcionalidades:
   - **Rama de estilos:** Ajustes visuales en CSS e integración local con `main`.
   - **Rama de formulario:** Incorporación de nuevos campos e integración mediante Pull Request en GitHub.
