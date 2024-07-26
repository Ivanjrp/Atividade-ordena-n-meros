 Algoritmos de Ordenação

 Executáveis

 insertion.exe
- Uso:`insertion.exe [nome do arquivo]`
- Saída: Exibe o tempo de execução do algoritmo Insertion Sort no console.
- Exemplo: `./insertion.exe num.1000.1.in` retorna `0.00088`

 selection.exe
- Uso: `selection.exe [nome do arquivo]`
- Saída: Exibe o tempo de execução do algoritmo Selection Sort no console.
- Exemplo: `./selection.exe num.1000.1.in` retorna `0.00132`

 ordenacoes.exe
- Uso: `ordenacoes.exe [nome do arquivo]`
- Saída: Exibe os tempos de execução de ambos os algoritmos (Insertion Sort e Selection Sort) no console, permitindo a comparação.
- Exemplo: `./ordenacoes.exe num.1000.1.in` retorna `Insertion x Selection 0.00070 X 0.00168`

 main.exe
- Uso: `main.exe`
- Saída: Exibe uma tabela no console com os tempos de execução de todos os casos de teste, comparando os tempos de ambos os algoritmos.
- Exemplo: `./main.exe` retorna uma tabela com as comparações de tempo, como mostrado abaixo:

  ```
  Insertion x Selection
  
  num.1000.1.in: 0.00094 X 0.00124
  num.1000.2.in: 0.00065 X 0.00155
  num.1000.3.in: 0.00064 X 0.00123
  num.1000.4.in: 0.00064 X 0.00141
  num.10000.1.in: 0.09160 X 0.15639
  num.10000.2.in: 0.08055 X 0.12119
  num.10000.3.in: 0.07112 X 0.12049
  num.10000.4.in: 0.07541 X 0.12927
  num.100000.1.in: 9.66665 X 14.20567
  num.100000.2.in: 8.88193 X 14.63092
  num.100000.3.in: 8.41695 X 15.07896
  num.100000.4.in: 7.92914 X 14.69483
  ```

 Compilação
Para compilar os programas, utilize o comando `make` no terminal dentro do diretório onde o Makefile está localizado. Esse comando irá gerar os executáveis `insertion.exe`, `selection.exe`, `ordenacoes.exe` e `main.exe`.

```
make
```

 Execução
Para executar cada programa, utilize a linha de comando conforme descrito:

- insertion.exe: `./insertion.exe [nome do arquivo]`
- selection.exe: `./selection.exe [nome do arquivo]`
- ordenacoes.exe: `./ordenacoes.exe [nome do arquivo]`
- main.exe: `./main.exe`
