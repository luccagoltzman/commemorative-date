# Presente Especial - Dia da Mulher

Um projeto romântico para celebrar o Dia Internacional da Mulher com uma pessoa especial.

## Como usar

1. Faça o download ou clone este repositório
2. **IMPORTANTE:** Salve a sua foto de casal com o nome `foto-casal.jpeg` na pasta raiz do projeto
3. Personalize as mensagens no arquivo `index.html` se desejar
4. Abra o arquivo `index.html` em qualquer navegador moderno

## Sobre a foto

Para garantir a melhor visualização:

1. Salve a imagem que você enviou com o nome exato `foto-casal.jpeg`
2. Coloque essa imagem na mesma pasta onde estão os arquivos HTML, CSS e JS
3. A foto foi redimensionada para não ficar muito grande e permitir a visualização do texto

Se preferir usar outro nome para a foto ou outro formato de imagem, edite a linha 40 do arquivo `index.html`:

```html
<img id="special-photo" src="./foto-casal.jpeg" alt="Foto especial">
```

Substitua `./foto-casal.jpeg` pelo nome correto do seu arquivo.

## Ajustando o tamanho da foto

Se a foto ainda estiver muito grande ou pequena, você pode ajustar seu tamanho editando o arquivo `style.css`:

```css
.photo-frame {
    width: 80%;
    max-width: 350px; /* Diminua este valor se a foto ainda estiver muito grande */
}

.photo-frame img {
    width: 100%;
    max-height: 350px; /* Diminua este valor se a foto ainda estiver muito alta */
    object-fit: cover;
}
```

## Personalizando

### Para mudar a mensagem:
Edite o arquivo `index.html` e localize a seção:

```html
<div class="message">
    <h2>Feliz Dia da Mulher, Meu Amor!</h2>
    <p>Para a mulher mais incrível, forte e especial que eu poderia ter na minha vida. Você ilumina meus dias e faz meu coração sorrir. Te amo mais que tudo!</p>
    <p class="signature">Com todo meu amor ❤️</p>
</div>
```

Modifique o texto dentro das tags `<h2>` e `<p>` conforme desejar.

### Para mudar as cores:
Edite o arquivo `style.css` e procure pelas seguintes seções:

Para a cor de fundo:
```css
body {
    background: linear-gradient(135deg, #ffcce0, #ffd9e6);
}
```

Para a cor dos títulos e assinatura:
```css
h1, h2, .signature {
    color: #e85f99;
}
```

Para a cor do botão:
```css
button {
    background: linear-gradient(to right, #ff7eb3, #e85f99);
}
```

## Recursos

Este projeto usa:
- HTML5
- CSS3 com animações
- JavaScript puro
- Fontes do Google (Dancing Script e Montserrat)

## Créditos

Criado com ❤️ para demonstrar carinho no Dia da Mulher. 