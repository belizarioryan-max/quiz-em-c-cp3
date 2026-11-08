# Quiz em C --- Projeto Integrador CP3

Projeto desenvolvido em linguagem C para a disciplina **Algoritmos e
Pensamento Computacional --- 2026/2**, como parte do Checkpoint 3 (CP3).

O sistema permite cadastrar perguntas, realizar um quiz, calcular a
pontuação dos jogadores, salvar o histórico em arquivos e apresentar um
ranking com os melhores resultados.

## 🎥 Vídeo de apresentação

Assista à demonstração do projeto:

[▶️ Assistir ao vídeo no YouTube](https://youtu.be/UtgyRmqBxqI)

## ✨ Funcionalidades

-   Cadastro e armazenamento de perguntas.
-   Execução do quiz e registro das respostas.
-   Cálculo da pontuação e do percentual de acertos.
-   Registro do histórico dos jogadores.
-   Exibição do ranking de jogadores.
-   Organização do ranking em ordem decrescente usando o algoritmo
    Bubble Sort.
-   Leitura e gravação de dados em arquivos `.txt`.

## 🧠 Conceitos utilizados

-   Linguagem C.
-   Structs para organizar os dados de perguntas e jogadores.
-   Vetores para armazenar e manipular informações.
-   Funções para dividir e organizar o código.
-   Manipulação de arquivos com leitura e escrita.
-   Estruturas condicionais e de repetição.
-   Algoritmo de ordenação Bubble Sort.

## 📁 Estrutura do projeto

``` text
quiz-em-c-cp3/
├── include/
│   ├── funcoes.h
│   └── modulo.h
├── src/
│   ├── main.c
│   ├── funcoes.c
│   └── modulo.c
├── data/
│   ├── perguntas.txt
│   └── historico.txt
├── .gitignore
└── README.md
```

## ⚙️ Como compilar e executar

É necessário ter um compilador C, como o GCC, instalado.

No terminal, dentro da pasta principal do projeto, execute:

``` bash
gcc -Wall -Wextra -Iinclude src/main.c src/funcoes.c src/modulo.c -o programa
```

Depois, execute o programa:

**Windows:**

``` bash
programa.exe
```

**Linux/macOS:**

``` bash
./programa
```

## 📊 Ordenação do ranking

O ranking utiliza o algoritmo **Bubble Sort** para comparar o percentual
de acertos dos jogadores e organizar os resultados em ordem decrescente,
do maior para o menor.

## 💾 Armazenamento dos dados

As perguntas e o histórico dos jogadores são armazenados em arquivos de
texto:

-   `perguntas.txt`: contém as perguntas utilizadas no quiz.
-   `historico.txt`: registra os resultados dos jogadores.

## 🎓 Sobre o projeto

Trabalho acadêmico desenvolvido para o **Checkpoint 3 (CP3)** da
disciplina **Algoritmos e Pensamento Computacional**, no segundo
semestre de 2026.

------------------------------------------------------------------------

**Projeto acadêmico --- Quiz em C \| CP3 --- 2026/2**