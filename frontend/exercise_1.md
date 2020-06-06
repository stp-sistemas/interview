# React - Like button 
Criar um componente "like button" usando o React 16. O componente deve ser usar `export default` no arquivo.

## Requisitos:
* O "like button" deve:
  * Ter um conteúdo seguindo o seguinte formato: "Like | 100", onde 100 é número o total de _likes_.
  * Ter uma classe chamada `like-button`.
  * O número de "likes" deve estar contido em um `<span>` com uma classe chamada `likes-counter.
  * O número inicial de "likes" deve ser igual a 100.

* Devemos "dar um like" clicando no "like button":
  * O número de `likes` deve incrementar em 1 o valor total de _likes_.
  * A classe `liked` deve ser adicionada ao "like button" (Pode ser usada a biblioteca classnames).

* Podemos desfazer o "like" clicando novamente no "like button":
  * O contador deve decrementar em 1 o valor total de _likes_.
  * A classe `liked` deve ser removida do "like button".

## Observações:
- Acesse o [link](https://codesandbox.io/s/stp-interview-like-button-xpt8u) e faça o fork do projeto.
- Use o arquivo `LikeButton.jsx` para implementar o "like button" e adicione o componente no `index.js`.
- Apenas dois _imports_ no arquivo `LikeButton.jsx` são permitidos: React (v16.13.1) e classnames (v2.2.6). 
- Use a animação abaixo como referência para a sua solução.
- Design e estilo do componente não vai afetar sua avaliação na entrevista. Se preocupe APENAS com os requisitos.
- A aba "Browser" do _codesandbox_ irá mostrará o resultado do seu código e você poderá usar para propósitos de teste.

![Like button example](./exercise_1.gif)