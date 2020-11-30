# Guia de estilo

## Definição

<p align = "justify">O guia de estilo é um registro das principais decisões de design tomadas, de forma que elas não se percam. Guias de estilo servem de ferramenta de comunicação entre os membros da equipe de design e também com a equipe de desenvolvimento. É importante que as decisões de design possam ser facilmente consultadas e reutilizadas nas discussões sobre extensões ou versões futuras do produto. (Barbosa e Silva, 2010)</p>
<p align = "justify">A imagem a seguir ilustra a fase da engenharia de usabilidade de Mayhew que estamos desenvolvendo.</p>

<figure>
<img align=center width="700" src="../../imagens/guia/analise_requisitos.png">
<figcaption>Fig. 1 - Diagrama feito no <a href= "https://app.diagrams.net/">draw.io</a>, baseando-se no diagrama de engenharia de usabilidade de Mayhew.</figcaption>

<br>
</figure>

<p align = "justify">Como demonstrado acima, a partir do perfil de usuário, a análise de tarefas, as características da plataforma e os princípios gerais do projeto, é possível definir as metas de usabilidade e, a partir daí, projetar o guia de estilo, que será apresentado seguidamente.</p>


## Participantes
- Bruna Almeida 
- Damarcones Porto



## 1 INTRODUÇÃO
<!--  -->
### 1.1 Objetivo do guia de estilo
<p align = "justify">O objetivo desse guia de estilo é documentar as características do site avaliado e registrar as principais escolhas de design tomadas pelos desenvolvedores. As informações descritas a seguir serão utilizadas, principalmente, no desenvolvimento de um protótipo. </p>

### 1.2 Organização e conteúdo do guia de estilo
<p align = "justify">Este Guia de Estilo está organizado no GitPages, afim de fornecer uma maior clareza sobre a consulta do layout e principais características do site.</p>

### 1.3 Público-alvo do guia de estilos
<p align = "justify">O público alvo desse guia são os próprios integrantes da equipe, que estão propondo uma reestruturação do site.</p>

### 1.4 Como utilizar o guia
<p align = "justify">O guia deve ser utilizado como base para as próximas atividades do projeto, especialmente na elaboração do protótipo de melhorias para o site.</p>

### 1.5 Como manter o guia
<p align = "justify">O guia deve ser atualizado a cada final de fase como indicado por Mayhew, assim torna-se possível sua evolução ao decorrer do desenvolvimento do projeto.</p>

## 2 RESULTADOS DE ANÁLISE
<!--  -->
### 2.1 Descrição do ambiente de trabalho do usuário
<p align = "justify">Ao acessar o site, o usuário se depara com a tela inicial contendo informações referentes a notícias da cidade de Águas Lindas. Em seguida, é apresentado um menu de funcionalidades disponíveis para o usuário, dentre as quais o usuário pode realizar a tarefa desejada. Esse menu encontra-se também no início da página, em formato de barra. Ao clicar em qualquer uma das opções do menu, o usuário será direcionado para a respectiva aba, e ao lado direito da tela, passam a ser exibidas notícias atualizadas sobre a cidade, sob o título de "Mais notícias".</p>

## 3 ELEMENTOS DE INTERFACE
<!--  -->
### 3.1 Disposição espacial e grid
<p align = "justify"> O grid está disposto de uma maneira que alguns elementos se confundem com notícias e ícones do menu. Existem ícones de menu fora da barra principal do menu, tornando a  navegação exaustiva. Um espaço do grid que poderia estar preenchida somente com uma cor de fundo, possui um botão com o nome "+vídeos", porém o mesmo leva novamente a tela inicial, causando assim, uma desorientação no usuário. Segue abaixo o grid que foi citado anteriormente: </p>

<figure>
<img align=center width="600" src="../../imagens/guia/grid1.png">
<br>
<figcaption>Fig. 2 - Ideia da homepage.</figcaption>
</figure>
<br>

<p align = "justify">Agora são apresentadas algumas imagens da tela inicial do site:</p>

<figure>
<img align=center width="600" src="../../imagens/guia/home.png">
<br>
<figcaption>Fig. 3 - Print da homepage.</figcaption>
</figure>

