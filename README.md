# Sistema de Sorteios JB PIX

Alterações aplicadas:

- Nome principal trocado para **JB PIX**.
- Tema alterado para **vermelho com preto**.
- Criadas páginas para:
  - `/unidades/` — unidades de 0 a 9
  - `/dezenas/` — dezenas de 00 a 99
  - `/grupos/` — grupos de 01 a 25
- Painel admin mantém as funções existentes e ganhou:
  - excluir sorteio apagando automaticamente participantes, reservas, WhatsApps bloqueados e ganhadores daquele sorteio;
  - pausar sorteio sem esconder do público: ele aparece, mas não deixa fazer escolhas;
  - filtro por número para encontrar quem escolheu determinada unidade/dezena/grupo;
  - filtro rápido para selecionar ganhador pelo número escolhido;
  - botão para excluir histórico de ganhadores;
  - botão para excluir histórico de participantes e liberar escolhas;
  - campos de nome da loteria, horário/descrição e prêmio em branco para preencher pelo admin.

## Publicação

Envie a pasta inteira para sua hospedagem/Vercel. O arquivo principal redireciona para `/dezenas/`.

## Admin

O painel admin continua em `/admin/` ou em qualquer página usando o botão **Admin**.
