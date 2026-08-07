# 🌿 Site Institucional: Tessmann Consultoria

![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)
![Contexto](https://img.shields.io/badge/Contexto-Freelance-blueviolet)
![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-success)

Este projeto marca o meu primeiro trabalho como desenvolvedor freelancer, criado para a cliente **Tessmann Consultoria & Treinamentos**. Trata-se de uma aplicação Front-end estática focada em apresentar os serviços corporativos da empresa (segurança do trabalho, primeiros socorros e saúde mental) de forma clara, moderna e responsiva.

---

## 🎯 Objetivo do Projeto

O objetivo principal foi entregar uma presença digital profissional e de alta performance para a cliente. Como as informações dos serviços e da empresa são estruturais e não exigem atualizações diárias, a arquitetura foi planejada para ser 100% Front-end (sem a complexidade de um Back-end ou banco de dados), garantindo menor custo de manutenção, maior segurança e altíssima velocidade de carregamento.

---

## 🚀 Funcionalidades

O site funciona como uma vitrine digital da consultoria, oferecendo as seguintes capacidades:

1. **Navegação SPA (Single Page Application):** Transições fluidas e sem recarregamento de página entre as diferentes seções do site.
2. **Catálogo de Serviços Estruturado:** Páginas dedicadas e detalhadas para as frentes de atuação da empresa, incluindo *Primeiros Socorros (Lei Lucas)*, *Saúde Mental* e *Treinamentos de NRs*.
3. **Apresentação Institucional:** Seções exclusivas sobre a história da fundadora e os pilares de atuação da empresa, gerando autoridade e confiança.
4. **Componentes de Conversão (CTAs):** Chamadas para ação distribuídas estrategicamente para direcionar o usuário à página de contato de forma intuitiva.

---

## 🛠️ Tecnologias Utilizadas

* **Angular (v20):** Framework Front-end robusto utilizado como base para a construção de toda a interface e roteamento.
* **TypeScript:** Superconjunto de JavaScript utilizado para garantir a tipagem estática e maior segurança no código durante o desenvolvimento.
* **Bootstrap (v5.3):** Framework CSS utilizado para a construção ágil do layout e estruturação em grid.
* **FontAwesome (v7):** Biblioteca de ícones vetoriais empregada na identidade visual e nos blocos de serviços.
* **Angular CLI gh-pages:** Ferramenta utilizada para automatizar o processo de compilação (build) e deploy diretamente no GitHub Pages.
* **Vercel Speed Insights:** Integração para monitoramento de métricas de performance do site em produção.

---

## 🧠 Conceitos Aplicados

* **Desenvolvimento Baseado em Componentes:** Divisão da interface em blocos modulares e reutilizáveis (como a tag customizada `<app-cta-section>`), mantendo o código limpo e de fácil manutenção.
* **Roteamento de Front-end (Routing):** Configuração de rotas internas no Angular (utilizando a diretiva `[routerLink]`) para gerenciar a navegação do usuário de forma ágil, sem novas requisições ao servidor.
* **Mobile-First & Design Responsivo:** Aplicação do sistema de grids e classes utilitárias do Bootstrap (como `col-md-4`, `img-fluid`, etc.) para garantir que o layout se adapte perfeitamente a smartphones, tablets e desktops.
* **Arquitetura Estática (KISS):** Decisão arquitetural de manter o sistema simples, direto e econômico, resolvendo o problema de negócio da cliente sem incluir a sobrecarga técnica de um servidor back-end desnecessário.
* **Automação de Deploy:** Configuração de scripts NPM customizados (`npm run deploy`) para gerar a versão de produção otimizada com `--base-href` correto e publicá-la automaticamente.
