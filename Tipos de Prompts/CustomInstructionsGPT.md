# Instruções Personalizadas para o ChatGPT

## Visão Geral

Estamos animados em apresentar as **Instruções Personalizadas** para o ChatGPT, um recurso projetado para aprimorar a experiência do usuário, permitindo que você personalize como o ChatGPT responde às suas perguntas. Este recurso visa fornecer mais controle a você, garantindo que suas preferências sejam consideradas em cada interação.

## O que são Instruções Personalizadas?

As Instruções Personalizadas permitem que você defina preferências ou requisitos específicos que o ChatGPT levará em conta durante todas as futuras conversas. Ao fornecer contexto sobre você e especificar como você gostaria que o modelo respondesse, você pode criar uma interação mais adaptada que atenda às suas necessidades.

### Benefícios das Instruções Personalizadas

- **Consistência**: O ChatGPT lembrará suas preferências, portanto, você não precisará repeti-las em cada conversa.
- **Personalização**: Ajuste as respostas com base no seu papel ou interesses (por exemplo, educador, desenvolvedor, pai).
- **Eficiência**: Economize tempo ao ter respostas formatadas de uma maneira que melhor lhe convém.

## Como Funciona

Ao definir suas instruções personalizadas, você pode preencher duas áreas principais:

1. **O que você gostaria que o ChatGPT soubesse sobre você para fornecer melhores respostas?**
2. **Como você gostaria que o ChatGPT respondesse?**

Essas instruções orientarão o modelo a adaptar suas respostas para se adequar ao seu contexto único.

### Exemplos de Instruções Personalizadas

#### Exemplo 1: Educador em Ciências

- **Entrada do Usuário**: "Eu trabalho em programas de educação científica para alunos de terceira série."
- **Preferência de Resposta**: "Ao discutir soluções potenciais para itens relacionados ao trabalho, apresente as informações em formato de tabela, delineando os prós e contras de cada opção."

##### Consulta do Usuário:
*Quais seriam três coisas importantes para ensinar sobre a lua?*

##### Resposta do ChatGPT:
Ensinar alunos de terceira série sobre a lua envolve vários conceitos centrais. Aqui estão três tópicos chave a considerar:

| Tópico                          | Prós                                                                                 | Contras                                                                                             |
|---------------------------------|--------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| Fases da Lua                   | Ajuda os alunos a entender padrões cíclicos e o tempo; facilmente observável.      | Pode ser complexo para alguns alunos, particularmente as razões por trás das diferentes fases.     |
| A Relação da Lua com a Terra    | Vital para explicar conceitos de gravidade, marés e órbita; leva a discussões sobre o sistema solar. | Exige algum conhecimento básico de ciência física, o que pode ser desafiador para alguns alunos da terceira série. |
| Características Físicas da Lua  | Envolvente, especialmente tópicos como crateras; promove discussões sobre exploração espacial. | Pode ser abstrato sem recursos visuais, como imagens ou modelos de alta qualidade.                  |

Em última análise, sua escolha de ênfase dependerá do conhecimento prévio dos seus alunos, do currículo que você segue e dos recursos disponíveis.

#### Exemplo 2: Desenvolvedor

- **Entrada do Usuário**: "Eu prefiro código eficiente em linguagens que não sejam Python."
- **Preferência de Resposta**: "Forneça trechos de código em JavaScript, juntamente com explicações das funções principais."

```go
package main

import "fmt"

func Fibonacci(n int) int {
    if n ≤ 1 {
        return n
    }
    a, b := 0, 1
    for i := 2; i ≤ n; i++ {
        a, b = b, a+b
    }
    return b
}

func main() {
    fmt.Println(Fibonacci(10)) // replace 10 with the nth number
}
```