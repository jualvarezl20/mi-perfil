# Mi perfil

Sitio web personal de Juan Esteban Alvarez. Presento mi perfil profesional, formación, experiencia, conocimientos y datos de contacto, con un diseño oscuro construido con HTML y Tailwind CSS.

## Contenido del sitio

- **Inicio** (`index.html`): presentación, foto, enlace al portafolio, descarga de la hoja de vida y contacto.
- **Portafolio** (`paginas/portafolio.html`): página preparada para mostrar proyectos; actualmente no tiene contenido.
- **Conocimientos** (`paginas/conocimientos.html`): herramientas y conocimientos técnicos.
- **Educación** (`paginas/educacion.html`): formación académica y cursos.
- **Experiencia** (`paginas/experiencia.html`): trayectoria laboral.
- **Referencias** (`paginas/referencias.html`): referencias profesionales.

Las páginas comparten navegación y un pie con información de contacto y enlaces profesionales.

## Estructura

```text
mi-perfil/
├── index.html                         # Página principal
├── paginas/                           # Secciones internas del sitio
├── imagenes/foto.png                  # Foto del perfil
├── Hoja_de_Vida_Juan_Esteban_Alvarez.pdf # Hoja de vida descargable
├── src/input.css                      # Entrada de Tailwind CSS
├── output.css                         # CSS generado por Tailwind
├── styles.css                         # Variables de color del sitio
├── package.json                       # Metadatos y dependencias de desarrollo
└── package-lock.json                  # Versiones fijadas de dependencias
```

## Tecnologías

- HTML para la estructura y el contenido.
- Tailwind CSS 4 para los estilos utilitarios.
- CSS propio para las variables de color.
- Fuente Manrope cargada desde Google Fonts.

## Uso local

Necesitas Node.js y npm para instalar Tailwind o regenerar los estilos.

1. Instala las dependencias:

   ```bash
   npm install
   ```

2. Abre `index.html` en un navegador para ver el sitio. También puedes servir la carpeta con cualquier servidor web estático.

3. Si modificas `src/input.css` o las clases Tailwind del HTML, regenera `output.css`:

   ```bash
   npx @tailwindcss/cli -i ./src/input.css -o ./output.css
   ```

   Para mantener la compilación activa mientras trabajas, agrega `--watch` al comando.