<br>

<figure>
<img align=center width="600" src="../../imagens/guia/materias.png">
<br>
<figcaption>Fig. 4 - Print das notícias na homepage.</figcaption>
</figure>

<br>

<figure>
<img align=center width="600" src="../../imagens/guia/menualternativo.png">
<br>
<figcaption>Fig. 5 - Print dos menus alternativos na homepage.</figcaption>
</figure>
<br>

### 3.2 Janelas
<p align = "justify"> O site possui inúmeras janelas. Existem janelas para visualizar notícias, para saber mais sobre a história da cidade, acessar contatos, entre outras janelas. A seguir, encontra-se alguns exemplos de janelas do site.</p>

<figure>
<img align=center width="600" src="../../imagens/guia/janela.png">
<br>
<figcaption>Fig. 6 - Exemplo de janela presente no site.</figcaption>
</figure>

<figure>
<img align=center width="600" src="../../imagens/guia/prefeito.png">
<br>
<figcaption>Fig. 7 - Página que mostra dados do atual prefeito.</figcaption>
</figure>

<figure>
<img align=center width="600" src="../../imagens/guia/informacao.png">
<br>
<figcaption>Fig. 8 - Página de informações..</figcaption>
</figure>

<figure>
<img align=center width="600" src="../../imagens/guia/contatos.png">
<br>
<figcaption>Fig. 9 - Página dos contatos das secretarias.</figcaption>
</figure>

<figure>
<img align=center width="600" src="../../imagens/guia/noticias.png">
<br>
<figcaption>Fig. 10 - Página página de notícias da cidade.</figcaption>
</figure>

<p align = "justify">Para padronizar o modelo de janelas apresentado no site, foi desenvolvido o seguinte grid:</p>

<figure>
<img align=center width="600" src="../../imagens/guia/grid2.png">
<br>
<figcaption>Fig. 11 - Ideia geral sobre as janelas do site.</figcaption>
</figure>



### 3.3 Tipografia
<p align = "justify">Em relação à tipografia, o site utiliza as seguintes fontes:</p>

<figure>
<img align=left width="600" src="../../imagens/guia/tipografia.png">
<figcaption>Fig. 12 - Tipos de fontes utilizadas no site.</figcaption>
</figure>

### 3.4 Símbolos não tipográficos

<p align = "justify">O site apresenta os seguintes símbolos:</p>

<figure>
<img align=left width="700" src="../../imagens/guia/icones.png">
<figcaption>Fig. 13 - Ícones utilizados no site.</figcaption>
</figure>

<p align = "justify">Esses símbolos representam, respectivamente, os seguintes itens do menu:</p>
<p>- Telefones úteis;</p>
<p>- Portal do aluno;</p>
<p>- Portal saúde - escala médica;</p>
<p>- Agendamento teste - COVID19;</p>
<p>- Portal da transparência;</p>
<p>- Relatórios fiscais;</p>
<p>- Serviços online;</p>
<p>- Licitações.</p>

<p align = "justify">Os ícones de telefones úteis, portal do aluno e portal da saúde são intuitivos. Já os símbolos para agendamento de teste para COVID19, portal, relatórios fiscais, serviços online e licitações podem deixar o usuário confuso, pois não explicitam exatamente o que significam. O usuário não deduz automaticamente o que pode significar esses símbolos.</p>


### 3.5 Cores
<p align = "justify">A logo pode ser encontrada de duas formas: com o nome do site por extenso ou apenas sua logo. Aqui está a palheta de cores de ambas as logos:</p>

<figure>
<img align=left width="700" src="../../imagens/guia/paleta_1.png">
<figcaption>Fig. 114 - Paleta de cores da logo.</figcaption>
</figure>

<p align = "justify">No percorrer do site as seguintes cores podem ser encontradas:</p>

<figure>
<img align=left width="700" src="../../imagens/guia/paleta_2.png">
<figcaption>Fig. 15 - Paleta de cores encontrada no site.</figcaption>
</figure>


### 3.6 Animações
<p align = "justify">Os links para serviços diversos no final da página possuem uma animação, somente após a página ser atualizada, que é ativada assim que a página é rolada para baixo na parte onde estão localizados, o mesmo efeito não é encontrado quando se acessa o site pelo browser do smartphone. </p>


