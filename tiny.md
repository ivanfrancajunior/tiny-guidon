# Manual de Como Utilizar o Tiny

## **1. Introdução**

- **Objetivo da Apresentação** é de explicar como utilizar o Tiny de forma eficiente no fluxo de trabalho da empresa.

A idéia é mostrar o uso básico do Tiny pros novos usuários e pros antigos que tenham experiencia ou não com o sistema.

Na Guidon usamos o Tiny como forma de manter o controle de estoque, entrada e saida de material, geração e NF entre outras mas no nosso caso o uso do sistema é voltado **pra tentar manter da forma mais fiel possivel os produtos fisicos e a tabela-mãe**.


### Inteterface do Tiny: - Telas iniciais

Pra acessar o sistema deve-se ter usuário e senha. Eu Ivan já tenho vc deve solicitar seu acesso ou ao Alexandre ou ao TP

![tela inicial](<assets/bloco_1/tela inicial.PNG>)


<br>

### Interface de Produtos no tiny:

No menu lateral vamos procurar a opção de cadastros -> Produtos

![alt text](assets/bloco_1/menu-cadastrp-produtos.PNG)

<br>

Uma vez Acessando o menu cairemos na tela de produtos. Essa tela reflete todos os produtos que estão armazenados podendo ou não ter um anúncio no Mercado Livre

![alt text](assets/bloco_1/tiny-tela-de-produtos-no-sistema.PNG)



### Buscanco produtos:

Você consegue fazer buscas no sitema por produtos utilizando formas diferentes de pesquisa as que mais são usadas são: Título(Descrição) e SKU.

#### Buscando por título:

Digite o título do produto com o filtro **palavra-chave** selecionado:

![alt text](assets/bloco_1/tiny-busca-por-palavra-chave.PNG)


#### Buscando por sku:

Digite o título do produto com o filtro **código** ou **código(parcial)** selecionado:

![alt text](assets/bloco_1/tiny-busca-por-código.PNG)


**Uma observação é que em caso de busca por código o sku completo deve ser inserido do contrário, a busca não retornará nada**


-(guia) Padronizar os processos para garantir maior produtividade e organização.

### Já sei abrir o sistema, já sei pesquisar por produtos como q eu cadastro o produto?


O processo para cadastrar um produto é feito de duas forma:


**Inserção de produtos manualmente no sistema** e **Importação de produtos junto a plataforma do ML**


Devido a praticidade estamos fazendo isso pela segunda opção: Pegamos os  anúncios do mercado livre e trazemos ele pro sistema criando um produto com base nas características do anúncio.

### Passo a Paso

#### 1º Importando novos produtos

No canto superior clicamos no botão **receber do ecommerce**:

![alt text](assets/bloco_1/tiny-receber-produto-do-ecommerce.PNG)


<hr>

#### 2º Selecionando os produtos a serem importados

Uma vez clicado no botão vamos ter 3 opções para importação:

- todos os anúncios da minha conta
- somente os anúncios novos
- um anúncio específico

Temos usado o somente anúncios novos devido a demora da importação.

![alt text](assets/bloco_1/tiny-selecionando-produtos-novos.PNG)

#### 3º Importando os produtos

Feito o passo anterior basta esperar a importação:

![alt text](assets/bloco_1/tiny-importando-produtos-novos-do-ml.PNG)

<hr>


#### 4ª Relacionando transformando anúncios em produtos:

Os anúncios foram importado agora temos que transformar esses anúncios em produtos, para isso clique no botão **relacionar esses anuncios aos seus produtos**

![alt text](assets/bloco_1/tiny-relacionando-anuncios-com-produtos.PNG)


Em seguida temos que estabelecer um critério para essa relação e a diretriz é relacionar com o **SKU**.

Como segunda seleção optamos por atualizar informações do produto caso ele já exista, então marca-se **sim** e como opções sequentes **Apenas dados não preenchidos**, **Atualizar o estoque** e **Atualizar imagens e seguimos com o relacionamento.
 **:

![alt text](assets/bloco_1/tiny-opções-de-importação.PNG)


#### 5ª Criando novos produtos:

Ao fim do processo caimos finalmente na criação de novos produtos:

- Seguimos com **Criar produtos novos com base nos anúncios**

![alt text](assets/bloco_1/tiny-tela-de-criação-por-importação.PNG)


Na sequencia, basta criar os produtos com base nos anúncios.

![alt text](assets/bloco_1/tiny-criação.PNG)

<br>

Ao final do processo novos produtos serão criados.

![alt text](assets/bloco_1/tiny-criação-sucesso.PNG)

---


## ah mas e agora?!

![alt text](assets/john-travolta.gif)

<br>

<hr>

# VAMOS CRIAR PRODUTOS A PARTIR DE OUTROS PRODUTOS DO SISTEMA

Primeiro para economizar tempo buscamos no própio sistema por um modelo parecido no exemplo vamos utilizar rodas Gaúchas

![alt text](<assets/bloco_2/tiny-clonando item do sistema.png>)


Na sequencia no menu de opções, clonamos o item:

![alt text](assets/bloco_2/clonando-01.png)


Escolhemos a opção de clonar:

![alt text](assets/bloco_2/clonando-02.png)

Na sequência, as opções já vem marcadas basta continuar

![alt text](assets/bloco_2/clonando-03.png)


Na tela seguinte alguns campos devem ser editados:

**Na aba dados gerais**:

- Descrição
- Tipo
- Preço de venda
- Unidade: UN para unidade e JG para jogo
- Peso Líquido

![alt text](assets/bloco_2/clonando-4.png)

Na aba **Dados Complementares**

Edite a Descrição complementar e Categoria

![alt text](assets/bloco_2/clonando-05.png)

Na aba **Anúncios** se tiver, adicione o id do anúncio no Mercado Livre

![alt text](assets/bloco_2/clonando-06.png)

<br>
<br>

Com o produto criado e pro caso de ser unidade, depois temos que acrescer a quantidade de rodas isso fazemos em gerenciar estoque também no menu a esquerda do produto criado:

![alt text](assets/bloco_2/clonando-07.png)


Antes de adicionar se certifique que o estoque seja o pronto pra vendas, com isso verificado vamos um lançamento no botão azul no canto superior direito:

![alt text](assets/bloco_2/clonando-08.png)

A partir disso, vamos preencher mais alguns campos:

- Tipo: Entrada
- Quantidade
- Preço unitário: Este é o preço de custo da roda
- Observação: Justifique sempre o lançamento, no nosso caso será Ajuste de estoque imaginando q esse produto estava na tabela mãe mas ainda não estava cadastrado no sistema.

![alt text](assets/bloco_2/clonando-10.png)
