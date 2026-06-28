## Mi Portafolio - Jekyll + GitHub Pages

Página personal con perfil, proyectos destacados y experiencia.

### Requisitos

- Ruby 2.7+
- Bundler (`gem install bundler`)

### Instalación y ejecución local

```bash
# 1. Instalar dependencias
bundle install

# 2. Levantar el servidor Jekyll
bundle exec jekyll serve

# 3. Abre en el navegador
# http://localhost:4000
```

### Estructura del proyecto

```
.
├── _config.yml          # Config de Jekyll
├── index.md             # Página principal
├── md_pages/
│   └── about/index.md   # Página "Sobre mí"
├── _layouts/
│   └── default.html     # Layout principal
├── _includes/
│   ├── head.html        # Head con estilos
│   ├── header.html      # Navegación
│   └── footer.html      # Footer
├── _sass/
│   └── main.scss        # Estilos SASS
├── assets/
│   ├── css/styles.scss  # Import de SASS
│   └── images/avatar.jpg
└── Gemfile              # Dependencias
```

### Desplegar a GitHub Pages

1. Sube todo a un repo en GitHub
2. En Settings → Pages, selecciona "Deploy from a branch"
3. Branch: `main` (o `master`), folder: `/ (root)`
4. GitHub compilará automáticamente

Tu sitio estará en: `https://tu-usuario.github.io/nombre-repo`

O si el repo es `username.github.io`:
`https://username.github.io`

### Personalizaciones

- Edita `_config.yml` con tus datos
- Modifica colores en `_sass/main.scss` (variables `:root`)
- Cambia `assets/images/avatar.jpg` por tu foto
- Actualiza links en `_includes/header.html` y `_includes/footer.html`

### Notas

- Los estilos están incrustados en `_includes/head.html` para simplicidad
- Usa Markdown en `.md` files — Jekyll lo convierte automáticamente a HTML
- Los SASS se compilan automáticamente con Jekyll

¡Listo para GitHub Pages! 🚀
