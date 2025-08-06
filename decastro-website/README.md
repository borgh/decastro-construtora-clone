# De Castro Construtora - Clone do Site

Este é um clone moderno e aprimorado do site da De Castro Construtora, desenvolvido com React, Tailwind CSS e recursos modernos de web development.

## 🚀 Características

### ✨ Recursos Implementados
- **Design Responsivo**: Totalmente adaptado para desktop, tablet e mobile
- **Animações Modernas**: Animações de scroll e transições suaves
- **Lazy Loading**: Carregamento otimizado de imagens
- **PWA Ready**: Progressive Web App com manifest e service worker
- **SEO Otimizado**: Meta tags completas para melhor indexação
- **Performance**: Otimizado para velocidade e experiência do usuário
- **Acessibilidade**: Seguindo padrões WCAG para inclusão

### 🎨 Melhorias Visuais
- Efeitos parallax no hero section
- Hover effects avançados nos cards
- Animações de entrada por seção
- Botões com micro-interações
- Gradientes e sombras modernas
- Tipografia otimizada

### 📱 Funcionalidades
- Menu responsivo com hamburger
- WhatsApp floating button
- Newsletter subscription
- Cards interativos de empreendimentos
- Seção de notícias com categorias
- Footer completo com informações de contato

## 🛠️ Tecnologias Utilizadas

- **React 18**: Framework principal
- **Vite**: Build tool e dev server
- **Tailwind CSS**: Framework de CSS utilitário
- **Shadcn/UI**: Componentes de interface
- **Lucide React**: Ícones modernos
- **Framer Motion**: Animações (preparado para uso)

## 📁 Estrutura do Projeto

```
decastro-website/
├── public/
│   ├── manifest.json          # PWA manifest
│   └── favicon.ico
├── src/
│   ├── assets/               # Imagens e recursos
│   ├── components/           # Componentes React
│   │   ├── ui/              # Componentes base (shadcn/ui)
│   │   ├── Header.jsx       # Cabeçalho e navegação
│   │   ├── HeroSection.jsx  # Seção principal
│   │   ├── EmpreendimentosSection.jsx
│   │   ├── InstitucionalSection.jsx
│   │   ├── VilaVelhaSection.jsx
│   │   ├── NoticiasSection.jsx
│   │   ├── Footer.jsx
│   │   ├── AnimatedSection.jsx  # Componente de animações
│   │   └── LazyImage.jsx    # Componente de lazy loading
│   ├── hooks/               # Custom hooks
│   │   └── useScrollAnimation.js
│   ├── App.jsx             # Componente principal
│   ├── App.css             # Estilos customizados
│   └── main.jsx            # Entry point
├── package.json
└── README.md
```

## 🚀 Como Executar

### Pré-requisitos
- Node.js 18+ 
- pnpm (recomendado) ou npm

### Instalação e Execução
```bash
# Clonar o repositório
git clone [url-do-repositorio]

# Navegar para o diretório
cd decastro-website

# Instalar dependências
pnpm install

# Executar em modo desenvolvimento
pnpm run dev

# Build para produção
pnpm run build

# Preview da build de produção
pnpm run preview
```

O site estará disponível em `http://localhost:5173`

## 📊 Performance

### Otimizações Implementadas
- **Lazy Loading**: Imagens carregadas apenas quando necessário
- **Code Splitting**: Componentes carregados sob demanda
- **Image Optimization**: Formatos WebP para melhor compressão
- **CSS Optimization**: Tailwind CSS com purge automático
- **Bundle Optimization**: Vite com otimizações automáticas

### Métricas Esperadas
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1
- **First Input Delay**: < 100ms

## 🎯 SEO e Acessibilidade

### SEO
- Meta tags completas (title, description, keywords)
- Open Graph tags para redes sociais
- Twitter Card tags
- Structured data (preparado para implementação)
- Sitemap XML (preparado para geração)

### Acessibilidade
- Navegação por teclado
- ARIA labels em elementos interativos
- Contraste adequado de cores
- Textos alternativos em imagens
- Estrutura semântica HTML5

## 🔧 Customização

### Cores do Tema
As cores principais podem ser alteradas no arquivo `src/App.css`:
- **Azul Principal**: `#1e3a8a`
- **Verde Destaque**: `#059669`
- **Laranja**: `#ea580c`
- **Roxo**: `#7c3aed`

### Adicionando Novos Componentes
1. Criar o componente em `src/components/`
2. Importar no `App.jsx`
3. Adicionar animações usando `AnimatedSection`
4. Implementar lazy loading para imagens com `LazyImage`

## 📱 PWA Features

O site está configurado como Progressive Web App:
- **Manifest**: Configurado para instalação
- **Service Worker**: Preparado para cache offline
- **App Icons**: Ícones para diferentes dispositivos
- **Splash Screen**: Tela de carregamento personalizada

## 🚀 Deploy

### Opções de Deploy
1. **Vercel**: `vercel --prod`
2. **Netlify**: Conectar repositório Git
3. **GitHub Pages**: Build e deploy automático
4. **Servidor próprio**: Upload da pasta `dist/`

### Variáveis de Ambiente
Criar arquivo `.env` para configurações:
```env
VITE_API_URL=https://api.exemplo.com
VITE_GOOGLE_ANALYTICS_ID=GA_TRACKING_ID
```

## 🤝 Contribuição

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto é uma demonstração educacional baseada no site original da De Castro Construtora.

## 📞 Contato

Para dúvidas sobre o projeto:
- Email: contato@exemplo.com
- LinkedIn: [Seu LinkedIn]

---

**Desenvolvido com ❤️ usando React e Tailwind CSS**

