# Zero-Shot Prompt

**Descrição**  
O **Zero-Shot Prompt** é um tipo de instrução que solicita que o modelo realize uma tarefa sem fornecer exemplos anteriores ou ajustes finos. O modelo se baseia exclusivamente em seu conhecimento pré-treinado para gerar uma resposta relevante.

**Benefícios**  
Permite ao modelo lidar com tarefas desconhecidas ou não previstas sem necessidade de treinamento adicional. Além de reduzir o tempo e o esforço necessários para preparar conjuntos de dados para treinamento.

---

## Exemplo de Uso

### **Entrada**

```
Give me 10 examples of zero-shot prompts in a table with the prompts in the left column and your responses in the right column.
```

### Saída Esperada

Após receber o prompt acima, o modelo poderia gerar uma resposta como:

```
Sure, here are 10 examples of zero-shot prompts with my responses in a table:

| Prompt                                          | Response                                          |
|-------------------------------------------------|--------------------------------------------------|
| Translate "hello" from English to French.      | Bonjour                                          |
| What is the capital of Australia?               | Canberra                                         |
| Who wrote the play "Romeo and Juliet"?          | William Shakespeare                              |
| Convert 5 miles to kilometers.                  | 5 miles is approximately 8.05 kilometers.       |
| What is the chemical symbol for water?          | H2O                                             |
| Name the four primary colors.                   | The four primary colors are red, blue, yellow, and green. |
| Who is the lead singer of the band "Coldplay"? | Chris Martin                                    |
| What is the currency used in Japan?             | Japanese Yen                                    |
| Who is the author of the "Harry Potter" series? | J.K. Rowling                                    |
| Calculate the square root of 64.                | The square root of 64 is 8.                     |
```
