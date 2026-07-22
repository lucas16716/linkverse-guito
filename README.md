<div align="center">

<img src="public/assets/favicon/favicon.svg" width="120" height="120" alt="Logo Guito TRFZ"/>

# Linkverse • Guito TRFZ

**Traço. Música. Vivência.**

[![Status](https://img.shields.io/badge/status-em%20produção-e8e4de?style=flat-square&labelColor=10b981&color=1c1b2e)]()&nbsp;
[![Produto](https://img.shields.io/badge/produto-Linkverse-e8e4de?style=flat-square&labelColor=3437e6&color=1c1b2e)]()&nbsp;
[![Finalidade](https://img.shields.io/badge/finalidade-freelance-e8e4de?style=flat-square&labelColor=orange&color=1c1b2e)]()&nbsp;
[![Licença](https://img.shields.io/badge/licença-personalizada-e8e4de?style=flat-square&labelColor=ef4444&color=1c1b2e)](./LICENSE)

</div>

<p align="center">
  <a href="#projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#destaques-técnicos">Destaques Técnicos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#linkverse">Linkverse</a>
</p>

## PROJETO

O **Linkverse Guito TRFZ** é o hub de links oficial desenvolvido para o rapper Guito TRFZ, centralizando plataformas de streaming, lançamentos em destaque, o movimento **BECO** e os canais oficiais do artista em uma única interface.

Diferente de agregadores genéricos de link-in-bio, o projeto foi construído como uma extensão da identidade visual e da estética underground do artista – priorizando impacto visual, performance e uma experiência de navegação fluida em dispositivos móveis, onde a esmagadora maioria do público chega vindo do Instagram.

O projeto é construído sobre a arquitetura [AXIS](https://github.com/lucas16716/axis), empacotado com **Vite**, e é o segundo case oficial da linha de produtos **Linkverse**.

🌐 Acesse: [guitotrfz.vercel.app](https://guitotrfz.vercel.app/)

## DESTAQUES TÉCNICOS

- **Tipografia com Recorte de Textura (Background-Clip):** o título principal utiliza a técnica de máscara de texto sobre uma textura grunge, garantindo a estética crua da marca. Conta com fallbacks sólidos para compatibilidade cross-browser, mantendo a legibilidade intacta mesmo em navegadores legados.
- **Performance e LCP Otimizados:** estratégia de carregamento focada na experiência. O ativo visual principal (Hero) recebe prioridade de renderização (fetch priority), enquanto os recursos secundários são carregados sob demanda, evitando os temidos Cumulative Layout Shifts (CLS) e garantindo uma abertura instantânea da página.
- **Acessibilidade Nativa e Semântica:** hierarquia de conteúdo construída com marcação rigorosamente semântica, sem saltos de navegação. Elementos puramente visuais são ocultados via aria-hidden e todas as imagens possuem descrições reais. O código foi planejado para a usabilidade real com leitores de tela, indo além da simples aprovação em ferramentas de auditoria.
- **Navegação Segura e UX Contextual:** a grade de atalhos para as plataformas de streaming foi desenhada para manter o contexto do usuário. Os links externos são abertos em novas abas (`target="_blank"`) acompanhados das tags de segurança `rel="noopener noreferrer"`, prevenindo vulnerabilidades sem quebrar o fluxo de navegação.
- **Mobile-First e Interações Táteis:** sendo um hub de links, a interface foi projetada primordialmente para dispositivos móveis. O layout fluido se adapta organicamente, e os touch targets (áreas de clique) foram milimetricamente espaçados para evitar toques acidentais e frustrações.
- **Design System Tokenizado:** variáveis de cor, tipografia, espaçamentos e transições encapsuladas como tokens no SCSS. Uma base arquitetural modular, extremamente limpa e escalável, facilitando a manutenção e a expansão da identidade visual para futuros lançamentos.
- **Otimização para Compartilhamento (Open Graph):** implementação completa de metatags sociais (título, descrição e thumbnail). Ao compartilhar o Linkverse no WhatsApp, Instagram ou Twitter, a pré-visualização do card é gerada com perfeição, fortalecendo a presença da marca antes mesmo do clique.

## TECNOLOGIAS

| Tecnologia      | Uso                                                       |
| --------------- | --------------------------------------------------------- |
| HTML5           | Estrutura semântica com meta tags de SEO e Open Graph     |
| Sass (SCSS)     | Arquitetura AXIS com design tokens                        |
| JavaScript ES6+ | Inicialização e controle do carrossel de lançamentos      |
| Swiper.js       | Carrossel touch de alta performance com suporte a teclado |
| Vite            | Bundler, minificação e gestão de assets                   |
| Vercel          | Deploy, hospedagem e domínio                              |
| AXIS            | Arquitetura Sass utilizada como fundação do projeto       |

## LINKVERSE

O **Linkverse** é uma linha de hubs de links personalizados desenvolvida pela **LUCASCODE**.

Cada projeto é criado individualmente para refletir a identidade visual, os objetivos e a estratégia digital de cada cliente ou artista – oferecendo uma alternativa profissional e proprietária aos agregadores de links tradicionais.

Este repositório é o segundo case oficial do produto, ao lado do [Linkverse M&A Consultoria Câmbio](https://github.com/lucas16716/linkverse-ma).

## 📝 LICENÇA

Este projeto possui uma **licença profissional personalizada**. O código está disponível para consulta pública, estudos arquiteturais e portfólio. Porém é estritamente **proibida** sua reprodução, clonagem ou uso comercial sem autorização expressa.

Veja o arquivo [LICENSE](./LICENSE) para mais detalhes.

## 🧑🏻‍💻 AUTOR

Desenvolvido com muito código e café por [Lucas Couto](https://linkedin.com/in/lucas-coutoti)

Conheça meu trabalho ou entre em contato pelo site [Lucas Code](https://bio.site/lucascode)

Projeto desenvolvido para **Guito TRFZ**
