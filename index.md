---
layout: default
title: "Inicio"
---

# Portal Carnet Cósmico

- **Formulario CC**: [Abrir](https://tu-dominio-o-formulario)
- **Agenda**: [Eventos](https://tu-calendario)
- **Comunidad**: [Unirme](https://tu-grupo)

## Páginas

{% raw %}{% for p in site.paginas %}
- [{{ p.title }}]({{ p.url | relative_url }})
{% endfor %}{% endraw %}
