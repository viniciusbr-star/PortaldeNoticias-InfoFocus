# 📰 InfoFocus - Portal de Notícias

![Status do Projeto](https://img.shields.io/badge/Status-Sprint%203%20Concluída-success?style=for-the-badge)<br>
![Responsividade](https://img.shields.io/badge/Design-Responsivo-blueviolet?style=for-the-badge)<br>
![HTML5](https://img.shields.io/badge/HTML5-Semântico-orange?style=for-the-badge)<br>
![CSS3](https://img.shields.io/badge/CSS3-Moderno-blue?style=for-the-badge)<br>

> **InfoFocus** é um portal de notícias moderno, desenvolvido com foco em identidade visual consistente (baseada em Figma), semântica HTML e experiência de usuário fluida em dispositivos móveis e desktop.

---



| Requisito | Status | Detalhes da Implementação |
| :--- | :---: | :--- |
| **Identidade Visual** | ✅ | Réplica fiel do design Figma (Cores `#e48585`, tipografia limpa). |
| **Responsividade** | ✅ | Layouts adaptáveis via Flexbox e Grid para Mobile, Tablet e Desktop. |
| **Menu Interativo** | ✅ | Implementação de Dropdown com animação suave (Fade-in/Fade-out). |
| **Código Limpo** | ✅ | Uso de Variáveis CSS (`:root`) e remoção de redundâncias. |
| **Semântica** | ✅ | Estrutura correta com `<header>`, `<nav>`, `<main>`, `<article>`, `<footer>`. |

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica do conteúdo.
* **CSS3:** Estilização avançada sem frameworks pesados.
    * *Flexbox & Grid Layout*
    * *CSS Variables (Custom Properties)*
    * *Keyframes Animations*
    * *Media Queries*
* **Ícones:** Bootstrap Icons / FontAwesome.

---

## 🎨 Design System

Para garantir consistência em todas as páginas (`Home`, `Notícia`, `Contato`), defini um sistema visual rigoroso.

### 🌈 Paleta de Cores

| Cor | Hex | Uso | Preview |
| :--- | :--- | :--- | :---: |
| **Rosa Focus** | `#e48585` | Botões, Destaques, Links, Faixas | ![#e48585](https://via.placeholder.com/15/e48585/000000?text=+) |
| **Dark Text** | `#333333` | Títulos e Textos principais | ![#333333](https://via.placeholder.com/15/333333/000000?text=+) |
| **White Pure** | `#ffffff` | Fundo das páginas e Cards | ![#ffffff](https://via.placeholder.com/15/ffffff/000000?text=+) |
| **Soft Gray** | `#f4f4f4` | Rodapés e Fundos secundários | ![#f4f4f4](https://via.placeholder.com/15/f4f4f4/000000?text=+) |

---



## 📂 Estrutura do Projeto

O projeto foi organizado para facilitar a manutenção e escalabilidade:

```text
InfoFocus/
│
├── index.html        # Página Inicial (Destaques, Grid de Notícias, Vídeo)
├── noticia.html      # Página de Detalhe (Artigo completo, Layout colunas)
├── contato.html      # Página de Contato (Formulário estilizado e Infos)
│
├── css/
│   ├── style.css     # Estilos da Home e Reset Global
│   ├── noticia.css   # Estilos específicos da página de Artigo
│   └── contato.css   # Estilos específicos da página de Contato
│
└── img/              # Imagens utilizadas no projeto
```

---

## 📋 Visão Geral
O InfoFocus é um portal de notícias web moderno, desenvolvido com foco na experiência do usuário (UX) e na fidelidade visual a um design system pré-estabelecido (protótipo Figma). O projeto prioriza a legibilidade, a hierarquia visual clara e a adaptabilidade a diferentes dispositivos (responsividade).

O InfoFocus atende aos requisitos de um site institucional moderno, entregando uma interface polida, consistente e totalmente funcional em dispositivos móveis e desktops, respeitando rigorosamente o layout proposto co responsividade.