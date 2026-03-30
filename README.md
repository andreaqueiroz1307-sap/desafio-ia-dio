# desafio-ia-dio

🎯 Contexto e Objetivos

Este projeto foi desenvolvido como parte de um desafio da DIO com o objetivo de explorar o uso da Inteligência Artificial como ferramenta de aprendizagem ativa.

O foco foi a criação de um Caderno Temático utilizando o NotebookLM, organizando conteúdos, realizando curadoria de fontes e aplicando técnicas de engenharia de prompts para aprofundar o entendimento.

📌 Tema escolhido:

Fundamentos de Inteligência Artificial e Modelos de Linguagem (GPT)

🎯 Objetivos de estudo:
Compreender como funcionam modelos de linguagem natural
Entender conceitos como tokens, prompts e alucinações
Utilizar IA para resumir, explicar e organizar conteúdos
Desenvolver pensamento crítico ao analisar respostas da IA
Criar um material reutilizável para revisão futura


📚 Curadoria de Fontes

Abaixo estão algumas fontes utilizadas no NotebookLM para construção do conhecimento:

https://youtu.be/1VDcke66TRE?si=BZrU5Md350N-KykR
https://youtu.be/FI6x88l01_Y?si=xGFgNo1_DpPXXIB6
https://youtu.be/OzrZBBMRFhI?si=HPhxBmfccn68V7vT
https://youtu.be/0rXf90pnL44?si=Jt5HVVc1P0cKAMsf
https://www.youtube.com/live/dLLw6QjADjo?si=6VQi782j7lf9BcH_

🧪 Engenharia de Prompts e "Cicatrizes"

🔍 Prompt 1

Pergunta:

O que são tokens em modelos de linguagem?

Resposta:
Em modelos de linguagem, os tokens são as unidades individuais de informação ou dados que servem como os "tijolos fundamentais" para o processamento de linguagem natural (PLN)
. Eles representam a forma como as máquinas "leem" e fragmentam o texto para conseguir analisá-lo e processá-lo
.
Aqui estão os pontos principais para entender o que são e como funcionam:
1. O que compõe um token?
Embora seja comum associar um token a uma palavra, a definição é mais flexível:
Pode ser uma palavra inteira, uma frase curta ou até mesmo um único caractere, dependendo do contexto e do modelo
.
Algumas palavras complexas ou longas podem ser divididas em mais de um token
.
Símbolos, pontuações e espaços também podem ser contabilizados como tokens
.
2. O Processo de Tokenização
A tokenização é o processo de converter um texto bruto nesses pequenos pedaços (tokens)
. É uma etapa essencial porque os computadores não processam palavras como os humanos; eles processam números
. Após a tokenização, cada token é convertido em vetores numéricos (chamados de word embeddings) que capturam o significado e a relação entre as palavras
.
3. Como os modelos usam os tokens para "pensar"?
Os modelos de linguagem (LLMs) não entendem o significado intrínseco das frases como nós, mas sim a probabilidade estatística
.
O modelo analisa os tokens fornecidos no comando (prompt) e calcula qual é o próximo token mais provável para continuar o texto
.
Eles utilizam mecanismos de atenção para entender quais tokens em uma frase são mais importantes para manter o contexto
.
4. Limites de Contexto e Custos
O uso de tokens é um fator determinante na capacidade e no custo das IAs:
Janela de Contexto: Cada modelo tem um limite máximo de tokens que consegue processar por vez (incluindo a pergunta e a resposta)
. Por exemplo, o GPT-3 tem um limite de 4.096 tokens, enquanto versões do GPT-4 podem chegar a 32.768 tokens
.
Custo Financeiro: O uso de APIs de modelos avançados é geralmente cobrado com base na quantidade de tokens gerados ou processados
.
Alucinação: Se o limite de tokens for atingido antes da conclusão de uma tarefa, o modelo pode interromper a resposta no meio ou apresentar falhas de coerência
.
Em resumo, os tokens são a ponte entre a linguagem humana e a matemática computacional, permitindo que a IA identifique padrões e gere textos que pareçam naturais
.
🔍 Prompt 2

Pergunta:

Explique o que são alucinações em IA de forma simples.

Resposta resumida:
Uma alucinação em IA ocorre quando o modelo fornece uma resposta incorreta, falsa ou que não é verídica, mas a apresenta com um alto nível de confiança, fazendo com que pareça verdade
.

Dificuldade encontrada:
Respostas podem parecer corretas mesmo quando não são — exige senso crítico.



🧠 Principais aprendizados (cicatrizes):
Prompts vagos geram respostas genéricas
Refinar perguntas melhora drasticamente a qualidade
A IA pode errar com confiança (alucinações)
O usuário precisa guiar a IA com contexto




📖 Miniguia de Estudo
📝 1. Resumo Estruturado

A Inteligência Artificial aplicada à linguagem natural permite que máquinas compreendam e gerem texto de forma semelhante à humana.

Modelos como o GPT utilizam tokens para processar linguagem e são treinados com grandes volumes de dados. Apesar de sua eficiência, podem gerar respostas incorretas, conhecidas como alucinações.

O uso eficiente da IA depende da qualidade dos prompts e da capacidade do usuário de interpretar criticamente as respostas.

📚 2. Glossário
Token: Unidade básica de texto processada pela IA
Prompt: Comando ou pergunta feita para a IA
Alucinação: Resposta incorreta ou inventada pela IA
Engenharia de Prompt: Técnica de formular perguntas para obter melhores respostas


💡 3. Prompts Reutilizáveis

Aqui estão alguns prompts úteis para estudos futuros:

"Explique [conceito] de forma simples e com exemplos"
"Resuma o texto abaixo em tópicos principais"
"Quais são os pontos mais importantes sobre [tema]?"
"Explique como se eu fosse iniciante"
"Compare [conceito A] e [conceito B]"


🚀 Conclusão

Este projeto demonstrou como a Inteligência Artificial pode ser utilizada como uma poderosa aliada no processo de aprendizagem.

Além de facilitar o acesso à informação, a IA permite organizar, resumir e aprofundar conteúdos — desde que utilizada com pensamento crítico e boas práticas de prompt.


🔗 Link do Repositório

https://github.com/andreaqueiroz1307-sap/desafio-ia-dio



