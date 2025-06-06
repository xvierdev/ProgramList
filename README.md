# Lista de Exercícios de Programação em Python

Uma coleção de 30 exercícios de programação em Python, separados por nível de dificuldade, para praticar lógica, estruturas de controle, laços, funções e mais.

## Nível Fácil

---

### Bloco 1: Lógica Simples e Operações Matemáticas (1-5)

#### Exercício 1: Conversor de Temperatura
*   **Nível:** Fácil
*   **Enunciado:** Escreva um programa que converta uma temperatura digitada em graus Celsius para graus Fahrenheit. A fórmula é: `F = C * (9/5) + 32`.
*   **Exemplo de Entrada:**
    ```text
    30
    ```
*   **Exemplo de Saída:**
    ```text
    A temperatura de 30°C corresponde a 86.0°F.
    ```

#### Exercício 2: Calculadora de IMC
*   **Nível:** Fácil
*   **Enunciado:** Crie um programa que calcula o Índice de Massa Corporal (IMC) de uma pessoa. O programa deve pedir o peso (em kg) e a altura (em metros) e exibir o resultado. A fórmula é: `IMC = peso / (altura * altura)`.
*   **Exemplo de Entrada:**
    ```text
    Peso (kg): 70
    Altura (m): 1.75
    ```
*   **Exemplo de Saída:**
    ```text
    Seu IMC é 22.86.
    ```

#### Exercício 3: Calculadora de Área de Retângulo
*   **Nível:** Fácil
*   **Enunciado:** Faça um programa que peça a base e a altura de um retângulo e calcule e mostre a área.
*   **Exemplo de Entrada:**
    ```text
    Base: 10
    Altura: 5
    ```
*   **Exemplo de Saída:**
    ```text
    A área do retângulo é 50.
    ```

#### Exercício 4: Idade em Dias
*   **Nível:** Fácil
*   **Enunciado:** Desenvolva um programa que pergunte a idade de uma pessoa em anos e retorne a idade dessa pessoa em dias (considere que um ano tem 365 dias).
*   **Exemplo de Entrada:**
    ```text
    Quantos anos você tem? 25
    ```
*   **Exemplo de Saída:**
    ```text
    Você já viveu 9125 dias.
    ```

#### Exercício 5: Média de Notas
*   **Nível:** Fácil
*   **Enunciado:** Escreva um programa que peça três notas de um aluno e calcule a média.
*   **Exemplo de Entrada:**
    ```text
    Nota 1: 7.5
    Nota 2: 8.0
    Nota 3: 9.5
    ```
*   **Exemplo de Saída:**
    ```text
    A média do aluno é 8.33.
    ```

### Bloco 2: Estruturas Condicionais (6-10)

#### Exercício 6: Verificador de Maioridade (if)
*   **Nível:** Fácil
*   **Enunciado:** Crie um programa que pergunte a idade do usuário e informe se ele é maior de idade (18 anos ou mais).
*   **Exemplo de Entrada:**
    ```text
    22
    ```
*   **Exemplo de Saída:**
    ```text
    Você é maior de idade.
    ```

#### Exercício 7: Aprovado ou Reprovado (if/else)
*   **Nível:** Fácil
*   **Enunciado:** Faça um programa que peça a nota de um aluno (de 0 a 10) e informe se ele foi aprovado (nota maior ou igual a 7) ou reprovado.
*   **Exemplo de Entrada:**
    ```text
    6.5
    ```
*   **Exemplo de Saída:**
    ```text
    Reprovado.
    ```

#### Exercício 8: Positivo, Negativo ou Zero (if/elif/else)
*   **Nível:** Fácil
*   **Enunciado:** Peça um número ao usuário e diga se ele é positivo, negativo ou zero.
*   **Exemplo de Entrada:**
    ```text
    -5
    ```
*   **Exemplo de Saída:**
    ```text
    O número é negativo.
    ```

#### Exercício 9: Semáforo (if/elif/else)
*   **Nível:** Fácil
*   **Enunciado:** Crie um programa que pergunte a cor do semáforo ("vermelho", "amarelo", "verde") e informe ao motorista o que ele deve fazer.
*   **Exemplo de Entrada:**
    ```text
    amarelo
    ```
*   **Exemplo de Saída:**
    ```text
    Atenção!
    ```

