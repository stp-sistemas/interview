# React - Like button 
Criar um componente **\<LikeButton/\>** usando o React 16. O componente deve ser usar `export default` no arquivo.

## Requisitos:
* O **\<LikeButton/\>** deve:
  * Ter um conteúdo seguindo o seguinte formato: "Like | 100", onde 100 é número o total de _likes_.
  * Ter uma classe chamada `like-button`.
  * O número de _likes_ deve estar contido em um `<span>` com uma classe chamada `likes-counter`.
  * O número inicial de _likes_ deve ser igual a 100.

* Devemos "dar um _like_" clicando no **\<LikeButton/\>**:
  * O número de _likes_ deve incrementar em 1 o valor total de _likes_.
  * A classe `liked` deve ser adicionada ao **\<LikeButton/\>** (A biblioteca _classnames_ pode ser usada para facilitar a implementação).

* Podemos desfazer o _like_ clicando novamente no **\<LikeButton/\>**:
  * O contador deve decrementar em 1 o valor total de _likes_.
  * A classe `liked` deve ser removida do **\<LikeButton/\>**.

## Observações:
- Acesse o [link](https://codesandbox.io/s/stp-interview-like-button-xpt8u) e faça o fork do projeto.
- Use o arquivo `LikeButton.jsx` para implementar o **\<LikeButton/\>** e adicione o componente no `index.js`.
- Apenas dois _imports_ no arquivo `LikeButton.jsx` são permitidos: React (v16.13.1) e classnames (v2.2.6). 
- Use a animação abaixo como referência para a sua solução.
- Design e estilo do componente não vão afetar sua avaliação na entrevista. Se preocupe APENAS com os requisitos.
- A aba "Browser" do _codesandbox_ mostrará o resultado do seu código, ajudando à testá-lo.

![Like button example](./exercise_1.gif)