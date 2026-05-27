# primer-pr

Repositorio de demostración para aprender el flujo de Pull Requests con GitHub.

## ¿Qué es un Pull Request?

Un Pull Request (PR) es una solicitud para fusionar cambios de una rama a otra.
Es la forma principal de colaborar en proyectos de código abierto y en equipos.

## Flujo básico

1. Crea una rama nueva
2. Haz tus cambios
3. Abre un Pull Request
4. Espera revisión y aprobación
5. Los cambios se fusionan a `main`

## Comandos utiles

```bash
git checkout -b mi-rama   # crear rama
git add .                 # preparar cambios
git commit -m "mensaje"   # guardar cambios
git push origin mi-rama   # subir rama
gh pr create              # abrir PR
```
