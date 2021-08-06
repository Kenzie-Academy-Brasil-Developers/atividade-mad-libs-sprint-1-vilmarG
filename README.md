# Atividade: Mad-Libs! #

Vamos escrever um jogo [Mad-Lib](https://en.wikipedia.org/wiki/Mad_Libs) bem simples em JavaScript. Aqui está um exemplo de um Mad-Lib:

![mad_libs.jpg](https://i.snag.gy/G5iHbt.jpg)

O navegador inclui algumas funcionalidades que você pode usar para entrada e saída quando estiver começando. Você pode usar a função `prompt()` para criar uma caixa de diálogo pedindo para que o visitante da sua página digite alguma coisa. Você também pode usar `document.write()` para escrever algum texto na página.

Tente criar um novo documento HTML (lembra como usar os snippets Emmet para fazer isso rapidamente no VS Code?), e cole o seguinte código dentro da seção **body**:

```html
<h1>Mad-Libs</h1>
<script>  
	let animal = prompt("Name a kind of animal");
	let place = prompt("Name a place");
	let food = prompt("Name a food");
	document.write("Here is a story for you!<br>");  
	document.write("The inconsiderate " + animal + " strode proudly through " + place + ", dropping " + food + " everywhere.");  
</script>
```

Ao carregar essa página em seu navegador (clicando em Arquivo \> Abrir Arquivo, por exemplo), primeiro ela irá mostrar três caixas de diálogo pedindo que você digite um animal, um lugar e uma comida. Em seguida ela irá imprimir uma linha combinando esses termos. Observe como o _operador `+`_ é usado para _concatenar as strings_.

### Sua tarefa ###

Use esta abordagem para criar seu próprio jogo Mad-Lib. Aqui estão mais alguns exemplos bobos de textos que você pode usar quando estiver começando:

*   Fui a um(a) LUGAR e comi um(a) COMIDA horrível. Mas pude montar um(a) ANIMAL enorme!
*   Durante muitos anos, o(a) LUGAR era dominado unicamente por um(a) ANIMAL terrível. Tudo mudou no dia em que descobrimos o(a) COMIDA.
*   Você provavelmente não deveria se casar com aquele(a) ANIMAL. Você passará o resto da vida comendo COMIDA no meio do (a) LUGAR.
