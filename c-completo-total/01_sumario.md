# Sumário

## Prefácio

- Um Livro para Todos os Programadores
- O Que Há de Novo Nesta Edição
- O Que Há no Livro

## [Parte 1 — A Linguagem C](02_parte_1_a_linguagem_c.md)

1. Uma Visão Geral de C
    - As Origens de C
    - C É uma Linguagem de Médio Nível
    - C É uma Linguagem Estruturada
    - C É uma Linguagem para Programadores
    - Compiladores Versus Interpretadores
    - A Forma de um Programa em C
    - A Biblioteca e a Linkedição
    - Compilação Separada
    - Compilando um Programa em C
    - O Mapa de Memória de C
    - C Versus C++
        - Um Compilador C++ Funcionará com Programas C?
    - Uma Revisão de Termos

1. Expressões em C
    - Os Cinco Tipos Básicos de Dados
    - Modificando os Tipos Básicos
    - Nomes de Identificadores
    - Variáveis
        - Onde as Variáveis São Declaradas
        - Variáveis Locais
        - Parâmetros Formais
        - Variáveis Globais
    - Modificadores de Tipo de Acesso
        - `const`
        - `volatile`
    - Especificadores de Classe de Armazenamento
        - `extern`
        - Variáveis `static`
        - Variáveis `register`
    - Inicialização de Variáveis
    - Constantes
        - Constantes Hexadecimais e Octais
        - Constantes String
        - Constantes Caractere de Barra Invertida
    - Operadores
        - Operador de Atribuição
        - Conversão de Tipos em Atribuições
        - Atribuições Múltiplas
        - Operadores Aritméticos
        - Incremento e Decremento
        - Operadores Relacionais e Lógicos
        - Operadores Bit a Bit
        - Operador `?`
        - Operadores de Ponteiros `&` e `*`
        - Operador em Tempo de Compilação `sizeof`
        - Operador Vírgula
        - Operadores Ponto (`.`) e Seta (`->`)
        - Parênteses e Colchetes como Operadores
        - Resumo das Precedências
    - Expressões
        - Ordem de Avaliação
        - Conversão de Tipos em Expressões
        - Casts
        - Espaçamento e Parênteses
        - C Reduzido

1. Comandos de Controle do Programa

    - Verdadeiro e Falso em C
    - Comandos de Seleção
        - if
        - ifs Aninhados
        - A Escada if-else-if
        - O ? Alternativo
        - A Expressão Condicional
        - switch
        - Comandos switch Aninhados
    - Comandos de Iteração
        - O Laço for
        - Variações do Laço for
        - O Laço Infinito
        - Laços for sem Corpos
        - O Laço while
        - O Laço do-while
    - Comandos de Desvio
        - O Comando return
        - O Comando goto
        - O Comando break
        - A Função exit()
        - O Comando continue
    - Comandos de Expressões
    - Blocos de Comandos

1. Matrizes e Strings
    - Matrizes Unidimensionais
    - Gerando um Ponteiro para uma Matriz
    - Passando Matrizes Unidimensionais para Funções
    - Strings
    - Matrizes Bidimensionais
        - Matrizes de Strings
    - Matrizes Multidimensionais
    - Indexando Ponteiros
    - Inicialização de Matriz
    - Inicialização de Matrizes Não-Dimensionadas
    - Um Exemplo com o Jogo-da-Velha

1. Ponteiros
    - O Que São Ponteiros?
    - Variáveis Ponteiros
    - Os Operadores de Ponteiros
    - Expressões com Ponteiros
        - Atribuição de Ponteiros
        - Aritmética de Ponteiros
        - Comparação de Ponteiros
    - Ponteiros e Matrizes
        - Matrizes de Ponteiros
    - Indireção Múltipla
    - Inicialização de Ponteiros
    - Ponteiros para Funções
    - As Funções de Alocação Dinâmica em C
        - Matrizes Dinamicamente Alocadas
    - Problemas com Ponteiros

1. Funções
    - A Forma Geral de uma Função
    - Regras de Escopo de Funções
    - Argumentos de Funções
        - Chamada por Valor, Chamada por Referência
        - Criando uma Chamada por Referência
        - Chamando Funções com Matrizes
    - argc e argv — Argumentos para main
    - O Comando return
        - Retornando de uma Função
        - Retornando Valores
    - Funções Que Devolvem Valores Não-Inteiros
    - Protótipos de Funções
    - Retornando Ponteiros
    - Funções do Tipo void
    - O Que main Devolve?
    - Recursão
    - Declarando uma Lista de Parâmetros de Extensão Variável
    - Declaração de Parâmetros de Funções Moderna Versus Clássica
    - Questões sobre a Implementação
        - Parâmetros e Funções de Propósito Geral
        - Eficiência
    - Bibliotecas e Arquivos
        - Arquivos Separados
        - Bibliotecas
        - De Que Tamanho Deve Ser um Arquivo de Programa?

