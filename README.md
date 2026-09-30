# lunar-watchdog

Vigia externo do painel Lunar: a cada 5 min testa as URLs de `targets.txt` de fora das VPS e avisa no Telegram
quando algo cai ou volta (secrets `TELEGRAM_BOT_TOKEN` e `TELEGRAM_CHAT_ID`). Sem Telegram, a execução falha na
primeira detecção e o GitHub manda e-mail.
