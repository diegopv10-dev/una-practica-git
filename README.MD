# Guía de Colaboración

Gracias por tu interés en contribuir a este proyecto. Sigue los pasos a continuación para colaborar de forma ordenada.

## 🚀 Cómo contribuir

### 1. Haz un fork del repositorio

Ve a la página del repositorio en GitHub y haz clic en el botón **Fork** (esquina superior derecha). Esto creará una copia del repositorio en tu propia cuenta.

### 2. Clona tu fork

Clona el repositorio que acabas de forkear a tu máquina local:

```bash
git clone https://github.com/TU-USUARIO/NOMBRE-DEL-REPO.git
cd NOMBRE-DEL-REPO
```

> Reemplaza `TU-USUARIO` y `NOMBRE-DEL-REPO` con los datos correspondientes.

### 3. Crea una rama nueva

Nunca trabajes directamente sobre `main`. Crea una rama con un nombre descriptivo de la tarea que vas a realizar:

```bash
git checkout -b tipo/nombre-descriptivo
```

Ejemplos de nombres de rama:

| Tipo       | Ejemplo                          |
|------------|-----------------------------------|
| Nueva funcionalidad | `feature/login-usuario`     |
| Corrección de bug   | `fix/error-formulario`      |
| Documentación       | `docs/actualizar-readme`    |

### 4. Realiza tus cambios y haz commits

Realiza los cambios necesarios y confirma tu trabajo con mensajes claros:

```bash
git add .
git commit -m "Descripción breve y clara del cambio"
```

### 5. Sube los cambios a tu fork

```bash
git push origin tipo/nombre-descriptivo
```

### 6. Crea un Pull Request (PR)

1. Ve a tu fork en GitHub.
2. Haz clic en **Compare & pull request**.
3. Escribe un título y una descripción clara indicando **qué hiciste y por qué**.
4. Envía el PR hacia la rama `main` (o la rama base que corresponda) del repositorio original.
5. Espera revisión y comentarios del equipo antes de que sea aprobado y fusionado (merge).

## ✅ Buenas prácticas

- Mantén tu rama actualizada con la rama principal antes de crear el PR:
  ```bash
  git fetch upstream
  git merge upstream/main
  ```
- Un PR = un cambio/tarea específica (evita mezclar varias funcionalidades en un solo PR).
- Escribe mensajes de commit claros y descriptivos.
- Revisa que el código funcione y pase las pruebas antes de enviar el PR.

## 📝 Resumen rápido

```
Fork → Clonar → Crear rama → Cambios/Commits → Push → Pull Request
```

¡Gracias por colaborar! 🎉