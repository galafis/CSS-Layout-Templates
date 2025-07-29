# CSS Layout Templates

![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

Coleção de templates de layout responsivos implementados com CSS moderno, incluindo Flexbox, CSS Grid e técnicas avançadas de posicionamento para criar interfaces web profissionais.

## 🎯 Demonstração

Este projeto oferece uma base sólida para implementação de layouts responsivos usando as melhores práticas de CSS moderno.

## ✨ Características

- **Layouts Responsivos**: Adaptáveis a diferentes dispositivos
- **CSS Grid & Flexbox**: Técnicas modernas de layout
- **Mobile-First**: Abordagem responsiva otimizada
- **Cross-Browser**: Compatibilidade ampla
- **Semântico**: HTML estruturado e acessível

## 🛠️ Tecnologias

- **HTML5**: Estrutura semântica moderna
- **CSS3**: Grid, Flexbox, Media Queries
- **CSS Variables**: Sistema de design consistente

## 📁 Estrutura do Projeto

```
CSS-Layout-Templates/
├── index.html          # Template principal
├── styles.css          # Estilos e layouts responsivos
├── README.md           # Documentação
├── LICENSE             # Licença MIT
└── .gitignore          # Arquivos ignorados pelo Git
```

## 🚀 Como Usar

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/galafis/CSS-Layout-Templates.git
cd CSS-Layout-Templates
```

2. Abra o arquivo `index.html` no navegador:
```bash
# Usando Python
python -m http.server 8000

# Usando Node.js
npx serve .
```

### Tipos de Layout Disponíveis

#### 1. Layout com CSS Grid
```css
.grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    padding: 20px;
}
```

#### 2. Layout Flexbox
```css
.flex-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: center;
}
```

#### 3. Layout Responsivo com Media Queries
```css
/* Mobile First */
.container {
    width: 100%;
    padding: 10px;
}

/* Tablet */
@media (min-width: 768px) {
    .container {
        max-width: 750px;
        margin: 0 auto;
    }
}

/* Desktop */
@media (min-width: 1024px) {
    .container {
        max-width: 1200px;
    }
}
```

## 📐 Padrões de Layout Suportados

- **Holy Grail Layout**: Header, footer, sidebar e conteúdo principal
- **Card Layout**: Grid de cards responsivos
- **Sidebar Layout**: Layout com barra lateral fixa ou colapsável
- **Hero Section**: Seções de destaque com call-to-action
- **Navigation Layouts**: Menus responsivos e navegação

## 🎨 Personalização

Modifique as variáveis CSS para personalizar o design:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --container-max-width: 1200px;
    --grid-gap: 20px;
    --border-radius: 8px;
}
```

## 📱 Breakpoints Responsivos

```css
/* Mobile: 320px - 767px */
/* Tablet: 768px - 1023px */
/* Desktop: 1024px+ */
/* Large Desktop: 1440px+ */
```

## 🔧 Extensões Possíveis

- [ ] Mais variações de grid layouts
- [ ] Templates para e-commerce
- [ ] Layouts para dashboards
- [ ] Componentes de navegação avançados
- [ ] Layouts para blogs e portfólios
- [ ] Integração com frameworks CSS

## 🤝 Contribuindo

Contribuições são bem-vindas! Para adicionar novos templates:

1. Fork o projeto
2. Crie uma branch para seu template (`git checkout -b feature/NovoTemplate`)
3. Commit suas mudanças (`git commit -m 'Adiciona novo template de layout'`)
4. Push para a branch (`git push origin feature/NovoTemplate`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Autor

**Gabriel Demetrios Lafis**

- GitHub: [@galafis](https://github.com/galafis)
- Email: gabrieldemetrios@gmail.com

---

⭐ Se este projeto foi útil, considere deixar uma estrela!

