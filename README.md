# 🌍 Jornada Viagens - Website Responsivo

**Um website completo para uma agência de viagens, desenvolvido com foco em design responsivo durante a Formação Front-end da Alura.**

![Captura de Tela do Site Jornada Viagens](https://imgur.com/SUbLQvT.png) <!-- 📌 SUBSTITUA pelo link real da sua screenshot! -->

## 📋 Sobre o Projeto
O **Jornada Viagens** é um website funcional para uma agência de viagens fictícia, criado como projeto prático do curso de **CSS Responsivo** da Alura. O principal objetivo foi dominar as técnicas de **responsividade** para criar uma experiência de usuário perfeita em todos os dispositivos, desde smartphones até desktops.

**Contexto do Desenvolvimento:** Este projeto foi desenvolvido durante a formação Front-end da Alura, seguindo as melhores práticas de desenvolvimento web moderno.

## 🎯 Objetivos de Aprendizado
- Implementar **layouts responsivos** com Media Queries
- Dominar **unidades de medida relativas** (%, rem, vw/vh)
- Criar **grids e flexbox** adaptáveis
- Desenvolver **navegação mobile-first**
- Aplicar **imagens e elementos flexíveis**
- Garantir **acessibilidade** e **performance**

## 🛠️ Tecnologias Utilizadas
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)

## ✨ Funcionalidades Implementadas
### 🌐 **Responsividade Total**
- **Mobile-First Approach:** Design iniciado para dispositivos móveis
- **Breakpoints Estratégicos:** Adaptação para tablet (768px) e desktop (1024px+)
- **Imagens Responsivas:** Otimizadas para diferentes resoluções e densidades de tela
- **Tipografia Flexível:** Escalas de fontes adaptativas usando `rem` e `clamp()`

### 🎨 **Componentes do Website**
- **Header/Navbar:** Menu de navegação que se transforma em hamburger menu no mobile
- **Hero Section:** Banner principal com call-to-action impactante
- **Catálogo de Destinos:** Grid de cards de viagens que se reorganiza por dispositivo
- **Formulário de Contato:** Layout adaptativo com validação básica
- **Footer Informativo:** Multi-coluna no desktop, single-coluna no mobile

### ⚡ **Recursos Técnicos**
- **CSS Grid & Flexbox:** Para layouts complexos e alinhamento preciso
- **Variáveis CSS:** Sistema de cores e espaçamento consistente
- **Transições Suaves:** Animações para interações do usuário
- **Meta Tags Viewport:** Configuração adequada para dispositivos móveis

## 📁 Estrutura do Projeto
jornada-viagens/
├── index.html # Página principal
├── style.css # Estilos principais (responsivo)
├── script.js # Interatividade (menu mobile, etc.)
├── README.md # Esta documentação
└── assets/
├── images/ # Imagens otimizadas (webp/jpg)
│ ├── hero-banner.jpg
│ ├── destination-1.jpg
│ └── ...
├── icons/ # Ícones SVG
└── fonts/ # Fontes personalizadas (se houver)

text

## 🚀 Como Executar Localmente
1. **Clone o repositório:**
   ```bash
   git clone https://github.com/MalconB52/jornada-viagens.git
Acesse a pasta do projeto:

bash
cd jornada-viagens
Abra no navegador:

Método 1: Abra o arquivo index.html diretamente

Método 2: Use uma extensão Live Server (VS Code)

🌐 Deploy e Demonstração
🔗 Site ao Vivo: https://jornada-viagens.vercel.app <!-- 📌 SUBSTITUA pelo seu link do Vercel! -->

📂 Código Fonte: https://github.com/MalconB52/jornada-viagens

📱 Teste de Responsividade
Para ver a responsividade em ação:

Acesse o site pelo link acima

Abra as Ferramentas do Desenvolvedor (F12)

Use o toggle de dispositivo (Ctrl+Shift+M)

Teste em resoluções:

Mobile: 375px - 480px

Tablet: 768px - 1024px

Desktop: 1200px+

📚 Conceitos de Responsividade Aplicados
Conceito	Implementação no Projeto
Mobile-First	CSS escrito primeiro para mobile, depois media queries para telas maiores
Media Queries	@media (min-width: 768px) e @media (min-width: 1024px)
Unidades Flexíveis	Uso de rem, %, vw, vh em vez de pixels fixos
Flexbox/Grid	Layouts que se reorganizam automaticamente
Imagens Adaptativas	srcset e sizes ou CSS max-width: 100%
🔧 Personalização
Para modificar este projeto:

Cores: Edite as variáveis CSS no topo do style.css

Conteúdo: Modifique o texto em index.html

Imagens: Substitua as imagens na pasta assets/images/

Breakpoints: Ajuste os valores nas media queries conforme necessário

🎓 Aprendizados do Curso
Este projeto consolidou:

A mentalidade mobile-first no desenvolvimento

Como planejar breakpoints baseados no conteúdo

Técnicas de otimização de imagens para web

Padrões de design responsivos comuns

Debugging de layouts em múltiplos dispositivos

📈 Próximos Passos (Melhorias Futuras)
Adicionar modo escuro/claro

Implementar carrossel de destinos com JavaScript

Adicionar filtros de busca por tipo de viagem

Integrar com API de câmbio para mostrar preços

Adicionar mais páginas (sobre, blog, depoimentos)

Otimizar performance com lazy loading de imagens

🤝 Contribuindo
Este é um projeto de estudo, mas sugestões são bem-vindas:

Faça um Fork do projeto

Crie uma branch (git checkout -b feature/nova-feature)

Commit suas mudanças (git commit -m 'Adiciona nova feature')

Push para a branch (git push origin feature/nova-feature)

Abra um Pull Request

📄 Licença
Este projeto foi desenvolvido para fins educacionais como parte da Formação Front-end da Alura.

👨💻 Autor
Malcon Barbosa - LinkedIn | GitHub

Desenvolvedor Front-end em formação, focado em criar interfaces responsivas e acessíveis.

⭐ Se este projeto te ajudou, considere dar uma estrela no repositório!
