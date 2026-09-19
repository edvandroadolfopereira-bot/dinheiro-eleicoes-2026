# O dinheiro das Eleicoes 2026 e quem sao os seus beneficiarios

Levantamento semanal a partir dos **dados abertos do Tribunal Superior Eleitoral**, pela visao de um
perito judicial contabil.

- Painel: https://edvandroadolfopereira-bot.github.io/dinheiro-eleicoes-2026/
- Autoria: Edvandro Adolfo Pereira, perito judicial contabil. Instagram @edvandroadolfo e @gruponomos

## O que tem aqui

| Pasta | Conteudo |
|---|---|
| index.html | o painel completo, interativo |
| dados/ | planilhas e CSV com candidatos, fornecedores, doadores e fundos publicos |
| cartoes/ | as imagens publicadas nas redes, em 4:5 e 9:16 |

## Fonte

Brasil. Tribunal Superior Eleitoral. Dados abertos eleitorais, Eleicoes Gerais de 2026:
consulta de candidatos, bens de candidatos, prestacao de contas de candidatos e de orgaos
partidarios. https://dadosabertos.tse.jus.br

Consulta individual por candidato: https://divulgacandcontas.tse.jus.br

## O que estes numeros NAO dizem

- A prestacao de contas e **parcial** e muda todos os dias ate o fim do periodo eleitoral.
- O TSE **nao publica renda** de candidato. Existem bens declarados e ocupacao.
- Vice e suplente aparecem sem receita porque a conta de campanha e do titular da chapa.
- **CPF vai mascarado** nos arquivos deste repositorio. O dado e publico na fonte oficial,
  mas republicar documento de pessoa fisica em massa e outra coisa. CNPJ fica inteiro,
  porque identifica empresa.
- Patrimonio e valor declarado pelo proprio candidato. Bem isolado acima de R\$ 50 milhoes
  sai assinalado como atipico, sem correcao de valor, porque o valor exato nao e publicado.
- Votos so existem depois da votacao de 4 de outubro de 2026.

Cada extracao carrega no painel a data e a hora em que foi feita.
