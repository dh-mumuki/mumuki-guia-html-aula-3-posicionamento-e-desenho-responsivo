Imagine agora que temos uma seção em nossa página com vários artigos com caixas:

```html
<article>
  <div class = "yellow"> </ div>
  <div class = "red"> </ div>
</ article>
```
O primeiro `<div>` tem um fundo amarelo e mede 20 px por 20 px. O segundo `<div>` tem um fundo vermelho e mede 100px por 100px.

Nós vamos fazê-los se sobrepor e ver o que acontece com a nossa nova propriedade `z-index`

Para isto:

> 1. Dê aos dois div a propriedade `position: relative`. Sem esclarecer posição, não podemos usar z-index
> 2. Vamos mover o `<div class =" yellow ">` 10px acima.
> 3. Adicione o z-index a `<div class ="red">` e altere seu valor para ver o que acontece!