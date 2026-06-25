# 🐻 Baby Shower · Martín Bolívar Velásquez

Invitación animada para el baby shower de Martín.  
Sitio estático con HTML + CSS + JS puro. Sin dependencias ni build step.

---

## 🚀 Despliegue en Vercel (paso a paso)

### 1. Subir el repositorio a GitHub

```bash
# En la carpeta del proyecto:
git init
git add .
git commit -m "feat: invitación baby shower Martín"

# Crear repo en github.com y luego:
git remote add origin https://github.com/TU_USUARIO/baby-shower-martin.git
git branch -M main
git push -u origin main
```

### 2. Conectar con Vercel

1. Ir a [vercel.com](https://vercel.com) e iniciar sesión con GitHub
2. Clic en **"Add New Project"**
3. Importar el repo `baby-shower-martin`
4. Framework Preset: **Other** (ya detecta el `vercel.json`)
5. Clic en **Deploy** ✅

### 3. URL personalizada (opcional)

Desde el dashboard de Vercel → Settings → Domains → agregar tu dominio propio.

---

## 📁 Estructura

```
baby-shower-martin/
├── index.html     ← Todo el sitio (HTML + CSS + JS en un solo archivo)
├── vercel.json    ← Configuración de despliegue
├── .gitignore
└── README.md
```

---

## ✏️ Personalización

| Dato             | Dónde cambiar en `index.html`                        |
|------------------|------------------------------------------------------|
| Nombre invitado  | Buscar `Martín Bolívar Velásquez`                    |
| Fecha            | Buscar `28`, `Junio`, `2026`, `3:00 pm`              |
| Dirección        | Buscar `Unidad Residencial Serrana`                  |
| Link de mapa     | Atributo `href` del `<a class="btn-mapa">`           |
| Link de regalos  | Atributo `href` del `<a class="btn-regalo">`         |

---


## 📱 Miniatura en WhatsApp

La imagen de previsualización está embebida directamente en el HTML como `base64`
en los meta tags `og:image`. Esto permite que funcione en sitios estáticos sin
necesidad de un servidor de imágenes externo.

> **Nota:** WhatsApp cachea las previsualizaciones. Si ya compartiste el link antes,
> usa [https://developers.facebook.com/tools/debug/](https://developers.facebook.com/tools/debug/)
> para forzar la actualización del cache.

## 🎨 Paleta de colores

| Color              | Hex       | Uso                    |
|--------------------|-----------|------------------------|
| Crema fondo        | `#F5EFE4` | Background general     |
| Marrón dorado      | `#7B5B1A` | Títulos, acentos       |
| Marrón oscuro      | `#4A2E0A` | Botones, nombre        |
| Arena claro        | `#E8D5C4` | Globos, detalles       |
| Rosa palo          | `#D4A99A` | Banderines, globos     |
| Ocre               | `#C9B08A` | Separadores, bordes    |