1. Estruturas, Uniões, Enumerações e Tipos Definidos pelo Usuário
1. E/S pelo Console
1. E/S com Arquivo
1. O Pré-processador de C e Comentários

## Parte 2 — A Biblioteca C Padrão

1. Linkedição, Bibliotecas e Arquivos de Cabeçalho
    - O Linkeditor
    - Compilação Separada
    - Código Relocável
    - Linkeditando com Overlays
    - Linkeditando com DILs
    - A Biblioteca C Padrão
        - Arquivos de Biblioteca Versus Arquivos-Objetos
    - Arquivos de Cabeçalho
        - Macros em Arquivos de Cabeçalho
    - Redefinição das Funções da Biblioteca
1. Funções de E/S
1. Funções de String e de Caracteres
1. Funções Matemáticas
1. Funções de Hora, Data e Outras Relacionadas com o Sistema
1. Alocação Dinâmica
1. Funções Gráficas e de Texto
1. Funções Miscelâneas

## Parte 3 — Algoritmos e Aplicações

1. Ordenação e Pesquisa
    - Ordenação
        - Tipos de Algoritmos de Ordenação
        - Uma Avaliação dos Algoritmos de Ordenação
        - A Ordenação Bolha — O Demônio das Trocas
        - Ordenação por Seleção
        - Ordenação por Inserção
        - Ordenações Melhores
        - Ordenação Shell
        - Quicksort
    - Escolhendo uma Ordenação
    - Ordenando Outras Estruturas de Dados
        - Ordenação de Strings
        - Ordenação de Estruturas
    - Ordenando Arquivos de Acesso Aleatório em Disco
    - Pesquisa
        - Métodos de Pesquisa
        - A Pesquisa Sequencial
        - Pesquisa Binária
1. Filas, Pilhas, Listas Encadeadas e Árvores Binárias
    - Filas
    - A Fila Circular
    - Pilhas
    - Listas Encadeadas
    - Listas Singularmente Encadeadas
    - Listas Duplamente Encadeadas
    - Um Exemplo de Lista Postal
    - Árvores Binárias
1. Matrizes Esparsas
    - A Matriz Esparsa com Lista Encadeada
        - Análise da Abordagem com Lista Encadeada
    - A Abordagem com Árvore Binária para Matriz Esparsa
        - Análise da Abordagem com Árvores Binárias
    - A Abordagem com Matriz de Ponteiros para Matriz Esparsa
        - Análise da Abordagem com Matriz de Ponteiros
    - Hashing
        - Análise de Hashing
    - Escolhendo uma Abordagem
1. Análise de Expressões e Avaliação
    - Expressões
    - Dissecando uma Expressão
    - Análise de Expressão
    - Um Analisador Simples de Expressões
    - Acrescentando Variáveis ao Analisador
    - Verificação de Sintaxe em um Analisador Recursivo Descendente
1. Solução de Problemas de Inteligência Artifical
    - Representação e Terminologia
    - Explosões Combinatórias
    - Técnicas de Pesquisa
    - Avaliação das Pesquisas
    - Uma Representação Gráfica
    - A Pesquisa de Profundidade Primeiro
        - Uma Análise da Pesquisa de Profundidade Primeiro
    - A Pesquisa de Extensão Primeiro
        - Uma Análise da Pesquisa de Extensão Primeiro
    - Adicionando Heurísticas
    - A Pesquisa da Escalada da Montanha
        - Análise da Escalada da Montanha
    - A Pesquisa por Menor Esforço
        - Análise da Pesquisa por Menor Esforço
    - Escolhendo uma Técnica de Pesquisa
    - Encontrando Múltiplas Soluções
    - 526 Remoção de Percurso
        - Remoção de Nó
    - Encontrando a Solução Ideal
    - De Volta às Chaves Perdidas
1. Construindo o Esqueleto de um Programa Windows 95
    - A Perspectiva da Programação Windows 95
        - O Modelo da Mesa de Trabalho
        - O Mouse
        - Ícones e Mapas de Bits
        - Menus, Barras de Ferramentas, Barras de Status e Caixas de Diálogo
    - Como Windows 95 e Seu Programa Interagem
    - Windows 95 Usa Multitarefa Preemptiva
    - A API Win32: À API de Windows 95
    - Os Componentes de uma Janela
    - Noções Básicas sobre Aplicações Windows 95
        - WinMain()
        - A Função de Janela
        - Classes de Janelas
        - A Repetição de Mensagens
        - Os Tipos de Dados Windows
    - Um Esqueleto Windows 95
        - Definindo a Classe de Janela
        - Criando uma Janela
        - A Repetição de Mensagens
    - A Função de Janela
    - Usando um Arquivo de Definição
    - Convenções sobre Nomes

## Parte 4 — Desenvolvimento de Software Usando C
