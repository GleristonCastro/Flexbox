# Aula prática do Canal do Youtube "Node Studio Treinamentos"

Após o bootcamp Impulso FullStak da DIO, passei a procurar atividades diversas e de acordo com o conteúdo ministrado. Portanto, através do canal do Youtube NodeStudio assisti e passei a replicar o código e aprimorando o HTML/CSS com meus conhecimentos.

> [Ver resultado do projeto](https://gleristoncastro.github.io/Flexbox/Pratica2/)

### Inspiração

- [Curso de Flexbox - Node Studio](https://www.youtube.com/playlist?list=PLwXQLZ3FdTVGjLmjwfRc0Q9TA5U-PCWp4)

Diferentemente do tutorial coloquei o modo de importação dos css externos diretamente no css pelo **@import**. O objetivo era deixar o HTML mais limpo possível.

### Apliquei algumas melhorias no código.

no css adicionei além do:
```css
{
background-clip: content-box;
}
```
o
```css
{
background-clip: content-box;
-webkit-background-clip: content-box;
}
```
> pelo o que entendi da documentação, não é compatível com o safari < 14

### Html adicionei o tipo do button!


Antes:
```html
<button>Cadastrar</button>
```
Depois:
```html
<button type="button">Cadastrar</button>
```
> Motivo: Compatibilidade de navegadores

### No Grid deixei assim

##### HTML
```html
<ul class="grid">
    <li class="small itacare01"></li>
    <li class="large itacare02"></li>
    <li class="large itacare03"></li>
    <li class="small itacare04"></li>
</ul>
```

##### CSS
```css
.itacare01{
    background-image: url(./img/itacare-01.jpg);
}

.itacare02{
    background-image: url(./img/itacare-02.jpg);
}

.itacare03{
    background-image: url(./img/itacare-03.jpg);
}

.itacare04{
    background-image: url(./img/itacace-04.jpg);
}
```

### Agradecimentos/Créditos:

- [Canal Node Studio](https://www.youtube.com/c/NodeStudioTreinamentos)
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)

### Dificuldades

Não apresentei dificuldades importante, didática muito boa e já com algum conhecimento, consegui desempenhar rapidamente a atividade proposta.

Apesar do material (imagens) serem disponibilizados, faltou os textos no qual conseguir digitar pausando os vídeos e replica-los.