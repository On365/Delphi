# Delphi

Notificacoes.zip - Contem três projetos:
Um servidor para envio de notificações PUSH para android
Um App Android que recebe as notificações Push
Um servidor REST para receber os DeviceTokens

Usa um banco Sqlite3 para guardar os Ids.
Para usar é preciso:

configurar na aplicação servidora o Serverkey
Configurar o GCMAPPID no componente kinveyProvider na aplicação mobile. Uso o KinveyProvider apenas para obter o Token.


