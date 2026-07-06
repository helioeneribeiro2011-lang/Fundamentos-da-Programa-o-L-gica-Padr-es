# Fundamentos-da-Programa-o-L-gica-Padr-es
Este projeto tem como objetivo ajudar de forma dinâmica a compreender um pouco sobre lógica de programação. Para nortear de forma simples, mas não completa, sobre alguns princípios fundamentais.

<GLOSSÁRIO>


Algoritmo: Definido como uma sequência de instruções ordenada, finita e não ambígua para atingir um objetivo específico
. Pode ser comparado a uma receita de passos detalhados
.
Arrays (Vetores/Matrizes): Sequências de posições de memória que contêm dados do mesmo tipo, acessíveis diretamente através de subíndices
.
Atribuição: Operação que armazena um valor dentro de uma variável, frequentemente representada pelo símbolo := ou por uma seta
.


Classe: Descrição de um conjunto de objetos que compartilham características (atributos) e comportamentos (métodos) comuns
.
Condicionais (Estruturas Seletivas): Estruturas que permitem ao programa tomar diferentes caminhos de execução baseados no resultado de uma expressão lógica (ex: se-então-senão)
.
Constante: Dado ou valor que permanece inalterado durante todo o desenvolvimento do algoritmo e execução do programa
.
*C

Design Patterns (Padrões de Projeto): Descrições ou modelos reutilizáveis que oferecem soluções testadas para problemas recorrentes na arquitetura de software
. Eles são divididos em três categorias: criacionais, estruturais e comportamentais
.


Encapsulamento: Princípio de ocultar a representação interna e os detalhes de implementação de um objeto, permitindo o acesso apenas através de operações definidas
.
Escopo: Refere-se à visibilidade e validade de uma variável, podendo ser local (confunada a um subprograma) ou global (acessível em todo o programa)
.
Estrutura de Dados: Forma organizada de armazenamento e manipulação de informações na memória do computador, podendo ser estática ou dinâmica
.


Fluxograma: Representação visual e gráfica dos passos de um algoritmo utilizando símbolos geométricos padronizados
.
Função: Um subprograma que executa uma tarefa específica e devolve (retorna) um resultado ao módulo que o invocou
.


Laços de Repetição (Loops): Estruturas que repetem um bloco de instruções enquanto uma condição for verdadeira ou por um número definido de vezes (ex: enquanto, para, repita-até)
.
Lógica de Programação: O raciocínio por trás da resolução de problemas, consistindo em organizar instruções para orientar o computador
.


Objeto: Unidade fundamental da programação orientada a objetos que combina dados e as funções (métodos) que operam sobre eles
.
Operadores: Símbolos que realizam ações sobre os dados. São divididos em aritméticos (cálculos), relacionais (comparações) e lógicos (combinações de condições)
.


Paradigma de Programação: Um modelo ou padrão a ser seguido no desenvolvimento de software, como o imperativo (foco no "como" fazer) ou o declarativo (foco no "o que" obter)
.
Polimorfismo: Propriedade que permite que uma mesma mensagem ou operação atue de diferentes maneiras dependendo do objeto sobre o qual é aplicada
.
Portugol (Português Estruturado): Linguagem narrativa simplificada usada para descrever algoritmos em português, facilitando o aprendizado da lógica antes do uso de linguagens profissionais
.


Recursividade: Propriedade de uma função ou procedimento de invocar a si mesmo para resolver subproblemas menores de um problema original
.


SOLID: Acrônimo para cinco princípios fundamentais de design que tornam o software orientado a objetos mais robusto, flexível e fácil de manter
.


Tipos de Dados: Definição da natureza da informação armazenada. Os tipos primitivos incluem inteiro (sem casas decimais), real (com casas decimais), caracter (texto) e lógico (booleano: verdadeiro ou falso)
.


Variável: Espaço alocado na memória para guardar dados cujo valor pode mudar durante a execução do algoritmo




A lógica de programação é o pilar fundamental para a criação de softwares e consiste no raciocínio por trás da resolução de problemas, utilizando uma sequência de instruções que orientam o computador a realizar tarefas
. Aprender lógica permite que você converta desafios do cotidiano em passos que uma máquina pode executar, independentemente da linguagem de programação escolhida
.
Para começar do zero, você deve dominar os seguintes conceitos básicos:
1. O que é um Algoritmo?
Um algoritmo é a prática da lógica. É definido como uma sequência de instruções ordenada, finita e não ambígua para atingir um objetivo
. Uma analogia comum é uma receita de bolo ou os passos para fazer um sanduíche: se a ordem estiver incorreta, o resultado final falha
.
2. Estruturas Fundamentais
Para construir algoritmos, você utilizará estas ferramentas básicas:
Variáveis: Funcionam como "caixas" na memória do computador para guardar dados (números, textos, valores lógicos)
.
Tipos de Dados: Definem a natureza da informação. Os tipos primitivos são:
Inteiro: Números sem casas decimais
.
Real: Números com casas decimais
.
Caracter/Cadeia (Texto): Letras, símbolos e frases
.
Lógico (Booleano): Assume apenas dois estados: verdadeiro ou falso
.
Operadores:
Aritméticos: Para cálculos (+, -, *, /) e o módulo (resto da divisão)
.
Relacionais: Para comparações (igual, diferente, maior, menor)
.
Lógicos: Para combinar condições, como E (AND), OU (OR) e NÃO (NOT)
.
3. Estruturas de Controle (Decisões e Repetições)
Elas determinam o fluxo de execução do programa:
Condicionais (se-então-senão): Permitem que o programa tome caminhos diferentes baseados em uma condição
. Exemplo: "Se estiver chovendo, leve guarda-chuva; senão, não leve"
.
Estrutura de Seleção (escolha-caso): Ideal para quando existem muitas opções para uma mesma variável, como um menu
.
Laços de Repetição (Loops): Repetem instruções várias vezes.
Enquanto (while): Repete enquanto uma condição for verdadeira (teste no início)
.
Para (for): Usado quando se sabe de antemão quantas vezes o código deve ser repetido
.
4. Como Praticar e Representar a Lógica
Antes de escrever código em linguagens profissionais como Python ou Java, recomenda-se usar:
Fluxogramas: Representações visuais dos passos usando símbolos geométricos
.
Pseudocódigo (Portugol): Uma forma de descrever algoritmos usando linguagem natural (português estruturado) para focar na lógica antes da sintaxe
.
Ferramentas: O VisuAlg e o Portugol Studio são IDEs brasileiras excelentes para iniciantes praticarem sem a barreira do inglês
.
Metodologia para Resolver Problemas
Bons programadores planejam antes de escrever o código
. A técnica de decomposição consiste em dividir um problema complexo em partes menores e mais simples
. Por exemplo, para calcular o valor de uma compra, você primeiro identifica os produtos, depois os preços, calcula o subtotal e só então aplica descontos ou frete
.
A prática constante é o segredo: tente observar atividades cotidianas e descrevê-las como sequências lógicas de passos
.
