# Flujo editorial del blog de Oscar Bonilla

## Método elegido
Los artículos se preparan con ChatGPT y se incorporan al repositorio GitHub `oscarbonilla1210-eng/oscar-bonilla-web`. No se instalará un CMS visual en esta etapa.

## Flujo para cada publicación
1. Definir el tema, la audiencia, la intención de búsqueda y la llamada a la acción.
2. Preparar con ChatGPT el artículo, el título SEO, la descripción meta, el slug, la categoría, los enlaces internos y el texto alternativo de la imagen si corresponde.
3. Crear una página HTML estática dentro de `blog/articulos/`, con idioma español, diseño adaptable, canonical, metadatos sociales y encabezados semánticos.
4. Actualizar `blog/index.html` con una tarjeta que enlace al artículo.
5. Crear una rama de revisión y una solicitud de cambios (pull request). Revisar contenido, enlaces, visualización móvil y datos antes de fusionar.
6. Tras la aprobación, fusionar a `main`; Netlify publicará mediante su despliegue continuo.
7. Añadir la URL a `sitemap.xml` y, después de publicar, solicitar indexación en Google Search Console cuando esté configurado.

## Categorías iniciales
- Capacitación empresarial, conferencias e IA aplicada
- Marketing digital y Ads
- Finanzas y auditoría forense

## Criterios editoriales
- Priorizar experiencia práctica, ejemplos propios y recomendaciones verificables.
- Evitar promesas de resultados garantizados y afirmaciones no demostrables.
- Un objetivo de búsqueda principal por artículo; usar palabras clave con naturalidad.
- Añadir enlaces internos a servicios y contacto cuando aporten valor.
- Usar imágenes propias o con licencia adecuada; optimizarlas en WebP cuando sea viable.
- No publicar datos confidenciales de clientes, estudiantes, empleadores ni terceros.

## Limitación técnica actual
El sitio es HTML estático y no convierte Markdown en páginas web automáticamente. Por eso, en este flujo cada artículo se genera como HTML listo para el sitio. Si el volumen editorial crece, se podrá evaluar un generador estático compatible con contenido Markdown, sin necesidad de activar un CMS ahora.

## Lista de comprobación por artículo
- [ ] Título claro y único
- [ ] Descripción meta específica
- [ ] Un H1 y jerarquía lógica de H2/H3
- [ ] URL legible y canonical correcta
- [ ] Enlaces internos y externos comprobados
- [ ] Diseño y enlaces revisados en móvil
- [ ] Imagen optimizada y texto alternativo, si aplica
- [ ] Artículo enlazado desde el índice del blog y sitemap actualizado
- [ ] Revisión del usuario antes de publicar
