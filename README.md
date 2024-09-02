# 2023.2

# Coleção de Exercícios e Projetos em C com Estruturas de Dados

## Descrição
Este repositório contém uma coleção abrangente de exercícios e projetos desenvolvidos em C, focando em diversas estruturas de dados e algoritmos. O projeto inclui a manipulação de listas encadeadas, pilhas, árvores binárias, e sistemas de cadastro e gestão de informações. Cada projeto é complementado por bibliotecas auxiliares e arquivos de cabeçalho que fornecem funções adicionais para manipulação e persistência de dados.

## Estrutura dos Arquivos

### Arquivos C

- **Exercicio2.c**: Implementa [descrição específica do exercício].
- **main.c**: Arquivo principal que contém [descrição específica do main.c].
- **Maior Menor Idade Feminino Masculino.c**: Código que processa dados sobre idade e gênero, determinando a maior e menor idade, além de contar o número de homens e mulheres.
- **Cadastro Aluno.c**: Sistema de cadastro que permite operações de inclusão, edição e exclusão de registros de alunos.
- **Banco de Dados.c**: Implementação básica de um sistema de banco de dados para gerenciamento de registros.
- **Poltronas.c**: Sistema para gerenciar a reserva e compra de poltronas, com controle sobre os assentos disponíveis e reservados.

### Arquivos de Cabeçalho

- **Carrega_arquivos2.h**: Contém funções para carregar dados de arquivos em estruturas específicas.
- **arvore.h**: Implementa a manipulação de árvores binárias, incluindo inserção, remoção e navegação.
- **ExemploPilhaC.h**: Implementa operações de pilha, incluindo empilhamento e desempilhamento.
- **Salva_arquivo.h**: Funções para salvar dados em arquivos, garantindo a persistência das informações.
- **tad_lst1.h**: Define e implementa funções para manipulação de listas encadeadas.
- **tad_lst2.h**: Versão alternativa de `tad_lst1.h` com funcionalidades adicionais ou modificadas.
- **tad_pilha1.h**: Implementa operações básicas de pilha utilizando um array estático.
- **tad_pilha2.h**: Versão alternativa de `tad_pilha1.h`, possivelmente com suporte a pilhas dinâmicas.
- **metodos_auxiliares.h**: Inclui métodos auxiliares utilizados em diversos arquivos para operações comuns.
- **leitura.h**: Contém funções para leitura de dados de entrada e manipulação de strings.
- **persistencia.h**: Funções para salvar e carregar dados, focadas na persistência de informações.

### Outros Arquivos

- **Makefile**: Facilita a compilação dos projetos através de comandos simplificados.
- **replit.nix**: Configuração para o ambiente Replit, especificando as dependências e o ambiente necessário para compilar e executar os projetos.

## Como Usar

### Compilação

1. Para compilar qualquer um dos projetos, você pode utilizar o `Makefile` incluído ou compilar manualmente utilizando o gcc. Exemplo:
   ```bash
   gcc -o nome_do_executavel arquivo.c
   ```
   Para utilizar o `Makefile`, basta rodar:
   ```bash
   make
   ```
   Isso gerará os executáveis para os arquivos principais.

### Execução

2. Após a compilação, execute o programa gerado:
   ```bash
   ./nome_do_executavel
   ```
   Dependendo do arquivo `.c` em questão, o programa pode pedir entradas do usuário ou realizar operações de leitura/escrita em arquivos.

### Estruturas de Dados Utilizadas

Este repositório abrange uma ampla variedade de estruturas de dados:
- **Listas Encadeadas**: Utilizadas para armazenar e manipular conjuntos de elementos de forma dinâmica.
- **Pilhas**: Estruturas LIFO (Last In, First Out) implementadas tanto com arrays estáticos quanto com alocação dinâmica.
- **Árvores Binárias**: Estruturas hierárquicas para armazenar dados de forma ordenada, permitindo operações eficientes de busca, inserção e remoção.
- **Sistemas de Cadastro**: Implementam a manipulação de registros, como informações de alunos ou dados de banco de dados simples.

### Exemplos de Uso

Para compilar e executar o sistema de cadastro de alunos:
```bash
gcc -o cadastro_aluno Cadastro\ Aluno.c
./cadastro_aluno
```

Para compilar e executar o sistema de reserva de poltronas:
```bash
gcc -o poltronas Poltronas.c
./poltronas
```

## Ambiente de Desenvolvimento

O arquivo `replit.nix` está incluído para facilitar a configuração do ambiente de desenvolvimento em plataformas como o Replit. Ele especifica as dependências necessárias para compilar e executar os projetos.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias no código, correções de bugs ou novas funcionalidades.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
