# plann.er
Plann.er é um projeto que tem como principal objetivo ser um planejador de viagens, o qual é possível compartilhar com outras pessoas, convidando-as por e-mail. Possui opções como adicionar atividades a serem realizadas, bem como sua data e horário e adicionar links importantes para a viagem. Ao aceitar o convite para participar da viagem, todos os participantes poderão ver as atividades a serem realizadas, bem como os links importantes.

O projeto foi feito a partir do evento NLW Journey promovido pela Rocketseat.

## Routes

- [x] Create new trip (`POST /trips`);
- [x] Register user (`POST /users`);
- [x] Authenticate user by magic link (`GET /authenticate`);
- [x] Confirm trip (`PATCH /trips/:id/confirm`);
- [x] Trip details (`GET /trips/:id`);
- [x] Update trip (`PUT /trips/:id`);
- [x] Get trip activities (`GET /trips/:id/activities`);
- [x] Create trip activity (`POST /trips/:id/activities`);
- [x] Get trip links (`GET /trips/:id/links`);
- [x] Create trip link (`POST /trips/:id/links`);
- [x] Get the trip participants (`GET /trips/:id/participants`);
- [x] Create a new invite (`POST /trips/:id/invites`);
- [x] Get user confirmation status for trip (`GET /trips/:id/confirmation-status`);
