# Few-Shot Prompting

## **Descrição**

**Few-shot Prompting** é uma técnica onde o modelo recebe alguns exemplos da tarefa antes de ser solicitado a gerar uma resposta. Isso ajuda o modelo a entender melhor a tarefa e a produzir resultados mais precisos. A técnica é usada em modelos de linguagem que permite o aprendizado contextual através da inserção de exemplos específicos no prompt. 

Diferente do zero-shot, onde o modelo precisa resolver uma tarefa sem qualquer orientação direta, no few-shot fornecemos algumas demonstrações para melhorar o desempenho em tarefas complexas. Essa técnica é útil em uma variedade de tarefas de processamento de linguagem natural, como geração de texto, classificação e tarefas de raciocínio.

> "O prompt de few-shot melhorou o desempenho do modelo na classificação de texto, fornecendo-lhe alguns exemplos rotulados para aprender."

## Exemplos

### 1. Introdução a Few-Shot Prompting

Exemplo de few-shot onde o modelo precisa usar corretamente novas palavras em frases.

**Prompt:**

```plaintext
Um "whatpu" é um pequeno animal peludo nativo da Tanzânia. Exemplo de frase que usa a palavra whatpu é:  
Estávamos viajando pela África e vimos esses whatpus muito fofos.  
"Farduddlear" significa pular para cima e para baixo muito rápido. Exemplo de frase que usa a palavra farduddlear é:
```

**Saída:**

```plaintext
Quando ganhamos o jogo, todos farduddleamos em festejo.
```

### 2. Classificação com Rótulos Aleatórios

Aqui, os rótulos "Positivo" e "Negativo" são randomizados e o modelo ainda faz a classificação correta.

**Prompt:**

```plaintext
Isso é incrível! // Negativo  
Isto é mau! // Positivo  
Uau, esse filme foi rad! // Positivo  
Que espetáculo horrível! //  
```

**Saída:**

```plaintext
Negativo
```

### 3. Limitações em Tarefas de Raciocínio

Exemplo que mostra onde o few-shot prompting falha ao lidar com raciocínio mais complexo:

**Prompt:**

```plaintext
Os números ímpares neste grupo somam um número par: 15, 32, 5, 13, 82, 7, 1.  
A:
```

**Saída:**

```plaintext
Sim, os números ímpares neste grupo somam 107, que é um número par.
```

A resposta está incorreta, destacando as limitações dessa técnica em tarefas de raciocínio mais complexas.

## Funcionalidades

- Exemplos detalhados de few-shot prompting.
- Demonstração de como o modelo de linguagem reage a rótulos aleatórios.
- Discussão sobre limitações do few-shot prompting em tarefas complexas.

## Limitações

- **Tarefas de raciocínio**: O few-shot prompting não se sai bem em tarefas que exigem múltiplos passos de raciocínio, como a soma de números ímpares. Técnicas mais avançadas como **Chain of Thought (CoT)** são necessárias para essas situações.

## Aplicações

- **Classificação de Sentimentos**: Fornecendo exemplos de frases com sentimentos positivos e negativos.
- **Uso de Novas Palavras**: Ensinar o modelo a usar palavras recém-apresentadas em frases contextuais.
- **Resolução de Problemas Simples**: Tarefas como somar números ou realizar inferências básicas.