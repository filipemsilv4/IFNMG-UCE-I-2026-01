# Matriz de Referências

Esta matriz foi reorganizada para seguir a estrutura planejada da palestra.

Princípios desta versão:
- `ID` é o primeiro campo e representa `bloco.subtema` da apresentação;
- cada linha responde a uma necessidade concreta do roteiro;
- a análise `fonte por fonte` continua em [curadoria-de-fontes-para-a-palestra.md](curadoria-de-fontes-para-a-palestra.md);
- a matriz abaixo existe para evitar sensação de escopo infinito e mostrar exatamente o que cada bloco da palestra precisa.

## 0. Base do Projeto

| ID | Bloco da palestra | Subtema | Fontes centrais | Fontes de apoio | Status | Observações |
| --- | --- | --- | --- | --- | --- | --- |
| 0.1 | Base institucional | Contexto da UCE e critérios do projeto | [INT-01](../../01-contexto/disciplina-uce-e-curso.md) UCE no curso de Ciência da Computação; [INT-02](../../01-contexto/escopo-do-projeto.md) Escopo do projeto | [INT-03](../02-roteiro-e-conteudo/roteiro-inicial-da-palestra.md) Roteiro inicial | Consolidado | Serve para alinhar o projeto com a disciplina, não para virar slide da palestra |
| 0.2 | Base narrativa | Estrutura preliminar da apresentação | [INT-03](../02-roteiro-e-conteudo/roteiro-inicial-da-palestra.md) Conteúdos da palestra | [INT-02](../../01-contexto/escopo-do-projeto.md) Escopo do projeto | Consolidado | Base interna para organizar a curadoria por bloco |

## 1. IA sempre esteve aqui

| ID | Bloco da palestra | Subtema | Fontes centrais | Fontes de apoio | Status | Observações |
| --- | --- | --- | --- | --- | --- | --- |
| 1.1 | IA sempre esteve aqui | A própria definição de IA sempre foi debatida | Turing (1950) - Computing Machinery and Intelligence; Dartmouth Proposal (1955) | Curadoria histórica da abertura | Cobertura forte | Bom para mostrar que a pergunta sobre IA é antiga e conceitualmente instável |
| 1.2 | IA sempre esteve aqui | IA impressionava muito antes dos LLMs | IBM Research - Deep Blue; Nature - AlphaGo | [Roteiro inicial](../02-roteiro-e-conteudo/roteiro-inicial-da-palestra.md) | Cobertura forte | Ajuda a quebrar a ideia de que IA pré-ChatGPT era “boba” |
| 1.3 | IA sempre esteve aqui | IA já impactava saúde e cuidado antes do hype atual | JAMA 2016 - diabetic retinopathy; FDA - IDx-DR; WHO - TB screening guidance | WHO 2025 - CAD for TB; curadoria da abertura | Cobertura forte | Muito melhor para repertório e sensibilidade humana do que exemplos de infraestrutura |
| 1.4 | IA sempre esteve aqui | IA como ferramenta de descoberta científica | DeepMind - AlphaFold: Five Years of Impact | Curadoria da abertura | Cobertura forte | Ótimo bloco de fascínio científico e repertório sobre ciência e inovação |

## 2. O que é IA generativa

| ID | Bloco da palestra | Subtema | Fontes centrais | Fontes de apoio | Status | Observações |
| --- | --- | --- | --- | --- | --- | --- |
| 2.1 | O que é IA generativa | Definição geral, diferença entre IA tradicional e generativa | IBM - O que é a IA generativa? | UNESCO Guidance | Cobertura forte | Bom bloco para definição inicial sem excesso técnico |
| 2.2 | O que é IA generativa | Como os modelos respondem e por que a explicação “só prevê a próxima palavra” é insuficiente | Anthropic - Tracing the thoughts of a large language model | IBM - O que é a IA generativa?; Anthropic - Emotion concepts | Cobertura forte | Usar só a nuance útil; não aprofundar interpretabilidade demais |

## 3. Os 4 Ds do uso inteligente

| ID | Bloco da palestra | Subtema | Fontes centrais | Fontes de apoio | Status | Observações |
| --- | --- | --- | --- | --- | --- | --- |
| 3.0 | Os 4 Ds do uso inteligente | Origem e valor do framework | Anthropic - AI Fluency overview; Dakan e Feller - AI Fluency Framework | Anthropic - AI Fluency cheat sheet | Cobertura forte | Boa referência para justificar os 4 Ds como estrutura pedagógica explícita e citar sua origem |

