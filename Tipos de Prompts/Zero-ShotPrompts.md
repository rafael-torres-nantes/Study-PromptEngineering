## 🔍 Zero-shot Prompting

## **Descrição**
O **Zero-Shot Prompting** refere-se à capacidade de um modelo de linguagem realizar uma tarefa sem ter recebido qualquer exemplo ou ajuste específico para aquela tarefa no prompt. Essa técnica é poderosa porque permite que o modelo utilize seu conhecimento pré-treinado para gerar respostas precisas e relevantes sem a necessidade de exemplos pré-fornecidos.

Os modelos de linguagem de grande escala (LLMs), como o GPT-4, são treinados em grandes quantidades de dados e ajustados para seguir instruções. Isso os torna capazes de executar tarefas **zero-shot**, ou seja, sem necessitar de exemplos ou demonstrações. Esses modelos aproveitam seu vasto conhecimento prévio e, graças a métodos como **Instruction Tuning** e **RLHF (Reinforcement Learning from Human Feedback)**, conseguem se alinhar melhor às preferências humanas ao seguir instruções.  

Por exemplo, ao solicitar que o modelo classifique o sentimento de uma frase sem fornecer exemplos de sentimentos anteriores, o modelo ainda pode identificar corretamente o sentimento com base em seu treinamento.

## **Exemplo Zero-Shot:**

**Prompt:**
```
Classifique o texto em neutro, negativo ou positivo.
Texto: Acho que as férias estão boas.
Sentimento:
```

**Saída:**
```
Neutro
```

No exemplo acima, o modelo conseguiu classificar o sentimento como "neutro" sem a necessidade de fornecer exemplos específicos no prompt. Esse é um exemplo clássico do poder do **zero-shot prompting**.

### **Benefícios**  
- **Economia de tempo e esforço:** Não há necessidade de preparar ou curar conjuntos de dados de exemplos antes de realizar a tarefa.
- **Versatilidade:** Os modelos podem lidar com uma ampla variedade de tarefas sem ajustes específicos para cada caso.
- **Escalabilidade:** O **Instruction Tuning** e **RLHF** permitem que modelos ajustados em grandes conjuntos de dados de instruções respondam de maneira alinhada com preferências humanas e adaptem-se melhor a novas tarefas sem a necessidade de re-treinamento.

### **Quando Zero-Shot não Funciona**
Embora o zero-shot prompting seja útil, ele pode falhar em tarefas mais complexas que requerem mais contexto ou demonstrações. Quando isso ocorre, recomenda-se utilizar a técnica de **Few-Shot Prompting**, onde alguns exemplos são fornecidos para que o modelo tenha um padrão claro a seguir.

---

## Exemplos adicionais de Zero-Shot Prompts

**Prompt:**  
```
Give me 10 examples of zero-shot prompts in a table with the prompts in the left column and your responses in the right column.
```

**Saída esperada:**

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

Esses exemplos mostram como o modelo pode lidar com tarefas de conhecimento geral e raciocínio básico sem a necessidade de treinamento adicional.