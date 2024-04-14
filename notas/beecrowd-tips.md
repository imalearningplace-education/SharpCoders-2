# Dicas Beecrowd

## Entradas em uma linha

- objeto: soma dois valores
- entrada: `2 3`
- saida: `5`

- split: separar

```cs
string linha = Console.ReadLine(); // 2 3
string[] dados = linha.Split(' '); // ['2', '3']

int a = int.Parse(dados[0]); // int a = 2
int b = int.Parse(dados[1]); // int b = 3
```

fazendo mais curto:

```cs
string a, b = Console.ReadLine().Split(' '); 

int a = int.Parse(a); // int a = 2
int b = int.Parse(b); // int b = 3
```

## Posicoes anteriores e posteriores em vetor

Problema de borda.

- checar até onde vai e garantir que não acessa posições indesejadas
- borda falsa

## Criando projeto CLI (Command Line Interface)

checando dotnet:

```bash
dotnet --version
```

criando em .net6:

```bash
dotnet new console -n NomeDoProjeto --framework net6.0
```
