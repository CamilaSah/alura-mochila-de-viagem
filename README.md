![Front-end-JavaScript na Web](https://github.com/CamilaSah/alura-mochila-de-viagem/assets/128820692/9ff9936a-b972-4b94-9796-1a868649e7ef)
![Static Badge](https://img.shields.io/badge/Status-Conclu%C3%ADdo-%2391DCFF)


<h1> Mochila de Viagem </h1>
O projeto Mochila de Viagem é um site que serve de lista de itens e tem um visual com formulário simples, no qual o usuário insere o nome e a quantidade do item desejado e clica no botão “adicionar”. O usuário pode editar essa lista, atualizando a quantidade, deletando um item e mesmo que essa página seja recarregada, os dados continuarão fixos.
O HTML e CSS desse projeto já estão prontos e esse site inteiro será criado a partir do zero com o JavaScript.
<br>
PS.: A mochila foi desenhada com CSS e é um projeto da Tricia Katz (https://codepen.io/triciaakatz).

## :hammer: Funcionalidades do projeto
- `Adicionar item na lista`: o usuário pode adicionar um item na lista ao inserir o nome e quantidade desejada e clicar no botão "adicionar".
- `Atualizar item na lista`: o usuário pode atualizar um item na lista ao inserir o nome e nova quantidade desejada e clicar no botão "adicionar".
- `Remover item da lista`: O usuário pode remover o item da lista ao clicar no botão "x".

![apresentacao-alura-mochila-viagem840-min](https://github.com/CamilaSah/alura-mochila-de-viagem/assets/128820692/57a028ee-8665-42a8-9543-84b54f9180ac)


## 📁 Acesso ao projeto

Você pode acessar o projeto clicando [aqui](https://alura-mochila-de-viagem-zeta.vercel.app/).

## ✔️ Técnicas e tecnologias utilizadas

Técnicas utilizadas:
- ``Função getElementById()``: faz uma busca do elemento pelo ID.
- ``Função addEventListener()``: evento de interação que recebe dados passados pela pessoa usuária, neste caso, quando ela aperta o botão de adicionar item e para remover o item da lista.
- ``Evento submit``: é acionado quando um <form> é enviado.
- ``Evento click``: é acionado quando é clicado no item.
- ``Método preventDefault()``: cancela o evento se for cancelável, sem parar a propagação do mesmo. 
- ``Método document.createElement()``: cria o elemento HTML especificado por tagName, no caso, cria novos itens da lista.
- ``Método forEach()``: foi aplicado para manter os itens criados na página, mesmo após atualizá-la.
- ``Método findIndex()``: foi utilizado para retornar o índice no array do primeiro elemento que satisfizer a função de teste provida.
- ``Método push()``: insere um elemento no array. Neste caso, cada item novo adicionado pelo usuário entra no array.
- ``Método splice()``: foi utilizado para remover determinado elemento da mochila.
- ``Método remove()``: foi utilizado para remover o item do DOM.
- ``element.classList.add("anotherclass")``: usado para adicionar uma classe na lista.
- ``element.innerHTML``: esta propriedade obtém ou altera qualquer elemento no HTML. Neste caso, nome e quantidade do item da lista.
- ``element.innerText``: esta propriedade permite inserir textos no HTML. Neste caso, o “x” do botão remover.
- ``document.appendChild()``: adiciona um elemento HTML.
- ``Array de objetos``: neste caso é a variável “itens”, que armazena os objetos da mochila em um array.
- ``LocalStorage``: armazena dados do tipo texto string de forma persistente dentro do navegador do usuário, apenas aqueles considerados não sensíveis. Aprendemos a criar, a pegar e a remover os itens, além de limpar o Local Storage.
- ``SessionStorage``: não salva de forma persistente, armazenando dados apenas enquanto o site estiver aberto.
- ``Cookies``: possuem menor espaço de armazenamento 4KB e salvam dados considerados sensíveis de forma persistente.
- ``localStorage.setItem``: cria um elemento no Local Storage.
- ``localStorage.getItem``: acessa um elemento no Local Storage.
- ``Método JSON.stringify()``: transforma objetos, arrays e listas em string.
- ``Método JSON.parse()``: como alterar valores de tipo texto para valores JavaScript.
- ``Operador "ou"``: como utilizar o operador lógico “ou” || para retornar um tipo de dado desejado.
- ``Operador ternário``: (?) - se positivo, faça a primeira condição e (:) - se negativo, faça a outra.

Tecnologias e ferramentas utilizadas:
- ``Visual Studio Code``: editor de código.
- ``Firefox e Edge``: navegadores utilizados para teste.
- ``HTML``: fazer a estrutura semântica da página.
- ``CSS``: fazer os estilos da página.
- ``JavaScript``: adicionar o dinamismo e as atualizações de programação, a lógica na página.
- ``DevTools``: utilizamos a aba “Console”, no qual podemos executar qualquer código JavaScript, além de nos ajudar a desenvolver, a entender o nosso código e ver como os erros são apresentados. Além disso, foram acessados os dados salvos no navegador no Local Storage.
- ``Git``: ferramenta de controle de versão de seu arquivo, projeto ou código. 
- ``GitHub``: plataforma para gerenciar seu código e criar um ambiente de colaboração entre devs (permite compartilhamento de código através da criação de repositórios), utilizando o Git como sistema de controle.
- ``Vercel``: colocar o projeto no ar e compartilhar com o mundo.

## 📚 Mais informações do curso
Gostou do projeto e quer conhecer mais? Você pode acessar o curso que me ajudou a desenvolver o projeto desde o começo! 
Busque na plataforma da Alura o curso da escola Front-end:
- [JavaScript na Web: armazenando dados no navegador](https://cursos.alura.com.br/course/javascript-web-armazenando-dados-navegador).

Esse curso faz parte da formação [Desenvolva aplicações Web com JavaScript](https://cursos.alura.com.br/formacao-javascript-front-end) da Alura

# Autores

| <img src="https://github.com/CamilaSah/site-pessoal/assets/128820692/bed790ab-3722-4503-8fed-c786e774661b" width="100"><br>[<sub>Camila Sayuri Tokubo</sub>](https://www.linkedin.com/in/camila-tokubo/)|
| :---: |
