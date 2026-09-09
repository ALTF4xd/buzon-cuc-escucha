# Registro de Desarrollo - Fase 1: Configuración Local

**Proyecto:** Buzón CUC Escucha  
**Curso:** Buenas Prácticas de Desarrollo de Software  
**Docente:** Ing. Lorena Redondo G.  
**Semestre:** 2026-2  

---

## 1. Resumen de la Fase
En esta primera etapa se preparó la estructura base del micrositio para la recopilación de sugerencias estudiantiles en la Facultad de Ingeniería. Se implementó el maquetado semántico en HTML5, la hoja de estilos en CSS3 y se inicializó el control de versiones local con Git en la rama principal `main`.

---

## 2. Estructura del Proyecto
```text
buzon-cuc-escucha/
├── css/
│   └── styles.css
├── js/
│   └── app.js
├── img/
├── index.html
└── README.md
```

---

## 3. Comandos Ejecutados en Terminal

1. Creación de directorios y archivos base:
   ```bash
   mkdir buzon-cuc-escucha
   cd buzon-cuc-escucha
   mkdir css js img
   touch index.html css/styles.css js/app.js README.md
   ```

2. Inicialización del repositorio y definición de rama principal:
   ```bash
   git init
   git branch -M main
   ```

3. Preparación de cambios en el área de staging:
   ```bash
   git add .
   git status
   ```

4. Registro del commit inicial:
   ```bash
   git commit -m "feat: inicializar estructura y maquetacion base del buzon CUC"
   ```

5. Verificación del historial:
   ```bash
   git log --oneline
   ```
