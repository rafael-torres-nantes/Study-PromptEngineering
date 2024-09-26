# **One-Shot Prompt**

**Descrição**  
O **One-Shot Prompt** é um tipo de instrução onde a ideia principal é que você está treinando o modelo de IA com um único exemplo do formato e da resposta que está buscando.

**Benefícios**  
Com um único exemplo, o modelo já consegue entender o formato desejado para futuras respostas. Além de evitaa a necessidade de fornecer múltiplos exemplos ou repetir instruções, economizando tempo e esforço.

---

## Exemplo de Uso

### **Entrada**

No prompt, estou fazendo uma pergunta: como funciona uma unidade de ar condicionado residencial?

Em seguida, respondo com uma lista de quatro itens que têm a ver com o funcionamento interno de uma unidade de ar condicionado.

```
Preciso de respostas curtas e em tópicos para as minhas perguntas.

Pergunta: Como funciona uma unidade de ar condicionado residencial?
Resposta:
- Circulação de refrigerante
- Transferência de calor
- Resfriamento e desumidificação
- Controle por termostato

Pergunta: Como funciona um airbag automotivo?
Pergunta: Como funciona um coração artificial?
Pergunta: Como funciona um embaralhador automático de cartas?
Pergunta: Como funciona um banco de dados?
Pergunta: Como funciona uma escova de dentes?
Pergunta: Como funciona a psicologia?
```

### **Saída Esperada**

Após receber o prompt acima, o modelo poderia gerar uma resposta como:

```
Como funciona um airbag automotivo?

- Sensores detectam uma colisão
- Sinal aciona a inflagem do airbag
- O inflador se ativa, produzindo gás
- O airbag infla rapidamente para amortecer os ocupantes

Como funciona um coração artificial?

- O sangue é bombeado através do corpo
- Bomba motorizada ou sistema pneumático
- Pode ser usado como ponte para transplante ou implantado permanentemente

Como funciona um embaralhador automático de cartas?

- As cartas são inseridas no embaralhador
- Mecanismos internos embaralham as cartas aleatoriamente
- Cartas embaralhadas são distribuídas para o próximo jogo

Como funciona um banco de dados?

- Armazena e organiza dados em tabelas
- Usa consultas para recuperar informações específicas
- Permite adicionar, modificar e excluir dados

Como funciona uma escova de dentes?

- As cerdas esfregam os dentes e gengivas
- A pasta de dentes ajuda na limpeza e no cuidado dental
- O movimento manual ou elétrico remove placa e resíduos

Como funciona a psicologia?

- Estudo do comportamento humano e da mente
- Envolve pesquisa, observação e análise
- Lida com processos mentais, emoções e cognição
- Aplicada em terapia, aconselhamento e compreensão do comportamento humano
```