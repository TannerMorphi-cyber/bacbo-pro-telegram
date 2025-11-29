# Bac Bo Analyzer + Telegram Bot

## Variables de entorno (Secrets en Replit)
- BOT_TOKEN → tu bot de Telegram
- CHAT_ID → tu chat o canal
- SECRET_HEADER → cualquier contraseña (ej: miClave123)

## Uso rápido
curl -X POST -H "Content-Type: application/json" -d '{"player":7,"banker":9}' http://0.0.0.0:8000/new_roll
curl -X POST -H "X-Secret: miClave123" http://0.0.0.0:8000/send_signal
