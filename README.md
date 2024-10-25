# POC-React

<img src="https://pbs.twimg.com/profile_images/1785867863191932928/EpOqfO6d_400x400.png" width="600px" >


# Conceitos de React utilizando o Next.JS

 <!--ts-->
 
 * [Estrutura de Projeto NextJS](#Estrutura)
 * [Criação de componentes simples (sem estado)](#Componentes)
 * [Estilo CSS (global e módulo).](#Estilo)
 
 <!--te-->

 ## Estrutura
A estrutura básica de um projeto Next.js geralmente se parece com isso:
~~~javascript
   my-next-app/
   ├── app/
   │   ├── page.js
   │   ├── layout.js
   │   ├── globals.css
   │   └── ... (outras pastas e arquivos)
   ├── public/
   │   ├── images/
   │   └── favicon.ico
   ├── styles/
   │   └── globals.css
   ├── package.json
   ├── next.config.js
   └── README.md
~~~
1. Pasta app/<br>
A nova estrutura de app é uma das principais mudanças no Next.js 13 e continuou em 14. Aqui estão os componentes principais:,<br>
page.js: Este arquivo define uma página em sua aplicação. Cada page.js em uma subpasta dentro de app representa uma rota. Por exemplo, app/about/page.js seria acessível em /about.<br>
layout.js: Este arquivo define o layout da sua aplicação. Você pode usar este componente para encapsular páginas comuns, como cabeçalhos ou rodapés, evitando a repetição de código.<br>
globals.css: Aqui você pode definir estilos globais para toda a sua aplicação. O Next.js cuida do carregamento desses estilos.

2. Pasta public/
Contém arquivos estáticos, como imagens e ícones, que podem ser acessados diretamente pela URL. Por exemplo, public/images/logo.png pode ser acessado em /images/logo.png.
3. Pasta styles/
Usada para armazenar estilos específicos da aplicação. Você pode organizar seus arquivos CSS ou usar pré-processadores como SASS.
4. Arquivo package.json
Contém as dependências do projeto, scripts de execução e outras configurações do npm. Aqui você encontrará pacotes como react, next, entre outros.
5. Arquivo next.config.js
Usado para configurar opções do Next.js, como redirecionamentos, reescritas de URL, e outras personalizações.
6. Arquivo README.md
Um arquivo padrão que pode ser usado para documentar seu projeto, instruções de instalação, uso e outras informações úteis.

 ## Componentes

 ~~~javascript


~~~


 ## Estilos

 ~~~javascript


~~~

