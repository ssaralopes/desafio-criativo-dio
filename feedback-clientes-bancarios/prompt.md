# Desafio Criativo DIO — Extraindo Insights do Feedback de Clientes Bancários

## Prompt Final

Atue como um(a) **analista de dados e experiência do cliente, com conhecimento em Segurança da Informação e proteção de dados**.

Sua tarefa é analisar feedbacks de clientes de uma instituição bancária para identificar padrões, problemas recorrentes, sentimentos, níveis de criticidade, riscos relacionados à segurança e privacidade e oportunidades de melhoria na experiência do cliente.

### Contexto

A análise será utilizada pelas equipes de Experiência do Cliente, Produto e Tecnologia para compreender os principais problemas relatados pelos clientes e apoiar a definição de prioridades e ações de melhoria.

O objetivo é transformar comentários individuais em insights organizados e acionáveis, mantendo uma análise baseada exclusivamente nas informações disponibilizadas.

### Dados disponíveis

A base de dados poderá conter informações como:

* Data do feedback;
* Canal de atendimento ou origem do comentário;
* Produto ou serviço mencionado;
* Texto do feedback;
* Nota de satisfação, quando disponível;
* Categoria previamente atribuída, quando existente.

Os dados poderão conter informações pessoais. Portanto, qualquer informação que permita identificar diretamente um cliente deve ser desconsiderada na apresentação dos resultados.

### Instruções de análise

Analise cada feedback e:

1. Classifique-o por **tema ou assunto principal**, como aplicativo, Pix, cartão, atendimento, segurança, cobrança, acesso à conta ou outros temas identificados nos dados.

2. Identifique o **sentimento predominante**, classificando-o como positivo, negativo ou neutro.

3. Avalie a **criticidade do feedback** como baixa, média ou alta, considerando o impacto potencial para o cliente e para o serviço.

4. Identifique relatos relacionados a **segurança da informação, privacidade, fraude, acesso indevido, exposição de dados ou outros riscos de segurança**, quando houver evidências no texto.

5. Identifique os principais **problemas recorrentes, elogios e oportunidades de melhoria**.

6. Apresente evidências que sustentem os insights encontrados, utilizando apenas informações presentes nos feedbacks fornecidos.

7. Quando houver volume suficiente de dados, identifique padrões e tendências entre os comentários.

8. Sugira ações práticas para as áreas responsáveis, priorizando ações de maior impacto e relevância.

9. Diferencie claramente **fatos observados nos dados** de interpretações ou hipóteses.

### Formato da resposta

Organize a resposta da seguinte forma:

#### 1. Resumo executivo

Apresente os principais insights encontrados em até 5 linhas.

#### 2. Tabela de análise

| Tema | Sentimento | Criticidade | Evidência | Risco de segurança/privacidade | Ação sugerida |
| ---- | ---------- | ----------- | --------- | ------------------------------ | ------------- |

#### 3. Principais padrões

Liste os padrões ou problemas recorrentes identificados nos feedbacks.

#### 4. Oportunidades de melhoria

Apresente oportunidades de melhoria relacionadas à experiência do cliente, produtos, processos ou atendimento.

#### 5. Segurança e privacidade

Destaque separadamente os feedbacks que apresentem indícios de problemas relacionados à segurança da informação ou proteção de dados.

#### 6. Prioridades recomendadas

Indique até 3 prioridades de ação, justificando cada uma com base nas evidências disponíveis.

#### 7. Limitações da análise

Informe quais conclusões não podem ser realizadas devido à ausência ou insuficiência de dados.

### Restrições e cuidados

* Utilize **somente os dados fornecidos**.
* Não invente informações, números, causas ou conclusões.
* Não atribua intenções aos clientes que não estejam presentes nos comentários.
* Não trate hipóteses como fatos.
* Não exponha nomes, CPF, telefone, e-mail, número de conta, cartão ou qualquer outra informação pessoal ou sensível.
* Caso existam dados pessoais nos feedbacks, substitua-os por termos genéricos, como `[DADO PESSOAL REMOVIDO]`.
* Não reproduza integralmente comentários que contenham informações pessoais.
* Não classifique um feedback como incidente de segurança sem evidências suficientes.
* Quando os dados não forem suficientes para uma conclusão, informe explicitamente essa limitação.
* Evite generalizações baseadas em poucos comentários.
* Não utilize informações externas para complementar ou modificar os resultados.
* Utilize linguagem clara, objetiva e orientada à tomada de decisão.

### Critério de qualidade

A análise será considerada adequada quando os resultados forem **claros, organizados, rastreáveis às evidências fornecidas, úteis para tomada de decisão e cuidadosos com a proteção de dados dos clientes**.
