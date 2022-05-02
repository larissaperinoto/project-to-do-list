# Projeto to do list

Projeto bônus realizado ao final do  Bloco 5 - JavaScript: DOM, Eventos e Web Storage, onde useu HTML, CSS e JavaScript.

### Objetivo

Criar uma interface de lista de tarefas onde o usuári possa interagir adicionando itens, selecionando e removendo. Deve ser possível salvar a lista de forma que, ao recarregar a página, os dados inseridos pelo usuário ainda estejam presentes.

### Requisitos 

#### 1 - Adicione à sua lista o título "Minha Lista de Tarefas" em uma tag <header>

Sua página deve possui uma tag `header` com o conteúdo `Minha Lista de Tarefas`.

#### 2 - Adicione abaixo do título um pequeno e discreto parágrafo com id="funcionamento" e com o texto "Clique duas vezes em um item para marcá-lo como completo"

Crie um elemento com o id `funcionamento` com o conteúdo `Clique duas vezes em um item para marcá-lo como completo`.

#### 3 - Adicione um input com o id="texto-tarefa" onde a pessoa usuária poderá digitar o nome do item que deseja adicionar à lista

Crie um elemento do tipo `input` com o id `texto-tarefa`.

#### 4 - Adicione uma lista ordenada de tarefas com o id="lista-tarefas"

Crie um elemento `ol` com o id `lista-tarefas`.

#### 5 - Adicione um botão com id="criar-tarefa" e, ao clicar nesse botão, um novo item deverá ser criado ao final da lista e o texto do input deve ser limpo

Crie um elemento do tipo `button` com o id `criar-tarefa` e após o clique, o texto digitado aparece na lista e desaparece do input. Todos os itens criados devem permanecer na lista na medida em que novos são adicionados.

#### 6 - Ordene os itens da lista de tarefas por ordem de criação

Os itens criados devem ser adicionado ao final da lista.

#### 7 - Clicar em um item da lista deve alterar a cor de fundo do item para cinza

Ao se carregar a página, os itens da lista não devem ter o estilo CSS `background-color: gray` e ao se clicar em um item da lista, ele passa a ter o estilo CSS `background-color: gray`.

#### 8 - Não deve ser possível selecionar mais de um elemento da lista ao mesmo tempo

Quando um elemento da lista é selecionado, o elemento selecionado previamente deixa de sê-lo. Isso é verificado através da presença ou não do estilo `background-color: gray` no elemento.

#### 9 - Clicar duas vezes em um item, faz com que ele seja riscado, indicando que foi completo. Deve ser possível desfazer essa ação clicando novamente duas vezes no item

Mediante duplo clique no elemento da lista deve ser adicionaro a classe `completed` e a propriedade `text-decoration` com o valor `line-through solid black` e com um segundo duplo clique, um elemento completo deixa de sê-lo.

#### 10 - Adicione um botão com id="apaga-tudo" que quando clicado deve apagar todos os itens da lista

Adicione um elemento `button` com o id `apaga-tudo` que um clique no botão a deixe a lista vazia.

#### 11 - Adicione um botão com id="remover-finalizados" que quando clicado remove **somente** os elementos finalizados da sua lista

 Adicione um elemento `button` com o id `remover-finalizados` que ao clicar no botão, todos os elementos marcados como feitos são removidos da lista.

#### 12 - Adicione um botão com id="salvar-tarefas" que salve o conteúdo da lista. Se você fechar e reabrir a página, a lista deve continuar no estado em que estava
  
Crie um elemento `button` com o id `salvar-tarefas`. Quando a lista tiver vários elementos, alguns dos quais marcados como finalizados, um recarregamento da página mantém a lista exatamente como está.

#### 13 - Adicione dois botões, um com id="mover-cima" e outro com id="mover-baixo", que permitam mover o item selecionado para cima ou para baixo na lista de tarefas

Adicione dois elementos `button`, um com o id `mover-cima` e o outro com o id `mover-baixo`, dado que diversos elementos foram acrescentados à lista, deve ser possível movimentá-los de formas diversas os deixa nas posições esperadas, caso algum elemento esteja finalizado, este status deve persistir ainda que se mova o elemento, caso nenhum elemento esteja selecionado, clicar nos botões não altera a lista. Um elemento que esteja selecionado deve se manter selecionado mesmo depois de movido. Caso se tente subir o elemento no topo da lista ou, caso se tente descer o último elemento da lista, esta não deve ser alterada.

#### 14 - Adicione um botão com id="remover-selecionado" que, quando clicado, remove o item selecionado

Adicione um elemento `button` com um id `remover-selecionado` que ao clicar no botão, somente o elemento selecionado é removido.

---
  
 ## Projeto Aprovado!
 
 ![Captura de tela de 2022-05-02 15-35-08](https://user-images.githubusercontent.com/98956659/166252861-bd4ccb2c-6d60-4916-84cb-385f887fac48.png)
  
  #### Crie sua [lista de tarefas](https://larissaperinoto.github.io/project-to-do-list/)!
  ![Captura de tela de 2022-05-02 15-11-50](https://user-images.githubusercontent.com/98956659/166252989-330f0d75-bd5a-4013-b766-2ea859250ff4.png)
  

