# Aula 48

Este desenvolvimento web possui os seguintes objetivos principais:

- Implementar os Bookmarks;

## Bookmarks

Os Bookmarks são links apresentados no decorrer do corpo do desenvolvimento e que se conectam a outra parte desse mesmo desenvolvimento.

### Implementação

1. **Definir o destino do hiperlink.**
   Utiliza-se o atributo `id` no elemento de destino. Por exemplo:

```html
   <header id="home"></header>
```

2. **Definir a origem do hiperlink.**
   Utiliza-se o símbolo `#` no atributo `href`, seguido do valor do `id` de destino. Por exemplo:

```html
   <a href="#home">Voltar</a>
```