# Script para processamento de planilhas usando python

Os dados gerados tem uma saida da seguinte forma

        [
          { 'Horas': 0, 'Quantidade': 21052 },
          { 'Horas': 1, 'Quantidade': 15609 },
          { 'Horas': 2, 'Quantidade': 17238 },
          { 'Horas': 3, 'Quantidade': 15634 },
          { 'Horas': 4, 'Quantidade': 17063 },
          { 'Horas': 5, 'Quantidade': 16305 },
          { 'Horas': 6, 'Quantidade': 16823 },
          { 'Horas': 7, 'Quantidade': 15510 },
          { 'Horas': 8, 'Quantidade': 16968 },
          { 'Horas': 9, 'Quantidade': 15661 },
          { 'Horas': 10, 'Quantidade': 16750 },
          { 'Horas': 11, 'Quantidade': 18491 },
          { 'Horas': 12, 'Quantidade': 20636 },
          { 'Horas': 13, 'Quantidade': 17469 },
          { 'Horas': 14, 'Quantidade': 16532 },
          { 'Horas': 15, 'Quantidade': 15728 },
          { 'Horas': 16, 'Quantidade': 16575 },
          { 'Horas': 17, 'Quantidade': 19057 },
          { 'Horas': 18, 'Quantidade': 20650 },
          { 'Horas': 19, 'Quantidade': 18230 },
          { 'Horas': 20, 'Quantidade': 17173 },
          { 'Horas': 21, 'Quantidade': 15916 },
          { 'Horas': 22, 'Quantidade': 17616 },
          { 'Horas': 23, 'Quantidade': 15763 }
        ]
Forma essa que pode ser usada como lista de objetos JSON, assim podendo criar graficos com os mesmos dados

## Forma de usar

1. Primeiro é necessário ter o arquivo da planilha "xlsx" e saber o nome da planilha, esses nomes devem ser inseridos no arquivo "script.py"
1. No final da planilha na primeira coluna é necessário inserir um sinalizador, no caso desse script a palavra "FIM"

