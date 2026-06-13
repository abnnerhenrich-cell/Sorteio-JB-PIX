# JB PIX Sorteios

Sistema de sorteios com painel admin protegido por Firebase Authentication usando e-mail e senha.

## Antes de publicar

1. No Firebase, abra Authentication.
2. Ative o método E-mail/senha.
3. Em Users, crie o usuário admin:
   kellymenezes.promotorajb@gmail.com
4. Defina uma senha forte.
5. Em Cloud Firestore > Regras, cole o conteúdo do arquivo `firebase-rules.txt` e clique em Publicar.
6. Publique os arquivos no GitHub/Firebase Hosting.

## Importante

O visitante consegue apenas participar do sorteio.
O admin logado consegue criar, pausar, excluir sorteios, limpar participantes e confirmar ganhadores.
