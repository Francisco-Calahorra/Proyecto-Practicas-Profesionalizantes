# 📘 Guía para trabajar con GitHub en el proyecto

Este documento explica de forma sencilla **cómo usar GitHub paso a paso** en nuestro proyecto de Prácticas Profesionalizantes. Nadie necesita ser experto en Git: con esta guía todos podremos colaborar de manera ordenada.

---

## 🔹 1. Requisitos previos

- Tener **una cuenta en GitHub** (gratis).
- Tener instalado **Git** en la computadora.

👉 [Descargar Git](https://git-scm.com/downloads)

---

## 🔹 2. Clonar el repositorio (descargarlo a tu PC)

En la terminal (símbolo del sistema, PowerShell o Git Bash):

```bash
git clone https://github.com/<usuario>/<nombre-del-repo>.git
cd <nombre-del-repo>
```

---

## 🔹 3. Crear una rama de trabajo

⚠️ **Nunca trabajamos directo en main**. Cada tarea se hace en una rama nueva.

```bash
git checkout -b feature/nombre-de-la-tarea
```

**Ejemplo:**
```bash
git checkout -b feature/crud-alumnos
```

---

## 🔹 4. Hacer cambios

1. **Editá** el código o archivos según la tarea asignada.
2. **Guardá** los cambios.
3. **Ejecutá** estos comandos:

```bash
git add .
git commit -m "Descripción corta del cambio realizado"
```

**Ejemplo:**
```bash
git commit -m "feat: implementar CRUD de alumnos"
```

---

## 🔹 5. Subir los cambios a GitHub

```bash
git push origin feature/nombre-de-la-tarea
```

Esto envía tu rama al repositorio en GitHub.

---

## 🔹 6. Abrir un Pull Request (PR)

1. **Ir** al repositorio en GitHub.
2. Aparecerá un cartel: **"Compare & pull request"**.
3. **Completar** la plantilla de PR.
4. **Esperar** revisión → aprobación → merge a main.

---
