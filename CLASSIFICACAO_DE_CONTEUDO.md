# CLASSIFICACAO DE CONTEUDO

CLASSIFICACAO: PUBLICO / INTERNO / SIGILOSO / SECRETO / COFRE / MILITAR-SAGRADO SENSIVEL
AUTORIZACAO: conforme o conteudo
PUBLICACAO: publicar somente versao permitida ou sanitizada
ACESSO: minimo necessario
REVISAO: humana obrigatoria quando houver risco

## Regra

Todo arquivo sensivel deve comecar com classificacao.

## Modelo

```text
CLASSIFICACAO: [PUBLICO / INTERNO / SIGILOSO / SECRETO / COFRE / MILITAR-SAGRADO SENSIVEL]
AUTORIZACAO: [publica / equipe / fundador / cofre / revisao humana]
PUBLICACAO: [pode publicar / nao publicar / publicar somente versao sanitizada]
ACESSO: minimo necessario
REVISAO: humana obrigatoria quando cabivel
```

## Banco de dados

Dumps, backups, seeds reais, dados pessoais, dados juridicos, documentos, logs sensiveis e qualquer dado real devem ser tratados como **SIGILOSO**, **SECRETO** ou **COFRE**, conforme o caso.

© Jus 9 Tecnologia Juridica - software livre, autoria preservada.
