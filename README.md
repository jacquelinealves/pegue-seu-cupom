Este projeto foi desenvolvido com as seguintes tecnologias:

[BEM](http://getbem.com/introduction/)

[Sass](http://sass-lang.com/)

[Atomic CSS](https://acss.io/)

[Bootstrap](https://getbootstrap.com/)

___________________________________________

### Atomic

Os arquivos CSS seguirão uma hierarquia baseado no __Atomic CSS__:

```

01_component/
├  background.scss
├  button.scss
├  font.scss
├  images.scss
├  size.scss
└  text.scss

02_molecule/
├  card.scss
├  carousel.scss
├  footer.scss
├  header.scss
└  nav.scss

04_pagse/
├  index.scss
└  pages.scss

style.scss
```

Para rodar o projeto basta cloná-lo, com o terminal ir até a pasta raíz e rodar:
```
npm install
```

em outra aba ir até o diretorio app/stylus e rodar o seguinte comando:
```
  sass --watch style.scss:../../build/css/style.css
```
Aqui o arquivo style.scss irá gerar um style.css em __build/css__.

Para editar o projeto é necessário instalá-los.

___________________________________________

Caso não tenha nada instalado na sua máquina e queira editar o projeto:

### Sass
Rodar esse comando Global:
`$ sudo gem install sass`
