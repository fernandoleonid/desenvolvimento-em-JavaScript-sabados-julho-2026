# Aula 01 - Fundamentos de HTML, CSS e JavaScript

## Sobre a aula

Nesta primeira aula, revisamos os fundamentos para criação de aplicativos e sistemas web usando:

- HTML: estrutura da página
- CSS: estilo e aparência
- JavaScript: comportamento e interatividade

Também reforçamos que o JavaScript é a linguagem nativa de programação no navegador (frontend), sendo essencial para tornar a interface interativa.

## O que foi visto na aula

1. Revisao dos papeis de cada tecnologia:
- HTML para estrutura
- CSS para estilo
- JavaScript para comportamento

2. Organizacao em arquivos separados e vinculacao:
- `index.html`, `style.css` e `app.js`
- CSS com `<link rel="stylesheet" href="./style.css">`
- JS com `<script src="./app.js" defer></script>`

3. Introducao a variaveis em JavaScript:
- Explicação do que é variável
- Palavras reservadas `var`, `let` e `const`
- Boas práticas: evitar `var`, priorizar `const` e usar `let` quando houver necessidade de reatribuição

4. Selecao de elementos da tela:
- Uso de `getElementById`
- Necessidade de definir `id` nos elementos HTML

5. Funcoes e interacao com o usuario:
- Criacao de funcoes para organizar a logica
- Uso de `addEventListener`
- Evento `click`
- Chamada de funções após a ação do usuário

6. Organizacao entre CSS e JS:
- Regra geral reforçada em aula: cada tecnologia no seu papel
- Sempre que possível, concentrar estilo no CSS e usar JS para aplicar/remover classes
- Mesmo quando o JS consegue alterar estilo diretamente, priorizar uma organização limpa e escalável

## O que existe no projeto atual

### `index.html`

A página contém:

- Campo para digitar nome (`id="nome"`)
- Botão para mostrar mensagem (`id="botao"`)
- Campo para digitar cor (`id="cor"`)
- Botão para trocar cor de fundo (`id="botaoTrocarCor"`)

Também há:

- `id="body"` na tag `<body>`
- Importação de `style.css`
- Importação de `app.js` com `defer`

### `style.css`

Foram definidos:

- Variável CSS `--cor-bg` no `:root`
- Estilos para `.caixaTexto` e `.botao`
- Classes de cor (`.vermelho`, `.azul`, `.amarelo`)
- Cor de fundo do `body` baseada em `--cor-bg`

### `app.js`

Foi implementado:

- Captura de elementos com `getElementById`
- Função `mostrarMensagem()` para exibir `alert` com o nome digitado
- Função `trocarCor()` para alterar a variável CSS `--cor-bg` com base no valor digitado
- Eventos de clique com `addEventListener` nos dois botões

## Fluxo do projeto

1. O aluno digita um nome.
2. Ao clicar em "Mensagem", o sistema mostra `Olá <nome>!`.
3. O aluno digita uma cor (ex.: `red`, `blue`, `yellow`, `green`).
4. Ao clicar em "Trocar Cor", o fundo da página é atualizado.

## Como executar

1. Abra a pasta `aula01`.
2. Abra o arquivo `index.html` no navegador.
3. Teste os botões e os campos de entrada.

## Autor

Prof. Fernando Leonid

[![LinkedIn](https://img.shields.io/badge/LinkedIn-fernandoleonid-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/fernandoleonid/)
[![YouTube](https://img.shields.io/badge/YouTube-fernandoleonid-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@fernandoleonid)
[![Instagram](https://img.shields.io/badge/Instagram-fernandoleonid-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/fernandoleonid/)
