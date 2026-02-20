📑 Regras de Negócio

Sistema de Agendamento de Hotel

Abaixo estão as principais regras de negócio do sistema:

🏨 Reservas

RN01 – A reserva só poderá ser realizada caso o quarto esteja disponível nas datas selecionadas.

RN02 – A data de check-out deve ser obrigatoriamente posterior à data de check-in.

RN03 – O sistema não deve permitir reservas com data de check-in anterior à data atual.

RN04 – O valor total da reserva deve ser calculado com base na quantidade de diárias e no valor da diária do quarto.

RN05 – Cada reserva deve estar vinculada a apenas um usuário cadastrado.

👤 Usuários

RN06 – O e-mail do usuário deve ser único no sistema.

RN07 – O usuário deve estar autenticado para realizar uma reserva.

RN08 – O usuário só pode cancelar ou visualizar reservas feitas por ele.

❌ Cancelamento

RN09 – O cancelamento só poderá ser realizado até 24 horas antes da data de check-in.

RN10 – Após o cancelamento, o quarto deve voltar automaticamente para a lista de disponíveis.
