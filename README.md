# Guaraipo Hotelaria

Painel demonstrativo para a gestão de uma pousada fictícia de Matinhos, PR.

## Como abrir

Baixe o arquivo `index.html` do repositório e abra-o no navegador. Também é possível servir a pasta com `python3 -m http.server 8000` e acessar `http://localhost:8000`. A demonstração usa HTML, CSS e JavaScript e dispensa instalação de dependências.

## O que testar

- Navegue pelo mapa de ocupação de sete dias. Clique em uma data livre para reservar ou em uma diária ocupada para abrir a reserva.
- Crie, edite e cancele reservas de hóspedes ou grupos. Cada reserva ocupa um quarto. Para grupos em vários quartos, registre cada quarto com o mesmo nome de grupo.
- Registre diária, valor recebido e comissão estimada. Use o filtro de canal para localizar reservas diretas, do Booking.com ou de outros canais.
- Confira o resumo financeiro. Ele soma o valor integral das reservas ativas que coincidem com o período escolhido. A ocupação considera somente as diárias dentro do período, incluindo a entrada e excluindo a saída.

Os dados iniciais são fictícios. As alterações ficam no armazenamento local do navegador. Os canais são informados manualmente e não há login, sincronização entre dispositivos ou integração com WhatsApp ou Booking.com.
