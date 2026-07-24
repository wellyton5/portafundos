# Calculadora de Lucro — Limpeza + Nextdoor

Página estática de arquivo único que estima o **lucro real por faxina** para
um serviço de limpeza residencial. Considera:

- Custo da assinatura do Nextdoor Opportunity Alerts e taxa de conversão
- Preço cobrado por faxina
- Custo de materiais de limpeza rateados por casa
- Deslocamento (tempo × velocidade × custo por milha)
- Ajudantes (múltiplos, com valor individual por dia)

Ao final apresenta lucro líquido por faxina e projeção mensal (receita bruta,
lucro líquido, quantas faxinas para empatar a assinatura, clientes esperados).

Sem dependências, sem build, sem framework — apenas `index.html`.

## Publicação

Servido via GitHub Pages a partir da branch `main`, raiz do repositório.

## Atualizar

Editar `index.html` localmente, commitar e dar `git push`. O deploy é
automático (~1–3 min).
