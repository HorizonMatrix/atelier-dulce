# Atelier Dulce

Site de Dulce Esteves: desenhos originais feitos à mão, emoldurados e prontos a pendurar.

## Como editar

Todo o conteúdo está no bloco `SITE`, no fim do ficheiro `index.html` (procura "EDITAR AQUI"):

- **Contactos**: `whatsapp` (indicativo + número, sem espaços, ex.: `351912345678`), `email`, `instagram`, `cidade`.
- **Biografia**: a lista `bio`, um parágrafo por linha.
- **Obras**: põe a foto em `img/quadros/` e acrescenta um bloco à lista `quadros`:

```js
{
  titulo: "Nome da obra",
  imagem: "img/quadros/nome-do-ficheiro.jpg",
  tecnica: "Lápis de cor sobre papel",
  medidas: "30 × 40 cm, com moldura",
  preco: 45,
  estado: "disponivel",   // "disponivel", "reservado" ou "vendido"
  descricao: "Uma frase sobre a obra."
}
```

As fotos ficam melhor na vertical (3:4), de frente e com luz natural.

## Publicação

O site é publicado com GitHub Pages a partir do ramo `main` (Settings → Pages → Deploy from a branch → `main` / root).
