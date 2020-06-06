# Questões para FrontEnd

Esse documento define as principais perguntas para a entrevista para a posição de Desenvolvedores Frontend.

Lembrando que é de suma importância o entrevistador entender as questões e saber o que esperamos como resposta do entrevistado.


## Programação básica / questões em JS:

- (Arquitetura) Quais os prós e contra programação funcional vs programação orientada à objeto?

- (Frontend) Qual a diferença entre throttling e debouncing?

- (JS) Quais são os tipos primitivos em Javascript?

- (ES6) Qual a diferença entre `const`, `var`, and `let`?  Uma breve descrição de cada uma.

- O que é uma clausura em JS (closure)? Como eles podem gerar memory leaks?
  - Explicação de problemas com referência circular na clausura por causa memory leak: https://www.ibm.com/developerworks/library/wa-memleak/

- Qual é o jeito correto de iterar sobre a propriedade de um objeto?
  - Resposta correta `for (let key in obj) { if obj.hasOwnProperty(key) { … } }`
  - Se o entrevistado souber ES6 poderá citar o `Map` também, se o fizer, perguntar sobre quando se usa `Map` e quando usar `Object`

- (Arquitetura) O que é um `Promise`? Quais as vantagens usando `Promise` em chamadas assíncronas?

- (Avançado) O q é um generator em JS e quando poderíamos usar?

## Questões espeçíficas de React:

- O que é React? Vc já usou outros frameworks em frontend? Qual a diferença entre eles?

- Descreva a diferença entre `state` e `props`.

- Qual a diferença entre _container components_ e _presentational components_?

- (Arquitetura) Descreva a arquitetura do Flux.

- (Arquitetura/Redux) Explique o que é Immutabilidade e quais as vantagens.

- O que é um Higher Order Component?
  - (Referência: https://medium.com/@franleplant/react-higher-order-components-in-depth-cf9032ee6c3e#.10on2s8ig)
