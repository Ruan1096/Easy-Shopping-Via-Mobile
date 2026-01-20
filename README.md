🛒 Easy Shopping - Mobile First Landing Page
Este projeto é uma Landing Page moderna de e-commerce focada em compras mobile. O objetivo principal foi aplicar conceitos avançados de CSS para criar uma interface limpa, elegante e totalmente responsiva.

🛠️ O que foi desenvolvido?
Neste projeto, foquei em resolver desafios comuns de layout e experiência do usuário (UX):

1. Estrutura Split-Screen (Tela Dividida)
Implementei um layout de duas colunas utilizando CSS Flexbox para garantir um alinhamento preciso entre o conteúdo textual e o visual.

Utilizei proporções de tela dinâmicas (60/40) para manter o equilíbrio visual em resoluções desktop.

2. Design Responsivo (Media Queries)
Criei uma transição suave para dispositivos móveis utilizando @media queries.

O layout se adapta de um modelo horizontal para vertical em telas menores que 900px, garantindo que o texto e o botão permaneçam legíveis e fáceis de clicar (touch-friendly).

3. Técnicas de Estilização e UI
Tipografia Dinâmica: Integração com Google Fonts (Oswald e Montserrat) para uma hierarquia visual clara.

Posicionamento Estratégico: Uso de position: absolute e relative para criar o efeito de sobreposição da imagem entre os dois containers, dando profundidade ao design.

Feedback Visual: Implementação de estados de hover e active nos botões e links de navegação para melhorar a interatividade.

4. Boas Práticas
Uso de box-sizing: border-box para um controle preciso de espaçamentos (padding/border).

HTML5 semântico com tags como <header>, <section> e <a> para melhor acessibilidade e SEO.

🚀 Tecnologias
HTML5

CSS3 (Flexbox, Media Queries, Transições)

Google Fonts

📝 Detalhes Técnicos do Projeto
📐 Arquitetura do Layout
O projeto foi construído utilizando uma abordagem de containers independentes, permitindo que o conteúdo textual e os elementos visuais cresçam de forma organizada.

Box Model: Utilizei a propriedade box-sizing: border-box em todo o projeto para garantir que paddings e borders não quebrassem as dimensões calculadas dos elementos, mantendo o layout matemático perfeito.

Transparências Camadas: A coluna da direita utiliza rgba(93, 93, 125, 0.16). Essa escolha de design permite um efeito de profundidade sem perder o contraste necessário para a leitura dos links do menu.

🧠 Desafios de CSS Resolvidos
Sobreposição de Imagem (Overlap): Um dos maiores desafios foi fazer com que a imagem da ilustração "escapasse" do seu container para invadir a área da esquerda. Isso foi resolvido combinando position: relative e valores negativos/percentuais de right, criando um efeito visual de camadas (layering) que é tendência no design moderno.

Hierarquia Tipográfica: Apliquei diferentes pesos de fonte e line-height específicos. No h1, o espaçamento entre linhas de 80px foi pensado para dar peso e importância ao título, enquanto no corpo do texto (p), a opacidade de 0.6 foi usada para criar um contraste secundário, guiando o olho do usuário primeiro para o título e depois para a descrição.

📱 Estratégia de Responsividade
Em vez de apenas "esconder" elementos, a estratégia de adaptação para telas menores (abaixo de 900px) incluiu:

Reorganização de Fluxo: Mudança do display: inline-block para um fluxo de bloco vertical.

Otimização de Toque: Aumentei a área clicável do botão e centralizei os elementos para facilitar a navegação com o polegar em dispositivos móveis.

Ajuste de Escala: A fonte do título é reduzida drasticamente de 70px para 36px via Media Queries para evitar que o usuário precise fazer muito scroll para ler a mensagem principal.

<img width="700" height="100" alt="image" src="https://github.com/user-attachments/assets/9670245c-d6a3-4c80-8458-972f9cc36f66" />
<br/>
<br/>
<br/>
<br/>
<br/>


Previa:
<img width="469" height="269" alt="Easy Shopping Via Mobile" src="https://github.com/user-attachments/assets/ebc3932c-122e-427b-b38a-3985a8590004" />







