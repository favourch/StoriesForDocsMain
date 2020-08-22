# Like Stories
> Slide como o Stories do Instagram. 

## Overview
Projeto desenvolvido com Vanilla JavaScript, HTML5 e CSS3.

Agradecimentos especiais à [Origamid](https://www.origamid.com/) que inspirou e auxiliou o desenvolvimento desse repositório com seu [vídeo do YouTube](https://www.youtube.com/watch?v=VaSr6uixmb0).

## Setup
Faça o download do repositório ou dos arquivos específicos. Após isso, adicione os arquivos `css/styles-slide.css` e `js/script-slide.js` no seu arquivo HTML. E construa uma estrutura para o slide semelhante a esta:
```html
  <div data-slide="slide" class="slide">
    
    <div class="slide-items">
      <img src="./img/giraffe1.jpg" alt="Girafa do Slide 1">
    </div>

    <nav class="slide-nav">
      <div class="slide-thumb"></div>
      <button class="slide-prev"></button>
      <button class="slide-next"></button>
    </nav>

  </div>
```

Para mais detalhes veja o arquivo `index.html`.

## Deploy
O deploy do projeto está sendo feito com o *github-pages* e está disponível [aqui](https://lucasbecker.github.io/like-stories/).
## License
[MIT License](./LICENSE) © [Lucas Becker](http://lucasbecker.github.io/)