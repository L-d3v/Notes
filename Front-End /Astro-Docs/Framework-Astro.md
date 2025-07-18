# Framework - Astro

Astro se trata de um Framework destinado a construção de websites que possuem como foco, a apresentação de
conteúdos (Blogs, E-commerce, Marketing, etc). Astro também é conhecido como um pioneiro por apresentar uma
nova arquitetura de frontend que visa reduzir a complexidade do JavaScript em relação a outros Frameworks.

### Por que Astro?

- Astro tem como objetivo de ser acessível para qualquer desenvolvedor web, independente do nível de
  habilidade ou experiência com desenvolvimento web. Astro auxilia a criação de websites ricos em conteúdos,
  em outras palavras, todo conteúdo presente no site deve alcançar seus leitores o mais rápido possível.
  Sendo assim, tornando-o diferente da maioria dos frameworks modernos que foram criados para construir uma
  experiência mais complexa;

- Ele busca “enxugar” a construção de aplicações focando em incluir tudo o que você precisa para criar um
  website, seja ele estático ou dinâmico, disponibilizando centenas de funcionalidades capazes de customizar
  seu projeto conforme a necessidade, alguns dos principais são:

  - **Ilhas:** Trata-se de uma arquitetura baseada em componentes otimizados e focados na apresentação dos
    conteúdos;
  - **UI Agnóstico:** Oferece suporte ao React, Svelte, Vue, Solid, entre outros frameworks;
    Servidor em Primeiro: Move o processo de renderização para um servidor, buscando melhorar o
    desempenho, segurança e SEO do site;
  - **Zero JS:** Por padrão, os componentes Astros renderizam HTML em tempo de build ou sob demanda através
    da renderização ao lado do servidor;
  - **Coleção de Conteúdos:** Pastas de nível superior dentro de pastas reservadas do projeto que apresentão
    coleções de conteúdos como Markdown, MDX, YAML ou JSON.

- Sua linguagem .astro trata-se de uma extensão do HTML, onde qualquer código HTML escrito será válido. No
  entanto, sua linguagem permite combinar outras funcionalidades “emprestadas” e outras linguagens como
  expressões JSX (React) e CSS com escopos por padrão (Svelte e Vue);

### Servidor em Primeiro

- Enquanto alguns frameworks fazem o uso da Aplicação de Página Única(SPA - Single Page Application), o
  Astro faz uso da mesma abordagem que alguns frameworks de servidores tradicionais(PHP, WordPress, Laravel,
  Ruby, etc) que se trata da Aplicação de Múltiplas Páginas (MPA- Multi Page App);

- Não se pode negar que o uso da abordagem de SPA possui muitos benefícios, entretanto, o seu uso vem
  acompanhado de uma complexidade adicional e tardeoff que prejudicam a performance da página;

- A idéia de colocar o servidor em primeiro lugar permite na escolha de qual renderização utilizar, sendo
  que, para a renderização ao lado cliente, utiliza-la somente quando necessário.
