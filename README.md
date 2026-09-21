# Reposi-aoEmGrupo-PI2
Reposição de Projeto Integrador II do dia 15/09, passada pelo professor Rodrigo Faustino. 

GRUPO - ARACHNIX: Felipe Viana; Miguel WIlliams; João Victor Santana e Gabriel Oliveira.

# Questões

Escolhemos o framework Bootstrap:

# A1. O que é o framework e qual abordagem ele segue? 
Bootstrap é um framework CSS que fornece classes e componentes prontos para facilitar a criação de páginas web. Ele segue uma abordagem baseada em componentes e classes reutilizáveis, além de oferecer um sistema de grid responsivo para adaptar o layout a diferentes tamanhos de tela.

# A2. Como você incluiu o framework na página?
Nosso grupo incluiu o Bootstrap 5.3.2 nas três páginas do projeto (index.html, servicos.html e contato.html) através de um CDN. No <head> foi adicionado o arquivo CSS e, no final do <body>, o arquivo JavaScript bootstrap.bundle.min.js. Depois utilizamos classes do Bootstrap como container, navbar, row, col-md-4, card, bg-primary e text-center para montar as páginas.

# A3. Cite três benefícios que você percebeu ao usar, não apenas os que o site do framework anuncia. 
Um benefício que percebemos foi a facilidade para criar o menu de navegação sem precisar desenvolver todo o CSS manualmente. Também foi mais fácil criar um layout responsivo para os cards de serviços e mascotes usando row e col-md-4. Por último, as classes de espaçamento, cores e alinhamento, como py-5, my-5, mb-5 e text-center, permitiram organizar visualmente as páginas com pouco código.

# A4. Cite duas limitações ou desvantagens. Exemplos: tamanho do arquivo baixado, aparência genérica, curva de aprendizado, dificuldade para sobrescrever um estilo. 
Uma limitação que percebemos é que vários elementos ficam com uma aparência semelhante ao padrão do Bootstrap, principalmente componentes como a barra de navegação e os cards. Outra é que o projeto passa a depender de várias classes específicas do framework, então é necessário conhecer o funcionamento delas para conseguir modificar o visual com mais precisão através do CSS próprio.

# A5. Abra o CSS do framework (ou inspecione um elemento no DevTools F12). Ele estiliza usando classes ou IDs? Por que você acha que frameworks preferem um dos dois? 
O Bootstrap utiliza principalmente classes para aplicar seus estilos, como .container, .navbar, .card, .row e .col-md-4. Isso permite reutilizar o mesmo estilo em vários elementos e combinar diferentes classes em um único elemento. IDs são destinados a elementos específicos e possuem maior especificidade, enquanto classes são mais reutilizáveis e fáceis de sobrescrever.

# A6. Fontes: a documentação oficial é obrigatória, mais pelo menos uma outra fonte. Para cada uma: título, endereço e data de acesso. 

Bootstrap — Documentação Oficial Get started with Bootstrap
https://getbootstrap.com/docs/5.3/getting-started/introduction/
Data de acesso: 20/09/2026

MDN Web Docs — Seletores CSS
https://developer.mozilla.org/pt-BR/docs/Web/CSS/Guides/Selectors
Data de acesso: 20/09/2026

Bootstrap - Grid System
https://getbootstrap.com/docs/5.3/layout/grid/
Data de acesso: 20/09/2026
