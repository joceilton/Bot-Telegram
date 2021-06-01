# Bot-Telegram

O primeiro passo é criar o seu bot no Telegram. Para isso, você deverá abrir uma conversa com o BotFather (@Botfather). Você deverá seguir os seguintes passos:

Enviar /newbot.
Depois escolher um nome para seu bot e em seguida, um username para seu bot (esse username deve finalizar com bot).

Feito isso o BotFather irá te retornar a chave (token) que você usará na sua integração. Após isso, você deverá abrir um chat com seu bot criado, @{nome_do_bot}

E falar qualquer coisa. No meu caso, eu escrevi clear, e em seguida, ir no seu navegador e digitar https://api.telegram.org/bot{token}/getUpdates.

Exemplo: https://api.telegram.org/bot999999:HEUeuwyhsyeieow736d/getUpdates.

Você verá um json com um atributo chamado “id”. No exemplo abaixo está 999999999. Esse é o chat id.
