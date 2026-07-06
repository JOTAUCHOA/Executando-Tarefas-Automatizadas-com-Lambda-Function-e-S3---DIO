Esse projeto é a entrega do terceiro desafio do bootcamp da DIO de AWS

Ele mostra como utilizar uma aplicação, com um dóminio personalizado. Onde o o usuário vai acessar e colocar 
uma informação e receber uma notificação, a qual utilizando um SNS para o envio de mensagem e o que dispará
a mensagem é uma função lambda.

A VM tem acesso ao bucket através de uma role que possui a permissão de adicionar documentos nele.

A rede da VM está atrelada uma subnet, security group e qual ele pode, opcionalmente se conectar ao route 53, com um domínio.
