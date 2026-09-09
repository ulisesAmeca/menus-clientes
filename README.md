# menus-clientes

Repositorio con los menús digitales de todos los locales clientes.

## Estructura

```
menus-clientes/
├── index.html              ← página raíz (opcional, ver abajo)
├── _plantilla/
│   └── index.html          ← copia esto para cada cliente nuevo
├── la-casona-54/
│   └── index.html          ← menú de La Casona 54
├── typica/
│   └── index.html          ← (ejemplo del siguiente cliente)
└── nombre-cliente/
    └── index.html
```

## Cómo agregar un nuevo cliente

1. Copia la carpeta `_plantilla/` y renómbrala con el nombre del negocio (sin espacios, minúsculas, guiones en vez de espacios). Ejemplo: `cafe-typica`.
2. Abre el `index.html` de esa carpeta nueva y reemplaza:
   - Nombre del negocio, dirección, horario (header y footer)
   - Categorías y platillos (secciones `<section>`)
   - Colores en `:root { ... }` si quieres una paleta distinta a la de "La Casona 54" (recomendado, para que cada cliente se sienta único)
3. Sube la carpeta al repositorio (arrastra y suelta en GitHub, o usa git si ya lo manejas).
4. La URL final de ese cliente queda:
   ```
   https://TU-USUARIO.github.io/menus-clientes/nombre-cliente/
   ```
5. Prueba esa URL desde el celular y prográmala en la tarjeta NFC del local.

## Notas

- Cada carpeta es independiente — puedes editar el menú de un cliente sin tocar los demás.
- GitHub Pages solo necesita estar activado **una vez** por repositorio (no por carpeta) — ver pasos de configuración en Settings → Pages, rama `main`, carpeta `/ (root)`.
- Si quieres una página de bienvenida en la raíz (`https://TU-USUARIO.github.io/menus-clientes/`) que liste todos tus clientes, se puede agregar un `index.html` general — pídelo si lo necesitas.
