💼 TalentHive — Landing Page Responsiva (Mobile First)

Projeto desenvolvido para a atividade prática de Front-End com foco em Mobile First, HTML5, CSS3 e uso de variáveis CSS.

O layout replica o design proposto no Figma, simulando uma landing page moderna para um aplicativo de busca de empregos.

🎯 Objetivo da Atividade

Construir o front-end fiel ao design fornecido, aplicando:

✅ Abordagem Mobile First

✅ Layout Responsivo (Mobile → Tablet → Desktop)

✅ Variáveis CSS

✅ Estrutura semântica

✅ Boas práticas de organização

🖌 Sobre o Design

O layout representa uma landing page de aplicativo chamada TalentHive, contendo:

Hero Section com destaque principal

Mockups do aplicativo

Seção explicativa com vídeo

Seção de benefícios

Footer com CTA (Call To Action)

A estrutura foi desenvolvida pensando primeiro na versão mobile e depois expandida para telas maiores.

🧠 Conceitos Aplicados
📱 Mobile First

O projeto foi iniciado pela versão mobile e adaptado para telas maiores utilizando media queries baseadas em min-width.

Exemplo:

@media (min-width: 768px) {
  /* ajustes para tablet */
}

@media (min-width: 1024px) {
  /* ajustes para desktop */
}
🎨 Variáveis CSS

Para manter consistência visual e facilitar manutenção, foram utilizadas variáveis no :root:

:root {
  --color-primary: #4f7cff;
  --color-secondary: #f5f5f5;
  --color-dark: #111111;
  --color-light: #ffffff;

  --font-primary: 'Inter', sans-serif;

  --spacing-sm: 0.5rem;
  --spacing-md: 1rem;
  --spacing-lg: 2rem;
}
🏗 Estrutura do Projeto
📁 talenthive
 ├── index.html
 ├── style.css
 ├── 📁 assets
 │     ├── images
 │     └── icons
 └── README.md
🛠 Tecnologias Utilizadas

HTML5

CSS3

Flexbox

CSS Grid

Media Queries

Google Fonts

📱 Responsividade

O layout foi testado nos seguintes breakpoints:

📲 375px (Mobile)

📟 768px (Tablet)

💻 1024px+ (Desktop)

O comportamento esperado:

Mobile → Layout em coluna

Tablet → Ajustes intermediários

Desktop → Layout em múltiplas colunas

🚀 Como Executar

Baixe ou clone o repositório:

git clone https://github.com/seu-usuario/seu-repositorio.git

Abra o arquivo index.html no navegador.

📦 Forma de Entrega

Arquivo .zip
ou

Link do repositório no GitHub

👨‍💻 Autor

Junior Gabriel Antunes de Souza

GitHub:
https://github.com/juniorAntunes910

✅ Status do Projeto

✔️ Layout responsivo implementado
✔️ Mobile First aplicado corretamente
✔️ Variáveis CSS organizadas
✔️ Estrutura limpa e semântica