#### Exercício 10: Mini-Quiz (if/elif/else aninhado)
*   **Nível:** Fácil
*   **Enunciado:** Crie um quiz simples com duas perguntas. Se o usuário acertar a primeira, faça a segunda pergunta. No final, informe quantas perguntas ele acertou.
*   **Exemplo de Entrada:**
    ```text
    Pergunta 1: Qual a capital do Brasil? (a) Rio de Janeiro, (b) Brasília, (c) São Paulo
    b
    Correto!
    Pergunta 2: Quanto é 7 * 6? (a) 42, (b) 35, (c) 48
    a
    Correto!
    ```
*   **Exemplo de Saída:**
    ```text
    Você acertou 2 de 2 perguntas!
    ```

### Bloco 3: Laços de Repetição (11-15)

#### Exercício 11: Contagem até 10 (for)
*   **Nível:** Fácil
*   **Enunciado:** Escreva um programa que use um laço `for` para imprimir os números de 1 a 10.
*   **Exemplo de Entrada:** (Nenhuma)
*   **Exemplo de Saída:**
    ```text
    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    ```

#### Exercício 12: Soma com Sentinela (while)
*   **Nível:** Fácil
*   **Enunciado:** Faça um programa que peça ao usuário para digitar números e os some. O programa deve parar quando o usuário digitar 0 e, ao final, mostrar a soma de todos os números digitados.
*   **Exemplo de Entrada:**
    ```text
    5
    10
    3
    0
    ```
*   **Exemplo de Saída:**
    ```text
    A soma dos números é 18.
    ```

#### Exercício 13: Encontrando o Maior Número (for e if)
*   **Nível:** Fácil
*   **Enunciado:** Crie um programa que, a partir de uma lista de números `[12, 45, 2, 4, 89, 22, 15]`, encontre e exiba o maior número.
*   **Exemplo de Entrada:** (Lista pré-definida no código)
*   **Exemplo de Saída:**
    ```text
    O maior número na lista é 89.
    ```

#### Exercício 14: Contador de Números Pares (for e if)
*   **Nível:** Fácil
*   **Enunciado:** Desenvolva um programa que conte quantos números pares existem em uma lista de números `[1, 2, 3, 4, 5, 6, 7, 8, 9, 10]`.
*   **Exemplo de Entrada:** (Lista pré-definida no código)
*   **Exemplo de Saída:**
    ```text
    A lista tem 5 números pares.
    ```

#### Exercício 15: Média de uma Lista (for e acumulador)
*   **Nível:** Fácil
*   **Enunciado:** Faça um programa que calcule a média de todos os números em uma lista `[10, 20, 30, 40, 50]`.
*   **Exemplo de Entrada:** (Lista pré-definida no código)
*   **Exemplo de Saída:**
    ```text
    A média da lista é 30.0.
    ```

## Nível Médio

---

### Bloco 4: Laços Aninhados (16-20)

#### Exercício 16: Tabuada Completa (for aninhado)
*   **Nível:** Médio
*   **Enunciado:** Crie um programa que imprima a tabuada de 1 a 10. A saída deve ser formatada, mostrando a multiplicação de cada número de 1 a 10 pelo outro.
*   **Exemplo de Entrada:** (Nenhuma)
*   **Exemplo de Saída:**
    ```text
    Tabuada do 1:
    1 x 1 = 1
    1 x 2 = 2
    ...
    1 x 10 = 10
    ---
    Tabuada do 2:
    2 x 1 = 2
    ...
    ---
    (até a tabuada do 10)
    ```

#### Exercício 17: Desenhando um Retângulo (for aninhado)
*   **Nível:** Médio
*   **Enunciado:** Escreva um programa que peça a altura e a largura e desenhe um retângulo usando o caractere `#`.
*   **Exemplo de Entrada:**
    ```text
    Altura: 4
    Largura: 10
    ```
*   **Exemplo de Saída:**
    ```text
    ##########
    ##########
    ##########
    ##########
    ```

#### Exercício 18: Desenhando um Triângulo Retângulo (for aninhado)
*   **Nível:** Médio
*   **Enunciado:** Crie um programa que peça um número (altura) e desenhe um triângulo retângulo com esse tamanho usando o caractere `*`.
*   **Exemplo de Entrada:**
    ```text
    Altura: 5
    ```
