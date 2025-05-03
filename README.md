# Spring AI + Angular - Curso by Loiane Groner

## Conceitos Importantes
* Modelos AI
* Prompt
* Prompt Templates
* Embeddings
* Tokens
* RAG (Retrieval Augmented Generation)

### Modelos AI
Os diferentes modelos para inteligência artificial que temos vai depender bastante de qual é o nosso input e output (entrada e saída de dados).
Nós temos os LLMs, por exemplo: Open AI, Azure Open AI, Gemini, Oracle Gen AI, existe diferentes LLMs e cada LLM pode ser responsável ou ser
muito boa em determinados modelos, então por exemplo se estamos entrando em linguagem, código, imagem com áudio, vídeo você pode pedir para
esse LLM fazer a transcrição daquele áudio pra você, esse é um tipo de modelo que temos.
Outro modelo que a gente tem visto bastante em redes sociais onde você coloca uma descrição e esse modelo vai gerar uma imagem pra você, exemplo
de modelo com foco em imagem.
Tem também modelos que são especializados em voz, vídeo sendo especializados em transcrever ou gerar imagens ou gerar áudio, ou seja, cada modelo
acaba tendo a sua própria especialização.

### Prompt
É aquele texto que a gente escreve só que muito mais que um texto simples, por exemplo: revise esse email e tire todos os erros gramaticais, tem
mais coisas, a gente tem que ter uma Persona também, como por exemplo revise esse texto como um editor de marketing, falar para a AI como exatamente
ela deve se comportar porque isso tem um impacto grande em como é gerada a resposta pra gente.
Existe também os templates para que a gente não fique sempre digitando ou para que a gente não fique sempre gerando o mesmo prompt a gente pode criar
um texto, criar o nosso prompt e passar argumentos da mesma forma que linguagens de programações a gente pode criar funções e métodos onde a gente
coloca os parâmetros como a entrada para esses métodos seria algo semelhante aqui na hora de trabalhar com AI.
A engenharia de prompt é muito importante porque um prompt bem feito pode ser o que vai fazer aquele projeto dar certo.

### Tokens
Os tokens são a moeda.
Um token, na verdade, é mais ou menos a cada três, quatro letras então não necessariamente uma palavra é igual a um token.
Então, quando colocamos crédito na nossa API pra gente poder consumir a gente vai ser cobrado em tokens, tanto na nossa entrada de dados (prompt) quanto
na saída de dados.

### RAG
É a parte de documentos que é você fornecer contexto sobre a AI.