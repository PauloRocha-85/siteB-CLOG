# 🚛 B&C Logística - Website Oficial

Website institucional moderno e responsivo desenvolvido para a **B&C Logística, Cargas e Descargas LTDA**. O projeto inclui uma apresentação completa dos serviços da empresa, catálogo de frota, clientes atendidos, layout totalmente adaptado para dispositivos móveis e um **Assistente Virtual Inteligente** integrado ao WhatsApp.

---

## 📸 Recursos e Funcionalidades

- **Menu Fixo Glassmorphism:** Navegação intuitiva com efeito de vidro fosco no topo da página.
- **Hero Section Reestruturada:** Banner inicial de alto impacto visual com frases de destaque, chamadas para ação (CTA) e destaques de segurança, pontualidade e rastreamento.
- **Assistente Virtual Inteligente (Mascote Flutuante):**
  - Chat interativo sem redirecionamento imediato.
  - Questionário guiado em 3 etapas para cotação de frete (Tipo de veículo, Origem/Destino e Qtd. de entregas).
  - Direcionamento automatizado do resumo da cotação com texto pré-formatado para os contatos operacionais (**Cleiton** e **Jocelio**).
  - Opções de contato direto com a equipe via WhatsApp.
- **Grade Dinâmica de Clientes:** Exibição centralizada dos logotipos dos principais clientes com efeito *hover* e layout responsivo em grid.
- **Rodapé Informativo:** Acesso direto via ícones do WhatsApp aos responsáveis, e-mail corporativo, dados de CNPJ e endereço institucional.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica da página.
- **CSS3:** Estilização moderna, CSS Grid, Flexbox, animações `@keyframes` e media queries para responsividade.
- **JavaScript (ES6):** Lógica interativa do assistente virtual, controle de estados do formulário e integração com a API do WhatsApp (`https://wa.me/`).
- **FontAwesome (v6):** Ícones vetoriais da interface e redes sociais.

---

## 📂 Estrutura de Arquivos

```text
├── imagem/
│   ├── BC LOGO.jpg           # Logotipo oficial da empresa
│   ├── banner-hero.jpg       # Imagem de fundo principal (Caminhão)
│   ├── mascote.png           # Avatar transparente do Assistente Virtual
│   ├── favicon.png           # Ícone da aba do navegador
│   ├── grupo-mateus.jpg      # Logo de cliente
│   ├── grupo-pao-de-acucar.jpg
│   ├── m-dias-branco.jpg
│   ├── ifco-systems.jpg
│   ├── grupo-alyne.jpg
│   ├── raymundo-da-fonte.jpg
│   ├── frosty.jpg
│   ├── comvap.jpg
│   └── sao-geraldo.jpg
├── index.html                # Código-fonte principal (HTML, CSS e JS)
└── README.md                 # Documentação do projeto