# Aluracord

## Conteúdo

- [Imersão React](https://www.alura.com.br/imersao-react)
    - [Aula 1](https://www.alura.com.br/imersao-react/aula01-react-aluracord)
        - Iniciaremos um projeto Next.js;
        - Criaremos components com React usando CSS in JS;
        - Vamos ver a estrutura inicial de um projeto Next.js;
        - Passaremos propriedades para components;
        - Faremos deploy do seu Aluracord na Vercel.
    - [Aula 2](https://www.alura.com.br/imersao-react/aula02-react-state-form)
        - Entender melhor o que é um SPA;
        - Conhecer o useState do React;
        - Como trabalhar com eventos no React onSubmit, onClick;
        - E sempre após cada push na sua branch principal do GitHub faremos deploy do seu Aluracord na Vercel.
    - [Aula 3](https://www.alura.com.br/imersao-react/aula03-chat-offline)
        - Entender um pouco mais de como podemos trabalhar com state no React;
        - Trabalhar com arrays no state;
        - Criar um campo que ao apertamos o "Enter", faz o submit das informações;
    - [Aula 4](https://www.alura.com.br/imersao-react/aula04-supabase-e-ajax)
        - AJAX e o que é?
        - Supabase
        - Aba network para debugarmos requests HTTP
        - useEffect no React
    - [Aula 5](https://www.alura.com.br/imersao-react/aula05-chat-e-realtime)
        - Web Sockets
        - E adicionar os stickers que você pode pegar VÁRIOS [aqui](https://github.com/alura-challenges/aluracord-matrix/blob/main/config.json#L33) :)

## Desenvolvimento

Iniciar projeto criando o `package.json`.
```sh
npm init
```

Criar projeto NextJS.
```sh
yarn add next react react-dom
```

Adicionar bibliotecas de componentes visuais.
```sh
yarn add @skynexui/components
```

Criar arquivo `.gitignore` com o perfil Node para não versionar o node_modules.
```sh
npx gitignore node
```
## Execução

Baixar dependências `node_modules`
```sh
npm install
```

Subir aplicação.
```sh
yarn run dev
```

## Deploy

https://aluracord-iota-rouge.vercel.app

## Referências

- [NextJS](https://nextjs.org/docs#manual-setup)
    - [Custom App](https://nextjs.org/docs/advanced-features/custom-app)
- Skynexui
    - [GitHub](https://github.com/skynexui/components)
    - [Docs](https://docs-skynexui.vercel.app)