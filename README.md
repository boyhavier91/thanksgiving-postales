# Postales de Thanksgiving

- `index.html` — la postal animada que abre cada contacto (`?c=CODIGO`). `?demo=1` muestra un ejemplo.
- `enviar.html` — panel privado para importar contactos, escribir dedicatorias (con IA) y enviar por SMS, WhatsApp o Messenger.
- Backend: Supabase (tablas `cards`, `owner_settings`, función `open_card`, edge function `dedicatoria`).
