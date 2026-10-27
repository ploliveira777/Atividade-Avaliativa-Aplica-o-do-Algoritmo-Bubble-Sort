# Atividade-Avaliativa-Aplica-o-do-Algoritmo-Bubble-Sort
Loja Virtual — Ordenação de Preços com Bubble Sort
1. Identificação do projeto
Disciplina:  Algoritmos e Pensamento Computacional
Professora:  Profa. Karla R. Sartin
Integrantes: Paulo Victor Oliveira Dos Santos
Linguagem: C
Algoritmo utilizado: Bubble Sort
2. Contextualização

Uma loja virtual possui diversos produtos com preços diferentes. Para facilitar a visualização e a comparação dos valores, é importante organizar os preços em ordem crescente.

Este projeto apresenta uma aplicação desenvolvida em linguagem C que utiliza o algoritmo Bubble Sort para ordenar os preços de dez produtos, do menor para o maior.

3. Objetivo

Desenvolver um programa que aplique os conceitos de arrays, estruturas de repetição, estruturas condicionais e algoritmos de ordenação, utilizando o Bubble Sort para organizar os preços de produtos de uma loja virtual.

4. Funcionamento do programa

O programa armazena os preços de dez produtos em um array de números reais.

Inicialmente, apresenta todos os preços na ordem original. Em seguida, utiliza o Bubble Sort para comparar elementos adjacentes e trocar suas posições quando o preço atual é maior que o próximo.

Após a ordenação, o programa exibe os preços em ordem crescente e informa o menor e o maior valor encontrados.

5. Algoritmo Bubble Sort

O Bubble Sort funciona por meio de comparações sucessivas entre elementos vizinhos de um array.

Neste projeto, são utilizados dois laços de repetição. O laço externo controla as passagens e o laço interno realiza as comparações. Quando um preço é maior que o preço seguinte, os valores são trocados com o auxílio de uma variável temporária.

O processo continua até que os preços estejam ordenados do menor para o maior.

6. Tecnologias e ferramentas
Linguagem C
Compilador GCC
Visual Studio Code ou outro editor compatível
Git para controle de versão
GitHub para hospedagem do código-fonte
7. Como compilar e executar

É necessário ter um compilador C, como o GCC, instalado no computador.

Compilação
bash
gcc loja_virtual.c -o loja_virtual

Execução no Linux ou macOS
bash
./loja_virtual

Execução no Windows
bash
loja_virtual.exe


Os comandos de execução pressupõem que a compilação foi realizada no diretório do projeto.

8. Exemplo de entrada e saída

O programa utiliza dez preços previamente definidos no código, portanto não exige entrada de dados pelo usuário.

Preços antes da ordenação
text
199.90, 49.90, 89.90, 29.90, 149.90,
19.90, 299.90, 79.90, 59.90, 119.90

Preços depois da ordenação
text
19.90, 29.90, 49.90, 59.90, 79.90,
89.90, 119.90, 149.90, 199.90, 299.90


Critério: ordem crescente, do menor para o maior.

9. Versionamento com Git e GitHub

O Git é utilizado para registrar as alterações realizadas durante o desenvolvimento, enquanto o GitHub permite armazenar e compartilhar o projeto.

O histórico de commits deve demonstrar a evolução real do trabalho, incluindo a criação do código, os testes, a documentação e as melhorias realizadas.

10. Considerações finais

O desenvolvimento deste projeto permitiu aplicar conceitos fundamentais da programação em C, como arrays, variáveis, estruturas condicionais e laços de repetição.

A utilização do Bubble Sort demonstrou como os elementos de um conjunto de dados podem ser organizados por meio de comparações e trocas sucessivas.

A aplicação representa uma situação prática de uma loja virtual e contribui para a compreensão dos algoritmos de ordenação e do controle de versão com Git e GitHub.
