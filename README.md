# 🌐 Site Institucional — Aliança de Pequenos

Site institucional desenvolvido para a **Aliança de Pequenos**, organização missionária sediada em Dourados/MS, Brasil. O projeto foi construído do zero, desde o planejamento da arquitetura até o deploy em produção.

🔗 **[Acesse o site ao vivo](https://site-alianca-de-pequenos.vercel.app/)**

---

## 📸 Preview

![Preview do Site](./imgs/forja/background-apresentacao-forja.png)

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — estrutura semântica e acessível
- **CSS3** — estilização completa com recursos modernos
  - CSS Custom Properties (variáveis)
  - Flexbox e CSS Grid
  - Design responsivo (mobile, tablet e desktop)
  - Animações e transições com `transition` e `transform`
- **Font Awesome 6** — ícones vetoriais
- **Google Fonts** — tipografias Bebas Neue e Montserrat
- **Vercel** — deploy contínuo em produção

---

## 📁 Estrutura do Projeto

```
alianca-de-pequenos/
├── index.html                  # Página principal
├── styles/
│   ├── style.css               # Estilos da página principal
│   └── pages.css               # Estilos compartilhados pelas páginas internas
├── pages/
│   ├── sobre_nos.html          # Quem somos, missão e valores
│   ├── projetos.html           # Projetos e iniciativas
│   ├── avivamento_now.html     # Canal de conteúdo e episódios
│   └── apoie.html              # Formas de apoio e doação
└── imgs/                       # Imagens e assets do projeto
```

---

## 📄 Páginas

| Página | Descrição |
|---|---|
| `index.html` | Hero da FORJA, Escola FORJA, Cursos, Oficinas, Estatísticas e Formulário |
| `sobre_nos.html` | História da organização, missão, valores e CTA |
| `projetos.html` | Grade de projetos ativos com descrições e categorias |
| `avivamento_now.html` | Canal de conteúdo com episódios em destaque e links para YouTube |
| `apoie.html` | Opções de doação via PIX, transferência bancária e parceria mensal |

---

## ✨ Funcionalidades

- Navbar fixa com efeito de sublinhado animado no hover
- Design responsivo com breakpoints para mobile (480px), tablet (768px) e desktop (1024px+)
- Imagens com `object-fit: cover` e gradiente de fallback para estabilidade de layout
- Cards interativos com animação de elevação no hover
- Formulário de contato estilizado no footer
- Links externos com `target="_blank"` para redes sociais e plataformas parceiras
- Paleta de cores consistente via CSS Variables em todo o projeto

---

## 🚀 Como Rodar Localmente

Não há dependências ou build necessário. Basta clonar o repositório e abrir o arquivo no navegador:

```bash
git clone https://github.com/seu-usuario/alianca-de-pequenos.git
cd alianca-de-pequenos
```

Abra o `index.html` diretamente no navegador ou use a extensão **Live Server** no VS Code para melhor experiência de desenvolvimento.

---

## 📱 Responsividade

O layout foi desenvolvido com abordagem **mobile-first**, adaptando-se a três breakpoints principais:

- **Mobile** — até 480px: colunas únicas, navbar empilhada
- **Tablet** — até 768px: grid de 2 colunas, footer reorganizado
- **Desktop** — 1024px+: layout completo com múltiplas colunas

---

## 🎨 Identidade Visual

| Elemento | Valor |
|---|---|
| Cor Primária | `#0F3057` (azul escuro) |
| Cor Secundária | `#145374` (azul médio) |
| Cor de Destaque | `#9E2A2B` (vermelho) |
| Fonte Display | Bebas Neue |
| Fonte Corpo | Montserrat |

---

## 👤 Autor

**Eduardo Panage Avila**
Desenvolvedor Full Stack

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/seu-perfil)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/seu-usuario)

---

## 📝 Licença

Este projeto foi desenvolvido para uso exclusivo da organização **Aliança de Pequenos**. Todos os direitos reservados.
