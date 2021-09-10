# Listas e Tabelas
Este arquivo traz algumas dicas para adicionar listas e tabelas ao arquivo markdown

## Tipos de Listas

#### Lista Não Ordenada
- Item
    - Sub Item
* Item
    * Sub Item
    * Sub Item
- Item
    * Sub Item
        - Sub Item

#### Lista Ordenada

1. Item
    1.1 Sub Item

2. Item
    2.1 Sub Item
    2.2 Sub Item

3. Item
    3.1 Sub Item
        3.1.1 Sub Item

#### Lista Ordenada Automática

1. Item
    1.1. Sub Item

1. Item
    2.1 Sub Item
    2.2 Sub Item

1. Item
    2.1. Sub Item
        3.1.1. Sub Item

#### Lista de Tarefas

- [ ] Tarefa 1
- [ ] Tarefa 2
- [x] Tarefa 3
- [x] ~~Tarefa 4~~

## Tabelas

Coluna 1 | Coluna 2
--------|--------
Valor 1 | 1
Valor 2 | 2
Valor 3 | 3
Valor 4 | 4

Por Padrão, o conteúdo das tabelas são alinhadas à esquerda

#### Alinhamento à direita
Coluna 1 | Coluna 2
--------|--------:
Valor 1 | **1**
Valor 2 | **2**
Valor 3 | **3**
Valor 4 | **4**

#### Alinhamento centralizado

Coluna 1 | Coluna 2
:--------:|--------:
**Valor 1** | 1
**Valor 2** | 2
**Valor 3** | 3
**Valor 4** | 4