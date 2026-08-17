# Rota Certa

Aplicativo estático e responsivo para montar propostas de viagem com passagem aérea, taxas, bagagem, assentos, hotel e clima.

## Como usar

Abra `index.html` em qualquer navegador. Preencha origem, destino, datas, passageiros, orçamento e prioridade; o cálculo é atualizado ao clicar em **Calcular proposta**.

É possível escolher voo de ida e volta ou somente ida, montar o pacote completo ou desmarcar passagem/hotel. O total é recalculado e os botões levam aos fornecedores para concluir reserva e pagamento.

A central multifuente apresenta 15 opções de pesquisa de passagens (comparadores, agências e companhias oficiais) e 9 fontes de hotelaria. Fotos reais do hotel são abertas na ficha pública do estabelecimento para evitar imagens ilustrativas enganosas.

Origem e destino aceitam cidade ou código IATA, com sugestões de aeroportos do mundo inteiro. A proposta exibe visualmente cinco estimativas ordenadas por preço, indicando escalas, duração, fonte, menor preço e trecho mais usado. A hospedagem usa automaticamente a data de ida como check-in, sem pedir uma data separada.

A busca de aeroportos utiliza uma cópia local compacta da base internacional `airportsdata`, com 7.884 aeroportos que possuem código IATA. Consulte `AIRPORTS-LICENSE` para atribuição e licença.

## Importante

O projeto é um simulador visual. Ele não consulta inventário ou preço em tempo real, não processa pagamento e não emite reservas. Antes da compra, confirme valores, disponibilidade, clima, cancelamento e reembolso diretamente com companhias aéreas e hotéis.

## Publicação

Por ser uma página HTML única, pode ser hospedada gratuitamente com GitHub Pages.