*   **Exemplo de Saída:**
    ```text
    *
    **
    ***
    ****
    *****
    ```

#### Exercício 19: Verificador de Números Primos em um Intervalo (while/for aninhado)
*   **Nível:** Médio
*   **Enunciado:** Peça ao usuário um número e imprima todos os números primos de 1 até o número digitado. (Dica: um número primo é divisível apenas por 1 e por ele mesmo).
*   **Exemplo de Entrada:**
    ```text
    20
    ```
*   **Exemplo de Saída:**
    ```text
    Números primos até 20:
    2, 3, 5, 7, 11, 13, 17, 19
    ```

#### Exercício 20: Padrão de Números (for aninhado)
*   **Nível:** Médio
*   **Enunciado:** Faça um programa que peça um número `n` e imprima um padrão de números, onde cada linha `i` contém o número `i` repetido `i` vezes.
*   **Exemplo de Entrada:**
    ```text
    5
    ```
*   **Exemplo de Saída:**
    ```text
    1
    2 2
    3 3 3
    4 4 4 4
    5 5 5 5 5
    ```

## Nível Difícil

---

### Bloco 5: Funções e Programas Elaborados (21-30)

#### Exercício 21: Função para Verificar se é Primo
*   **Nível:** Difícil
*   **Enunciado:** Crie uma função chamada `eh_primo(numero)` que recebe um número como argumento e retorna `True` se ele for primo e `False` caso contrário. Use esta função para pedir um número ao usuário e informar se ele é primo.
*   **Exemplo de Entrada:**
    ```text
    17
    ```
*   **Exemplo de Saída:**
    ```text
    O número 17 é primo.
    ```

#### Exercício 22: Calculadora com Funções
*   **Nível:** Difícil
*   **Enunciado:** Crie um programa que simule uma calculadora. Ele deve pedir dois números e a operação (+, -, *, /). Crie funções separadas para cada operação (`somar`, `subtrair`, `multiplicar`, `dividir`). O programa deve continuar funcionando até que o usuário escolha sair.
*   **Exemplo de Entrada:**
    ```text
    Escolha a operação (+, -, *, /) ou 's' para sair: +
    Primeiro número: 10
    Segundo número: 5
    ```
*   **Exemplo de Saída:**
    ```text
    Resultado: 15
    ```

#### Exercício 23: Jogo da Adivinhação
*   **Nível:** Difícil
*   **Enunciado:** Desenvolva um jogo onde o computador "pensa" em um número entre 1 e 100 e o jogador tenta adivinhar. O programa deve dar dicas como "Maior..." ou "Menor...". Crie uma função `jogar()` que gerencia o jogo e, no final, mostre em quantas tentativas o jogador acertou.
*   **Exemplo de Entrada:**
    ```text
    Tente adivinhar o número: 50
    Maior...
    Tente adivinhar o número: 75
    Menor...
    Tente adivinhar o número: 65
    ```
*   **Exemplo de Saída:**
    ```text
    Parabéns! Você acertou em 3 tentativas.
    ```

#### Exercício 24: Validador de Senha
*   **Nível:** Difícil
*   **Enunciado:** Crie uma função `validar_senha(senha)` que verifica se uma senha atende aos seguintes critérios: pelo menos 8 caracteres, contém pelo menos uma letra maiúscula, uma letra minúscula e um número. A função deve retornar `True` ou `False`.
*   **Exemplo de Entrada:**
    ```text
    Digite uma senha: Senha123
    ```
*   **Exemplo de Saída:**
    ```text
    Senha válida.
    ```

#### Exercício 25: Gerenciador de Lista de Tarefas
*   **Nível:** Difícil
*   **Enunciado:** Crie um programa para gerenciar uma lista de tarefas. O programa deve ter um menu que permita ao usuário: Adicionar tarefa, Ver tarefas, Remover tarefa e Sair. Use funções para cada uma dessas opções.
*   **Exemplo de Entrada:**
    ```text
    1. Adicionar tarefa
    2. Ver tarefas
    3. Remover tarefa
    4. Sair
    Escolha uma opção: 1
    Digite a tarefa: Estudar Python
    ```
*   **Exemplo de Saída (após escolher a opção 2):**
    ```text
    Tarefas:
    1. Estudar Python
    ```

