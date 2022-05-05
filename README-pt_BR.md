# FrontMentor - solução de componente de grid de preço único

Esta é uma solução para o [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Os desafios do FrontMentor me ajudam a melhorar suas habilidades de codificação, construindo projetos realistas.

## 🔍 Visão geral

### 🎯 O desafio

Os usuários devem poder:

- [x] Veja o layout ideal para o componente, dependendo do tamanho da tela do dispositivo
- [x] Veja um estado pairar na área de trabalho para a inscrição de inscrição

### 🤳 Captura de tela

![](./screenshot.jpg)

### 🔗 Links

- **STATUS/ON** Ao vivo Site URL: [Veja o Projeto na Vercel](https://nft-card-component-npz4l9cut-henriquessan.vercel.app/)

## 🚩 Meu Processo

### 🛠️ Construido Com

- Semantic HTML5 markup.
- CSS custom properties.
- SCSS(SASS) custom properties.
- CSS Methodology BEM.
- Flexbox.

### 📚 O que eu aprendi

Aprendi a usar o CSS Grid, Com metodologia BEM(BOUNDARY ELEMENT METHOD) que traz a ideia de armazenar tudo como caixa para uma melhor vizualização de caixa e trazendo mais significado para as classes do HTML

```html
<div class="root">
  <div class="button">
    <button class="buttons"></button>
  </div>
  <div class="button">
    <button class="buttons"></button>
  </div>
  <div class="button">
    <button class="buttons"></button>
  </div>
  <div class="button">
    <button class="buttons"></button>
  </div>
</div>
```

```css
.root{
  /*Declarações*/
  
}
.button{
  /*Declarações*/

}
.buttons{
  /*Declarações*/
}
```

**VS**.

```html
<div class="button">
  <div class="button__container">
    <button class="buttons"></button>
  </div>
  <div class="button__container">
    <button class="buttons"></button>
  </div>
  <div class="button__container">
    <button class="buttons"></button>
  </div>
  <div class="button__container">
    <button class="buttons"></button>
  </div>
</div>
```

```css
.button{
  /*Declarações*/
}
.button__container{
  /*Declarações*/

}
.buttons{
  /*Declarações*/
}
```

A Organização do Pojeto foi:

- Primeiro a estrutura HTML5 com boas práticas
- Criação de classes de forma mais clara
- Criação do layout em CSS
- Adicionando responsividade
- Animações em CSS

### ⚔️ Desenvolvimento contínuo

Pretendo Melhorar meu CSS e HTML e desenvolver projetos em JavaScript, CSS reduzir a utilização de classes desnecesarias e HTML desenvolver estruturas mais eficientes e melhores,Pretendo  criar projetos com JavaScript e continuar a fazer exercícios

### 📦 Recursos úteis

- [Video de como usar o SASS BR](https://www.youtube.com/watch?v=C8KlabGtE8Y) - Aprendi com esse video como usar o basico do pré-processador Sass(Scss) em projetos
- [CSS Methodology BEM](https://www.youtube.com/watch?v=27JtRAI3QO8) - Aprendi Uma melhor forma de criar classes com esta metodologia para tornar o codigo mais legível e limpo possível
- [CSS Artigo de Metodologia BEM](https://css-tricks.com/bem-101/) - Artigo sobre a metodologia BEM foi um complementar

## ✍️ Autor

- Linkedin - [Henrique Santos Santana](https://www.linkedin.com/in/henrique-santos-santana/)
- Frontend Mentor - [@HenriqueSSan](https://www.frontendmentor.io/profile/HenriqueSSan)
- Vercel - [HenriqueSSan](https://vercel.com/henriquessan)

## 🤝 Agradecimentos

Agradeço aqueles que estão vendo esse projeto e meu desenvolvimento tenham um bom dia.
