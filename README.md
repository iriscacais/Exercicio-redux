# Exercicio-redux
Redux puro, usando html e JavaScript.

## Exercício 01 da sessão 7 do módulo front-end da Trybe. 

1. Criar uma store;
2. Criar o reducer implementando switch com valor default;
3. Incrementar o switch com os cases NEXT_COLOR e PREVIOUS_COLOR;
4. Criar eventListeners para os botões Previous color e Next color, e realizar um dispatch com as respectivas actions.
5. Fazer o subscribe da store, alterando o innerHTML da tag com id value para a cor atual e o style do elemento com id container.
6. Criar um botão com o texto Random color, um eventListener e uma action no reducer. Utilizando a função de criar cores aleatórias:
```
function criarCor() {
    const oneChar = ['1', '2', '3', '4', '5', '6', '7', '8', '9', 'A', 'B', 'C', 'D', 'E', 'F'];
    let cor = '#';
    const aleatorio = () => Math.floor(Math.random() * oneChar.length);
    for (let i = 0; i < 6; i += 1) {
        cor += oneChar[aleatorio()];
    }
    return cor;
}
```

## Exercício 02 da sessão 7 do módulo front-end da Trybe. (light&dark.html)

1.  Criar um reducer com os estados iniciais;
2.  Criar uma store;
3.  Adicionar um case no reducer para alterar os estados theme e status;
4.  Fazer o dispatch de cada uma das actions ao clicar nos respectivos botões;
5.  Adicionar um store.subscribe() para atualizar as informaçõs na tela.
