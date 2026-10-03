# Contexto da pesquisa

## Tema e problema

Classificação seletiva com modelos de linguagem de grande escala (LLMs) em documentos do setor público.
LLMs atingem bom desempenho em classificação documental, mas não eliminam o erro. Em um processo público,
é preciso decidir **quando a classificação proposta pelo modelo pode ser aceita automaticamente e quando
deve ser encaminhada à revisão humana**.

## Recorte

- **Objeto:** classificação de documentos institucionais em português.
- **Referência:** uma base pública que já possui classificação oficial atribuída por especialistas, usada
  como gabarito para medir acertos e erros.
- **Modelos:** modelos de uso real na administração pública, acessados por API.
- **Contexto acadêmico:** mestrado profissional em Administração Pública (IDP), ênfase em Ciência de
  Dados e Inteligência Artificial.

## O que já está decidido

- Abordagem quantitativa, de caráter aplicado.
- Referencial teórico: classificação seletiva (troca risco-cobertura) e autoavaliação/calibração de LLMs.
- Os sinais de incerteza produzidos pelo próprio modelo funcionam como **função de seleção**.
- A avaliação é feita por curvas risco-cobertura contra a classificação oficial.

## O que está em aberto

- A métrica principal para comparar os sinais de incerteza entre si.
- Quais sinais entram no estudo.
- Como tratar classes raras.
- O tipo de contribuição científica que o trabalho reivindica.

## Fora do escopo deste planejamento

A escolha dos modelos específicos e a coleta e o tratamento dos dados.

## Pergunta de aprofundamento

Para que a pesquisa seja citável, a contribuição deve ser replicar em português e no setor público sinais de incerteza já validados em inglês, ou propor um critério operacional de encaminhamento à revisão humana com risco controlado?
