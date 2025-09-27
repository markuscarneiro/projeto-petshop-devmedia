# 🐾 Pet Boutique - Website Institucional

Um website moderno e responsivo para uma pet shop boutique, focado em elegância e experiência do usuário.

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Seções do Site](#seções-do-site)
- [Características Técnicas](#características-técnicas)
- [Paleta de Cores](#paleta-de-cores)
- [Fontes e Tipografia](#fontes-e-tipografia)
- [Responsividade](#responsividade)
- [Como Usar](#como-usar)
- [Estrutura de Arquivos](#estrutura-de-arquivos)

## 🎯 Sobre o Projeto

O **Pet Boutique** é um website institucional desenvolvido para uma loja especializada em produtos e serviços premium para cães e gatos. O site foi projetado para transmitir elegância, confiança e cuidado com os animais de estimação.

### Objetivos:
- Apresentar os serviços da empresa de forma atrativa
- Facilitar o contato com clientes via WhatsApp
- Mostrar as marcas parceiras e credibilidade
- Fornecer informações de localização
- Criar uma experiência visual impactante

## 🛠 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica e acessível
- **CSS3**: Estilização avançada com Flexbox e Grid
- **Google Maps**: Integração de mapa de localização
- **WhatsApp API**: Links diretos para contato
- **Fontes Web**: Typography responsiva

## 🏗 Estrutura do Projeto

```
Projeto/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── README.md          # Documentação
└── ../img/            # Pasta de imagens
    ├── banner-topo.jpg    # Imagem hero do cachorro
    ├── patas.png          # Ícone das patas
    ├── banho.png          # Imagem do serviço de banho
    ├── creche.png         # Imagem da creche
    ├── dog-walker.png     # Imagem do dog walker
    ├── loja.png           # Imagem da loja
    ├── veterinario.png    # Imagem do veterinário
    ├── redes-sociais/     # Ícones das redes sociais
    │   ├── facebook-svgrepo-com.png
    │   ├── instagram-svgrepo-com.png
    │   └── whatsapp-svgrepo-com.png
    └── marcas/           # Logos das marcas parceiras
        ├── AlfaPet.png
        ├── BichinhoChic.png
        ├── Boehringer.png
        └── ... (outras marcas)
```

## 📑 Seções do Site

### 1. **Banner Hero** (`.secao_banner`)
- **Função**: Primeira impressão impactante
- **Elementos**: 
  - Imagem de fundo em tela cheia (cachorro)
  - Logo da empresa no canto superior esquerdo
  - Call-to-action centralizado
  - Botão direto para WhatsApp
- **Técnica**: `height: 100vh` para ocupar toda a tela

### 2. **Seção de Serviços** (`.secao_servicos`)
- **Função**: Apresentar os serviços oferecidos
- **Elementos**:
  - Lista de serviços com descrições
  - Galeria de imagens dos serviços
- **Técnica**: Layout centrado com `max-width: 800px`

### 3. **Faixas Promocionais** (`.secao_faixas`)
- **Função**: Reforçar a marca e engajamento
- **Elementos**:
  - Frases promocionais
  - Links para redes sociais
- **Técnica**: Fundo roxo com contraste branco

### 4. **Marcas Parceiras** (`.secao_marcas`)
- **Função**: Mostrar credibilidade e parcerias
- **Elementos**: Grid de logos das marcas
- **Técnica**: Imagens uniformes (148x148px)

### 5. **Localização** (`.secao_mapa`)
- **Função**: Mostrar localização física
- **Elementos**: Google Maps integrado
- **Técnica**: Iframe responsivo

### 6. **Rodapé** (`.secao_rodape`)
- **Função**: Informações finais e créditos
- **Elementos**: Créditos do desenvolvedor

## 🎨 Características Técnicas

### Layout e Estrutura:
- **Box Model**: `box-sizing: border-box` para cálculos precisos
- **Container Padrão**: `.geral` com padding `120px 80px`
- **Centralização**: `margin: 0 auto` e `max-width` para responsividade
- **Reset CSS**: Remoção de margens e paddings padrão

### Efeitos Visuais:
- **Sombras**: `box-shadow` para profundidade
- **Bordas**: `border-radius` para suavidade
- **Transparências**: `rgba()` para sobreposições
- **Background**: `background-size: cover` para imagens responsivas

### Interatividade:
- **Links de Contato**: Integração direta com WhatsApp
- **Redes Sociais**: Links para Facebook e Instagram
- **Navegação**: Âncoras internas (se implementadas)

## 🎨 Paleta de Cores

| Cor | Hexadecimal | Uso |
|-----|-------------|-----|
| **Roxo Principal** | `#3c184e` | Marca, títulos, botões |
| **Branco** | `#ffffff` | Texto em fundos escuros |
| **Branco Transparente** | `#ffffffc4` | Sobreposições (77% opacidade) |
| **Preto Suave** | `#0000005c` | Sombras (36% opacidade) |

## 📝 Fontes e Tipografia

- **Fonte Principal**: `sans-serif` (sistema)
- **Hierarquia**:
  - H1 (Banner): 60px, extra-bold (800)
  - H3 (Títulos de seção): 36px
  - Logo: 30px
  - Texto promocional: 40px
  - Texto padrão: 20px
  - Créditos: 12px

## 📱 Responsividade

### Técnicas Implementadas:
- **Viewport Meta**: `width=device-width, initial-scale=1.0`
- **Larguras Máximas**: `max-width` em containers
- **Unidades Relativas**: `vh`, `%`, `em`
- **Box-sizing**: Border-box para cálculos precisos

### Breakpoints Sugeridos (para futuras melhorias):
- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px  
- **Mobile**: < 768px

## 🚀 Como Usar

### 1. **Estrutura de Arquivos**:
```bash
# Certifique-se que a estrutura está assim:
Projeto/
├── index.html
├── styles.css
└── ../img/ (pasta no nível anterior)
```

### 2. **Servidor Local**:
```bash
# Use um servidor local (Live Server, Python, etc.)
# Não abra diretamente pelo explorador de arquivos
```

### 3. **Personalização**:
- **Cores**: Altere as variáveis de cor no início do CSS
- **Conteúdo**: Edite os textos no HTML
- **Imagens**: Substitua as imagens mantendo os nomes
- **Contato**: Altere o número do WhatsApp nos links

## 📂 Estrutura de Arquivos Detalhada

### **HTML** (`index.html`):
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <!-- Meta tags e configurações -->
    <!-- Link para CSS -->
</head>
<body>
    <!-- Seção Banner -->
    <!-- Seção Serviços -->
    <!-- Faixas Promocionais -->
    <!-- Marcas Parceiras -->
    <!-- Localização -->
    <!-- Rodapé -->
</body>
</html>
```

### **CSS** (`styles.css`):
```css
/* Reset e Estilos Globais */
/* Seção Banner Principal */
/* Seção de Serviços */
/* Seções Promocionais */
/* Seção de Marcas */
/* Seção de Localização */
/* Rodapé */
```

## 🔧 Configurações Importantes

### **WhatsApp Integration**:
```html
<!-- Link direto para WhatsApp -->
<a href="https://wa.me/5511948133124" target="_blank">
```

### **Google Maps**:
```html
<!-- Iframe do mapa incorporado -->
<iframe src="https://www.google.com/maps/embed?pb=..." 
        width="600" height="450">
</iframe>
```

### **Caminhos das Imagens**:
```css
/* CSS - Background */
background-image: url("../img/banner-topo.jpg");

/* HTML - Imagens */
<img src="../img/patas.png" alt="Patas">
```

## 📈 Melhorias Futuras Sugeridas

1. **Responsividade Avançada**: Media queries para mobile
2. **Animações**: CSS animations e transitions
3. **SEO**: Meta descriptions, structured data
4. **Performance**: Lazy loading, otimização de imagens
5. **Acessibilidade**: ARIA labels, contraste melhorado
6. **JavaScript**: Interações dinâmicas
7. **PWA**: Service workers, manifest

## 👨‍💻 Créditos

- **Desenvolvido por**: @CarvaDevWeb
- **Projeto**: Pet Boutique Website
- **Tecnologias**: HTML5, CSS3
- **Ano**: 2025

---

*Este projeto foi desenvolvido com foco em boas práticas de desenvolvimento web, código limpo e experiência do usuário.*