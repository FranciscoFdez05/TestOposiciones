# Cómo hostear en GitHub Pages

## Pasos para configurar:

1. **Sube el repositorio a GitHub**
   - Crea un nuevo repositorio en GitHub
   - Sube todo el contenido incluyendo el `index.html` y la carpeta `Preguntas/`

2. **Activa GitHub Pages**
   - Ve a Settings → Pages
   - En "Source", selecciona:
     - Branch: `main` (o `master` si es tu rama principal)
     - Folder: `/ (root)`
   - Guarda

3. **Accede desde iPad**
   - La web estará disponible en: `https://tu-usuario.github.io/TestOposiciones/`
   - Abre este URL en Safari desde tu iPad
   - Añádelo a la pantalla de inicio como App Web

## Características:

✅ Interfaz optimizada para iPad (vertical)
✅ 8 bloques (B1-B4, S1-S4)
✅ Temas desplegables dentro de cada bloque
✅ Validación en tiempo real de respuestas
✅ Indicador de progreso
✅ Navegación entre preguntas
✅ Responsive y sin necesidad de instalar nada

## Estructura de carpetas requerida:

```
TestOposiciones/
├── index.html
├── Preguntas/
│   ├── B1/
│   │   ├── Tema1.json
│   │   ├── Tema2.json
│   │   └── ...
│   ├── B2/
│   ├── B3/
│   ├── B4/
│   ├── S1/
│   ├── S2/
│   ├── S3/
│   └── S4/
└── README.md
```

Todos tus archivos JSON ya están en la estructura correcta.
