## Definição
O GOMS (Goals, Operators, Methods, and Selection Rules - Objetivos, Operadores, Métodos e
Regras de Seleção) é um conjunto de modelos utilizados para análise de tarefas.

O CMN-GOMS (Card, Moran e Newell GOMS) é um desses modelos e consiste em uma hierarquia bem definida de objetivos representados em forma de programa, permitindo assim uma análise executável.

## Participantes
- Amanda Bezerra

## Legenda
| Termo    | Tradução         | Descrição                                                             |
| -------- | ---------------- | --------------------------------------------------------------------- |
| Goal     | Objetivo         | O que o usuário quer realizar utilizando o sistema                    |
| OP       | Operador         | Ações concretas que o site permite que o usuário faça              |
| METHOD   | Método           | Sequência de subobjetivos e operadores para atingir um objetivo maior |
| SEL.RULE | Regra de seleção | Tomada de decisão sobre qual método utilizar                          |

## Análise
Essa é uma análise que busca mapear a sequência e quantidade de objetivos, subobjetivos, métodos e operações utilizados para atingir algumas tarefas de caráter rotineiro do site foco desse projeto.
Cabe destacar que para cada objetivo é partido do princípio que o usuário está na página inicial do site.

Abaixo está a lista de objetivos analisados.

### Copiar telefone de contato de uma Secretaria específica
```
Goal 0: Copiar telefone de contato de uma Secretaria específica
  Goal 1: Encontrar informações da Secretaria desejada
    METHOD 1.A: Encontrar através do menu GOVERNO
    (SEL.RULE: peferência do usuário)
      OP: Levar cursor até menu "GOVERNO"
      OP: Levar cursor até menu "SECRETARIAS"
      OP: Levar cursor até opção com nome da Secretaria desejada
      OP: Clicar com o botão esquerdo do mouse
    METHOD 1.B: Encontrar através do menu CONTATOS
    (SEL.RULE: peferência do usuário)
      OP: Levar cursor até menu "CONTATOS"
      OP: Clicar com o botão esquerdo do mouse
      OP: Localizar linha na tabela com nome da Secretaria desejada
      OP: Levar cursor até número na coluna "Fone" da linha localizada
  Goal 2: Copiar telefone
    OP: Clicar com botão direito do mouse
    OP: Levar cursor até a opção menu "Copiar"
    OP: Clicar com botão esquerdo do mouse
```

___

### Baixar formulário de pessoa física para reclamação

```
Goal 0: Baixar formulário de pessoa física para reclamação
  Goal 1: Acessar página de Acesso à Informação
    METHOD 1.A: Acessar através do menu principal
    (SEL.RULE: preferência do usuário)
      OP: Levar cursor até o menu "INFORMAÇÕES"
      OP: Clicar com o botão esquerdo do mouse
    METHOD 1.B: Acessar através do botão de acesso à informação
    (SEL.RULE: preferência do usuário)
      OP: Levar cursor até o botão "Acesso  à Informação"
      OP: Clicar com o botão esquerdo do mouse
  Goal 2: Acessar página de Formulários
    OP: Levar o cursor até o link "Clique aqui"
    OP: Clicar com o botão esquerdo do mouse
  Goal 3: Baixar formulário desejado
    OP: Localizar a seção "_ Formulários para Reclamação"
    OP: Levar o cursor até o link "form-reclamacao_pn"
    OP: Clicar com o botão esquerdo do mouse
```

---

### Visualizar boletim de casos de Coronavirus de um dia específico
```
Goal 0: Visualizar boletim de casos de Coronavirus de um dia específico
  Goal 1: Acessar página do boletim do dia desejado
    METHOD 1.A: Acessar através do menu NOTÍCIAS
    (SEL.RULE: peferência do usuário)
      OP: Levar cursor até o menu "NOTÍCIAS"
      OP: Clicar com o botão esquerdo do mouse
      OP: Localizar notícia com boletim desejado na lista de notícias
      OP: Levar o cursor até a notícia com boletim desejado
      OP: Clicar com o botão esquerdo do mouse
    METHOD 1.B: Acessar através de pesquisa
    (SEL.RULE: peferência do usuário)
      OP: Levar o cursor até o campo de texto de "Pesquisa:"
      OP: Clicar com o botão esquerdo do mouse
      OP: Digitar "Boletim informativo {Dia/Mês}"
      OP: Apertar a tecla "Enter"
      OP: Levar o cursor até a notícia com boletim desejado
      OP: Clicar com o botão esquerdo do mouse
  Goal 2: Visualizar boletim
    OP: Levar o cursor do mouse até a imagem de "INFORME EPIDEMIOLÓGICO"
    OP: Clicar com botão esquerdo do mouse
```


## Versionamento

| Data  | Versão |                         Descrição                          |     Autor      |
| :---: | :----: | :--------------------------------------------------------: | :------------: |
| 01/10 |   V0   |                    Criação do documento                    | Bruna Almeida  |
| 02/10 |   V0   | Adição de conteúdo nas seções definição, legenda e análise | Amanda Bezerra |
