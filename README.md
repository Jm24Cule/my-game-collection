# 🎮 GameVault

PWA personal para gestionar mi colección de videojuegos físicos. Permite consultar el catálogo desde el iPhone en tiempo real, ideal para evitar duplicados al comprar en tiendas de segunda mano.

## Características

- 📋 Catálogo completo organizado por consola (PS2 → PS5, Xbox 360 → Series, Nintendo, PC...)
- 🔍 Búsqueda instantánea por título o género
- 🖼️ Vista lista y vista grid con carátulas
- 📷 Escáner de código de barras con búsqueda automática en IGDB
- ✏️ Edición completa de cada juego: puntuación, estado, carátula, vídeo de gameplay
- 📥 Importación y actualización masiva desde CSV
- ☁️ Sincronización en la nube vía Supabase (funciona en todos los dispositivos)
- 🔐 Acceso protegido con PIN personal
- 📱 Instalable en iPhone como app nativa (PWA)

## Stack

- HTML / CSS / JavaScript (vanilla) — un único archivo `index.html`
- [Supabase](https://supabase.com) — base de datos PostgreSQL en la nube + Edge Functions
- [IGDB API](https://api-docs.igdb.com) — base de datos de videojuegos (búsqueda por barcode y nombre)
- [ZXing](https://github.com/zxing-js/library) — lectura de códigos de barras desde la cámara
- Desplegado en GitHub Pages

## Uso

Accede desde Safari en iPhone, pulsa **Compartir → Añadir a pantalla de inicio** y úsala como cualquier app. En escritorio funciona en cualquier navegador moderno.

## Importación CSV

Consulta el manual incluido en este repositorio para importar juegos en masa desde Excel.

## Estado del proyecto

✅ Funcional y en uso activo

## Licencia

MIT
