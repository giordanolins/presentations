## Desenvolvimento Moderno com PHP
---

### Ferramentas

- IDE's (aka Editores)

    Netbeans, Aptana Studio, PHPStorm, Atom, Brackets, Visual Studio Code, Sublime, Notepad++, GEdit

- Composer

    É uma ferramenta para o gerenciamento de dependências em PHP. Ele permite que você declare as bibliotecas que seu projeto depende e as gerencia (instala/atualiza) para você.[[1]]

    Por padrão, ele gerencia as dependências separadamente para cada projeto, instalando-as em um diretório (*vendor*). Entretanto, ele suporta a instalação *[global](https://getcomposer.org/doc/03-cli.md#global)* caso assim se deseje.

    Esse tipo de ferramenta não é novidade e o Composer é fortemente inspirado no *[npm](https://npmjs.org/)* e no *[bundler](http://bundler.io/)*.

- Bower

    É um gerenciador de dependências criado pelo Twitter para resolver as dependências de componentes HTML, CSS, Javascript, fontes e até mesmo imagens.

- Gulp

    É uma ferramenta de build para o front-end. O Gulp provê um framework que auxilia o processo de build do desenvolvedor web. Os recursos do Gulp são distribuiídos em forma de plugins que extendem a capacidade do mesmo.

    ```javascript
    gulp.task('sass', function() {
      return sass('src/styles/main.scss', { style: 'expanded' })
        .pipe(autoprefixer('last 2 version', 'safari 5', 'ie 8', 'ie 9', 'opera 12.1', 'ios 6', 'android 4'))
        .pipe(gulp.dest('dist/assets/css'))
    });
    ```

- Git

    É um sistema de controle de versão distribuído gratuito e open source desenhado para gerenciar projetos de todos os tamanhos com velocidade e eficiência.
    
    É fácil de aprender e tem um footprint muito pequeno, com uma performance incrível. Ele ultrapassa seus principais concorrentes com recursos como branches locais "baratos", areas de elencagem de conveniência, e multiplos workflows.

- OS (Linux / Mac / Windows)

- Cloud (Amazon / DigitalOcean / OpenShift)

    - Aplicações hospedadas em VPS
    - Aplicações escaláveis
    - Menor custo operacional
    - Melhor custo/benefício

- Vagrant / Docker

    - Ambientes de desenvolvimento virtualizados
    - Nada de "Funciona na minha máquina"
    - Ambientes de desenvolvimentos muito próximos (ou iguais) ao de produção

### Padrões

- PSR's (PHP Fig)

    0 - Autoloading Standard (Deprecated)
    1 - Basic Coding Standard
    2 - Conding Style Guide
    3 - Logger Interface
    4 - Autoloading Standard
    6 - Caching Interface
    7 - HTTP Message Interface

- Padrões de Projeto

    Um Design Pattern é uma solução geral reutilizável para um problema que ocorre com frequência dentro de um determinado contexto no projeto de software. 

- S.O.L.I.D

    São cinco princípios de desenho orientado a objetos. Eles têm a intenção de fazer com que um sistema criado seja mais fácil de manter e extender (evoluir).
    
    - SRP - Single Responsability
    - OCP - Open-Closed
    - LSP - Liskov Substitution
    - ISP - Interface Segregation
    - DIP - Dependency Inversion

- DDD (Domain-Driven Design)

    É uma abordagem de desenvolvimento de softwares complexos que visa a implementação conectada diretamente com a evolução do modelo de negócio.

- Frameworks

### Frameworks

- Interoperabilidade
- Opções
- Market Share

### PHP 7

http://tableless.com.br/10-novidades-do-php-7/

- Desempenho! Muito desempenho!!!
- Erros fatais, no more! Exeptions! \o/
- Evolução da Linguagem

    - Traits
    - Funções Anônimas

    - Funções mysql_* e ereg_* removidas 
    - Construtores do PHP4 obsoletos
    - Tipos Escalares (Linguagem francamente tipada)
    - Tipos de retorno em funções e métodos
    - Novo operador <=> "Spaceship"
    - Null COalesce Operator (??)
    - Classes Anônimas



### Orientação a Objetos

- Design Orientado a Objetos
- Design Orientado a Interfaces
- Design Orientado aos Padrões de Projeto, Princípos S.O.L.I.D e DRY

### Dicas Para Desenvolvedores

- Iniciantes
- Familiarizados
- Experientes

### Inglês

- Inglês Técnico
- Literatura
- Documentação
- Recursos Multimídia
- Aprendizado Globalizado
- EDX, Coursera, outros

### GitHub

---
[[1]] https://getcomposer.org/doc/00-intro.md

---
[1]: https://getcomposer.org/doc/00-intro.md
