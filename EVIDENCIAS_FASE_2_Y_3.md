# Evidencias - Fase 2 y Fase 3: Repositorio Remoto y Colaboración en GitHub

**Proyecto:** Buzón CUC Escucha  
**Asignatura:** Buenas Prácticas de Desarrollo de Software  
**Docente:** Ing. Lorena Redondo G.  
**Estudiante:** Luis Guillermo Jimenez Samper (`ALTF4xd`)  
**URL del Repositorio:** [https://github.com/ALTF4xd/buzon-cuc-escucha](https://github.com/ALTF4xd/buzon-cuc-escucha)  

---

## 📌 FASE 2: Conexión del Repositorio Local con GitHub

### 1. Registro de Acciones
1. Se creó el repositorio público denominado `buzon-cuc-escucha` en GitHub sin inicializar archivos para preservar la estructura local.
2. Se vinculó el repositorio local con el remoto mediante:
   ```bash
   git remote add origin https://github.com/ALTF4xd/buzon-cuc-escucha.git
   ```
3. Se verificó el enlace con:
   ```bash
   git remote -v
   ```
4. Se envió la rama principal `main` al servidor remoto estableciendo seguimiento:
   ```bash
   git push -u origin main
   ```
5. Se verificó la sincronización con:
   ```bash
   git status
   # Salida: Your branch is up to date with 'origin/main'.
   ```

### 📸 Capturas Registradas de la Fase 2
- **`Captura_2.1_Creacion_Repositorio_GitHub.jpg`:** Formulario de creación del repositorio en GitHub (nombre, visibilidad pública).
- **`Captura_2.1b_Configuracion_Rapida_GitHub.jpg`:** Instrucciones de bienvenida y comandos remotos en GitHub.
- **`Captura_2.2_Vinculacion_Remoto_y_Push_Main.png`:** Consola Git Bash mostrando `git remote add`, `git remote -v`, `git push -u origin main` y paridad con `origin/main`.

---

## 👥 FASE 3: Gestión de Colaboradores del Proyecto

### 1. Procedimiento Requerido
1. Ingresar a: `https://github.com/ALTF4xd/buzon-cuc-escucha/settings/access`
2. Hacer clic en **Add people**.
3. Buscar a los integrantes del equipo por su usuario de GitHub o correo institucional.
4. Enviar la invitación formal.
5. Tomar la **Captura 3.1** mostrando las invitaciones en estado *Pending Invite*.

### 2. Instrucciones para los Compañeros de Equipo
Para que los compañeros continúen con las siguientes fases (**Fase 4: Rama 1 de estilos** y **Fase 5: Rama 2 de formulario y Pull Request**), deben:
1. Aceptar la invitación recibida en su correo o panel de GitHub.
2. Clonar el repositorio en su computadora local:
   ```bash
   git clone https://github.com/ALTF4xd/buzon-cuc-escucha.git
   cd buzon-cuc-escucha
   ```
3. Crear su rama independiente para trabajar:
   ```bash
   git switch -c feature/nombre-funcionalidad
   ```
