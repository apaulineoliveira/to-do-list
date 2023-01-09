# to-do-list
<h1>🤖 Objetivo</h1>

<p> O objetivo deste projeto foi criar um to-do-list com html, css, um pouco de bootstrap, e js. A ideia é que houvesse a possibilidade de criar as notas e também botão para exclui-las. </p>
<h3>Pontos relevantes </h3>
<li>Na estrutura html foram utilizados botões e inputs que posteriormente foram chamados no código js para criar as interações de captura de notas e adição das mesmas no container.</li><br>

<li>Na folha de estilo (css) o layout foi estruturado de forma responsiva com o uso de medidas em porcentagens, vh e o uso de max e min width. Além disso, foram utilizado css animation, e criando tags exclusivas que não são uma referência a uma classe ou id do html mas que serão posteriormente utilizadas no js ao estilizar as notas com <code>querySelector</code>. </li> <br>

<li>Em javascript com a utilização do DOM (document object model) foi possível fazer intersecção web com a utilização de funções como a <code>document.getElementById</code> e <code>document.querySelector</code>. Um laço de repetição percorrendo o array e seus valores foi criado para determinar o comportamento do código a partir do momento em que não for identificada nenhuma nota no input. Se nenhuma nota for inserida um <code>alert</code> aparecerá na tela indicando ao usuário a inserir algo no input. A segunda parte da condição (else) indica como a função irá se comportar caso uma nota tenha sido inserida. Neste caso, será inserida na div <code>tasks</code> a div <code>task</code> e adicionado a ela o valor recebido do input, como pode ser visualizado no seguinte código:</li><br>
<code>${document.querySelector('#taskInput').value}</code> 
<li>No mesmo bloco de código da função condicional citada acima encontra-se o um <code>button</code> que permite deletar a nota. Na construção desse botão foi utilizado o bootstrap.</li> <br>
<li>O bloco de código para determinar as funcionalidades da exclusão do botão foi fundamentado, a priori, com <code>document.querySelectorAll</code>, logo após a implementação de um loop e em seguida, utilizei a propriedade <code>parentNode</code> que é uma propriedade somente leitura retorna o nome do nó pai selecionado como um objeto de nó.</li>
<br></br>
<br></br>


<h1>🤖 Goal</h1>

<p> The goal of this project was to create a to-do list with html, css, a little bootstrap, and js. The idea is that there was the possibility to create notes and also a button to delete them. </p>
<h3>Relevant points </h3>
<li>In the html structure, buttons and inputs were used that were later called in the js code to create the abilities to capture notes and add them to the container.</li><br>

<li>In the style sheet (css) the layout has been protected responsively using percentage measurements, vh and the use of max and min width. In addition, css animation was used, and creating unique tags that are not a reference to a class or html id but that will be later used in the js when styling the notes with <code>querySelector</code>. </li> <br>

<li>In javascript using the DOM (document object model) it was possible to intersect the web using functions such as <code>document.getElementById</code> and <code>document.querySelector</code>. A repetition loop traversing the array and its values was created to determine the behavior of the code from the moment no note or entry is identified. If no note is entered, an <code>alert</code> will appear on the screen telling the user to insert something in the input. The second part of the condition (else) indicates how the function will behave if a grade has been entered. In this case, the div <code>task</code> will be inserted in the div <code>tasks</code> and the value received from the input will be added to it, as can be seen in the following code:</li><br>
<code>${document.querySelector('#taskInput').value}</code>
<li>In the same code block of the conditional function mentioned above, there is a <code>button</code> that allows deleting a note. Bootstrap was used to build this button.</li> <br>
<li>The block of code to determine the functions of deleting the button was based, a priori, with <code>document.querySelectorAll</code>, right after implementing a loop and then using the <code> property parentNode</code> which is a read-only property returns the name of the selected parent node as a node object.</li>