### 3.1 Description

| ID | Bloco da palestra | Subtema | Fontes centrais | Fontes de apoio | Status | Observações |
| --- | --- | --- | --- | --- | --- | --- |
| 3.1 | Description | Como pedir melhor em 2026 | OpenAI - Reasoning best practices | Prompt Engineering Guide - Reasoning LLMs | Cobertura forte | Este é o bloco que mais precisava de atualização em relação ao material antigo |

### 3.2 Delegation

| ID | Bloco da palestra | Subtema | Fontes centrais | Fontes de apoio | Status | Observações |
| --- | --- | --- | --- | --- | --- | --- |
| 3.2 | Delegation | Quando a IA ajuda de verdade e quando ela deve ser só apoio | Deng et al.; NBER 2026 | Microsoft Research - Critical Thinking | Cobertura forte | Bom para mostrar ganhos reais sem vender “substituição do pensar” |
| 3.3 | Delegation | Desempenho assistido versus aprendizado real | Bastani et al. - Generative AI Can Harm Learning | Deng et al.; NBER 2026 | Cobertura forte | Bloco central para a pergunta “aprendi ou só copiei?” |

### 3.3 Discernment

| ID | Bloco da palestra | Subtema | Fontes centrais | Fontes de apoio | Status | Observações |
| --- | --- | --- | --- | --- | --- | --- |
| 3.4 | Discernment | Alucinações, erros factuais e necessidade de verificar | Microsoft Research - Critical Thinking | UNESCO Guidance | Cobertura suficiente | Ainda podemos buscar um caso exemplar bem didático para mostrar erro real |
| 3.5 | Discernment | Contexto longo: modelos melhoraram, mas ainda erram | Lost in the Middle | Google Gemini API - Long context | Cobertura forte | Ótimo para mostrar que jogar muito texto no prompt não resolve tudo |

### 3.4 Diligence

| ID | Bloco da palestra | Subtema | Fontes centrais | Fontes de apoio | Status | Observações |
| --- | --- | --- | --- | --- | --- | --- |
| 3.6 | Diligence | Ética, integridade acadêmica e papel do usuário | UNESCO Guidance | Microsoft Research - Critical Thinking | Cobertura forte | Base principal para plágio, responsabilidade e agência humana |
| 3.7 | Diligence | Privacidade, dados pessoais e uso responsável | UNESCO Guidance | [Escopo do projeto](../../01-contexto/escopo-do-projeto.md) | Cobertura suficiente | Ainda cabe adicionar uma fonte mais prática sobre dados pessoais se sentirmos necessidade |
| 3.8 | Diligence | Saúde mental, apego emocional e companion AI | Nature editorial; Common Sense Media; OpenAI - Sensitive conversations | OpenAI - Sycophancy; Caso #keep4o | Cobertura forte | O `#keep4o` deve entrar apenas como caso ilustrativo, não como base científica central |

## 4. O que a IA nunca vai ter

| ID | Bloco da palestra | Subtema | Fontes centrais | Fontes de apoio | Status | Observações |
| --- | --- | --- | --- | --- | --- | --- |
| 4.1 | O que a IA nunca vai ter | Vivência própria, responsabilidade moral e identidade humana | Nature editorial | Anthropic - Emotion concepts; OpenAI - Sensitive conversations | Cobertura suficiente | Este bloco é mais interpretativo e retórico; as fontes servem para dar lastro, não para “provar” cada frase |

## 5. Encerramento

| ID | Bloco da palestra | Subtema | Fontes centrais | Fontes de apoio | Status | Observações |
| --- | --- | --- | --- | --- | --- | --- |
| 5.1 | Encerramento | Checklist final de uso saudável: entender, checar, aprender, limitar | UNESCO Guidance; Bastani et al. | Microsoft Research; OpenAI - Sensitive conversations | Cobertura forte | Dá para fechar a palestra com um checklist simples apoiado por evidências fortes |

## Escala de status

- `Consolidado`: já está resolvido para fins de estrutura interna.
- `Cobertura forte`: já temos base suficiente para construir o bloco.
- `Cobertura suficiente`: já temos base boa, mas pode caber um exemplo ou reforço adicional.
- `A reforçar`: ainda faltaria uma fonte ou exemplo melhor.

## Escala de confiabilidade das fontes

A avaliação detalhada de confiabilidade e ressalvas está em [curadoria-de-fontes-para-a-palestra.md](curadoria-de-fontes-para-a-palestra.md).