## 4 ELEMENTOS DE INTERAÇÃO
<!--  -->
### 4.1 Estilos de interação
<p align = "justify">Os estilos de interação mais utilizados no site são: os de menus, que possibilitam a navegação do usuário pelo site e linguagem natural que indicam onde e o que o usuário pode fazer; WIMP (window, icon, menu, pointing device) que é a utilização de ícones, menus e ações com o mouse; e formulários para aumentar o nível de comunicação com sistema.</p>

### 4.2 Seleção de um estilo
<p align = "justify"> Como citado anteriormente, o estilo de utilização de menus é o predominante no site. Dessa forma o usuário seleciona o menu e tenta realizar a função contida no menu. </p>

### 4.3 Aceleradores  (Teclas de atalho)
<p align = "justify">Não foi encontrado nenhum mecanismo facilitador no uso do site.</p>


## 5 ELEMENTOS DE AÇÃO
<!--  -->
### 5.1 Preenchimento de campos
<p align = "justify">Para solicitar o recebimento de informações por e-mail, o usuário deve preencher as seguintes informações a seguir, sem isso fica impossibilitado de realizar a ação.</p>

<figure>
<img align=center width="300" src="../../imagens/guia/receber_informacoes.png">
<br>
<figcaption>Fig. 16 - Formulário para recebimento de informações por e-mail.</figcaption>
</figure>

### 5.2 Seleção
<p align = "justify">Não existe opção de seleção no procedimento anterior.</p>

### 5.3 Ativação
<p align = "justify">Apos todos os campos preenchidos corretamente, basta o usuário clicar no botão "enviar".</p>


## 6 VOCABULÁRIO E PADRÕES
<!--  -->
### 6.1 Terminologia
<p align = "justify">A linguagem utilizada no site é bem simples e de fácil entendimento, exceto termos ligados ao poder administrativo, esses não são passíveis de alterações por se tratarem de palavras específicas da administração pública.</p>

### 6.2 Tipos de tela
<p align = "justify">O site possui uma tela padrão para todas as suas páginas, fora aqueles serviços que são realizados obrigatoriamente fora dele, dando assim, uma sensação de conforto para o usuário por não se deparar com ambientes totalmente desconhecidos.</p>

### 6.3 Sequências de diálogos
<p align = "justify">Uma mensagem (Sua mensagem foi enviada.) é exibida pelo sistema logo apos o usuário preencher os campos "RECEBA INFORMAÇÕES" e clicar em enviar, isso indica que a operação ocorreu de maneira correta. Nos casos que necessitam algum tipo de confirmação, o sistema informa o usuário com algum aviso na tela do site.</p>

## Referências

<div><p align = "justify">
- Livro: BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. 1ª edição, Rio de Janeiro: Elsevier, 2010.
</p>
</div>
<div><p align = "justify">
- Todas as imagens apresentadas nessa página foram criadas utilizando o <a href= "https://www.canva.com/pt_br/">Canvas</a>.
</p>
</div>
<div><p align = "justify">
- Todos os diagramas apresentados nessa seção, foram criados no <a href= "https://app.diagrams.net/">draw.io</a>.
</p>
</div>

<div><p align = "justify">
- Todos os prints apresentados nessa seção, foram retirados do site da <a href= "https://aguaslindasdegoias.go.gov.br/">Prefeitura de Águas Lindas de Goiás</a> nos dias 13 e 28 de Outubro de 2020.
</p>
</div>

## Versionamento
| Data | Versão |           Descrição             |    Autor    |
|:----:|:------:|:-------------------------------:|:-----------:|
|08/10 |V0      |     Criação do documento        |Bruna Almeida|
|13/10 |V1      |Adiciona strutura para o texto   |Damarcones Porto|
|13/10 |V2      |Adiciona Definição               |Bruna Almeida|
|13/10 |V3      |Adiciona Resultados              |Bruna e Damarcones|
|28/10 |V4      |Adiciona prints do site          |Bruna, Damarcones|
|30/11 |V5      |Corrigi documento                |Bruna, Damarcones|