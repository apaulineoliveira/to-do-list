# to-do-list
<h1>🤖 Objetivo</h1>

<p> O objetivo deste projeto foi criar um to-do-list com html, css, um pouco de bootstrap, e js. A ideia é que houvesse a possibilidade de criar as notas e também botão para exclui-las. </p>
<h3>Pontos relevantes </h3>
<li>Na estrutura html foram utilizados botões e inputs que posteriormente foram chamados no código js para criar as interações de captura de notas e adição das mesmas no container.</li><br>

<li>Na folha de estilo (css) o layout foi estruturado de forma responsiva com o uso de medidas em porcentagens, vh e o uso de max e min width. Além disso, foram utilizado css animation, e criando tags exclusivas que não são uma referência a uma classe ou id do html mas que serão posteriormente utilizadas no js ao estilizar as notas com <code>querySelector</code>. </li> <br>

<li>Em javascript com a utilização do DOM (document object model) foi possível fazer intersecção web com a utilização de funções como a <code>document.getElementById</code> e <code>document.querySelector</code>. Um laço de repetição percorrendo o array e seus valores foi criado para determinar o comportamento do código a partir do momento em que não for identificada nenhuma nota no input. Se nenhuma nota for inserida um <code>alert</code> aparecerá na tela indicando ao usuário a inserir algo no input. A segunda parte da condição (else) indica como a função irá se comportar caso uma nota tenha sido inserida. Neste caso, será inserida na div <code>tasks</code> a div <code>task</code> e adicionado a ela o valor recebido do input, como pode ser visualizado no seguinte código:</li><br>
<code>${document.querySelector('#taskInput').value}</code>