#### Exercício 26: Jogo da Forca Simplificado
*   **Nível:** Difícil
*   **Enunciado:** Faça uma versão simplificada do Jogo da Forca. O programa escolhe uma palavra secreta e o jogador tenta adivinhar as letras. Crie funções para: `escolher_palavra()`, `mostrar_forca(letras_corretas, palavra_secreta)` e `jogar()`. O jogador tem 6 tentativas.
*   **Exemplo de Entrada:**
    ```text
    Palavra: _ _ _ _ _ _
    Letras erradas:
    Adivinhe uma letra: a

    Palavra: _ a _ a _ a
    Letras erradas:
    Adivinhe uma letra: b
    ```
*   **Exemplo de Saída:**
    ```text
    Palavra: b a _ a _ a
    Letras erradas:
    ...
    ```

#### Exercício 27: Conversor de Moedas
*   **Nível:** Difícil
*   **Enunciado:** Crie um programa que converta valores entre diferentes moedas (ex: Real, Dólar, Euro). Peça o valor, a moeda de origem e a moeda de destino. Use funções e um dicionário para armazenar as taxas de conversão (ex: `{'dolar': 5.25, 'euro': 6.20}`).
*   **Exemplo de Entrada:**
    ```text
    Valor: 100
    Moeda de origem (real, dolar, euro): real
    Moeda de destino (dolar, euro): dolar
    ```
*   **Exemplo de Saída:**
    ```text
    R$100.00 equivale a US$19.05.
    ```

#### Exercício 28: Simulador de Lanchonete
*   **Nível:** Difícil
*   **Enunciado:** Crie um programa que simule o sistema de pedidos de uma lanchonete.
    1.  Crie um menu de produtos com preços (use um dicionário).
    2.  Crie uma função `mostrar_menu()`.
    3.  Crie uma função `fazer_pedido()` que permita ao usuário adicionar vários itens ao carrinho.
    4.  Crie uma função `calcular_conta(pedido)` que calcula o total a pagar.
    5.  O programa principal deve orquestrar essas funções.
*   **Exemplo de Entrada:**
    ```text
    --- Cardápio ---
    1: Hambúrguer - R$15.00
    2: Batata Frita - R$8.00
    3: Refrigerante - R$5.00
    
    Pedido (digite o código ou 'fim' para encerrar): 1
    Pedido (digite o código ou 'fim' para encerrar): 3
    Pedido (digite o código ou 'fim' para encerrar): fim
    ```
*   **Exemplo de Saída:**
    ```text
    --- Seu Pedido ---
    Hambúrguer: R$15.00
    Refrigerante: R$5.00
    Total a pagar: R$20.00
    ```

#### Exercício 29: Simulador de Caixa Eletrônico
*   **Nível:** Difícil
*   **Enunciado:** Faça um programa que simule um caixa eletrônico. O programa deve ter um saldo inicial e um menu com as opções: Ver Saldo, Depositar, Sacar e Sair.
    *   Crie funções para cada operação.
    *   Na função `depositar`, não aceite valores negativos.
    *   Na função `sacar`, não permita saques de valores negativos ou maiores que o saldo disponível.
*   **Exemplo de Entrada:**
    ```text
    1. Ver Saldo
    2. Depositar
    3. Sacar
    4. Sair
    Escolha uma opção: 2
    Valor do depósito: 200
    ```
*   **Exemplo de Saída:**
    ```text
    Depósito de R$200.00 realizado com sucesso.
    Saldo atual: R$1200.00 (supondo um saldo inicial de R$1000)
    ```

#### Exercício 30: Agenda de Contatos
*   **Nível:** Difícil
*   **Enunciado:** Crie um programa que funcione como uma agenda de contatos. Use um dicionário para armazenar os contatos, onde a chave é o nome e o valor é outro dicionário com telefone e e-mail. Crie funções para: Adicionar Contato, Buscar Contato, Listar Contatos, Remover Contato e Sair.
*   **Exemplo de Entrada:**
    ```text
    1. Adicionar Contato
    2. Buscar Contato
    3. Sair
    Escolha uma opção: 1
    Nome: Ana
    Telefone: 9999-8888
    Email: ana@email.com
    ```
*   **Exemplo de Saída (após buscar por "Ana"):**
    ```text
    Contato encontrado:
    Nome: Ana
    Telefone: 9999-8888
    Email: ana@email.com
    ```
