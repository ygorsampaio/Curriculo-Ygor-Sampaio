# Portfólio & Currículo Web — Ygor Sampaio

Este repositório contém o ecossistema do meu portfólio web pessoal, composto por uma Landing Page minimalista e imersiva conectada a um Currículo Técnico detalhado. O projeto foi desenhado sob a estética **Cyber-Dark** com foco em altíssima performance, fluidez visual e sem a necessidade de scripts adicionais para a interface.

⚡ **Acesse o projeto rodando ao vivo:** [https://curriculo-ygor-sampaio.vercel.app/]

---

## 🗺️ Arquitetura do Projeto

O ecossistema é dividido em duas interfaces principais estruturadas de forma independente, garantindo que o usuário navegue com o máximo de performance e carregamento instantâneo:

### 1. 🪐 Landing Page (`landing.html`)
A porta de entrada do projeto. Uma interface focada em branding pessoal e impacto visual rápido:
*   **Orbes Dinâmicos:** Esferas de luz difusas que flutuam em segundo plano via animações CSS (`@keyframes`), gerando profundidade espacial.
*   **Tech Strip:** Uma vitrine minimalista exibindo os principais ícones e tecnologias de domínio do desenvolvedor.
*   **Foco em Conversão (CTA):** Direcionamento estratégico para o currículo completo ou para o ecossistema do GitHub.

### 2. 📄 Currículo Detalhado (`script.html`)
A central de informações profissionais e acadêmicas:
*   **Módulos de Experiência:** Linha do tempo limpa detalhando atuações de impacto (como Porto Digital/Capgemini e KPMG).
*   **Categorização de Skills:** Divisão exata entre competências de Engenharia de Dados, Full-Stack e Automação/BI.

---

## 🚀 Recursos Técnicos de Destaque

*   **🎨 Efeito de Ruído Digital (Noise Overlay):** Injeção de uma textura sutil de ruído procedural diretamente através de uma string SVG embutida no CSS background, dispensando o uso de imagens externas pesadas.
*   **📱 Tipografia Fluida:** Uso da função `clamp()` para fazer com que os títulos principais se adaptem organicamente ao tamanho da tela do dispositivo sem quebras abruptas.
*   **⚡ Zero Overheads:** Layout puramente construído com CSS sem dependência de frameworks ou bibliotecas externas de script, priorizando o menor tempo de carregamento possível.

---

## 🛠️ Tecnologias e Ferramentas Empregadas

*   **Linguagens & Frontend:** HTML5 e CSS3 Avançado (Variáveis nativas, CSS Grid, Flexbox e Animações).
*   **Design & Vetores:** SVGs inline otimizados para redução de requisições HTTP e fontes do ecossistema Google Fonts (*Plus Jakarta Sans*, *Syne*, e *DM Sans*).
*   **Core Técnico do Portfólio (Stack):** Python, SQL, Azure Databricks, Power Platform (Apps, Automate, BI, Power Fx), Node.js, React e APIs/MuleSoft.

---

## 📂 Estrutura de Arquivos

```text
.
├── landing.html       # Página inicial (Apresentação, orbes flutuantes e links)
├── script.html        # Currículo completo estruturado profissionalmente
├── landing.css        # Estilizações e animações dos orbes da Landing Page
├── script.css         # Identidade visual Cyber-Dark e grid do Currículo
└── README.md          # Documentação técnica do repositório
