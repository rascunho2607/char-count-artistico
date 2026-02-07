# Char Count Artístico

![Char Count Artístico](https://img.shields.io/badge/Char%20Count%20Artístico-Generative%20ASCII%20Cyber--Art-00f3ff)
![Version](https://img.shields.io/badge/Version-1.0.0-b967ff)
![License](https://img.shields.io/badge/License-MIT-00ff9d)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

Uma ferramenta de arte generativa que transforma texto em arte ASCII cibernética. Cada caractere se torna um pixel em uma tela digital única, criando visualizações artísticas procedurais.

## 🎨 Demonstração

![Screenshot da Aplicação](https://via.placeholder.com/800x400/0a0a12/00f3ff?text=Char+Count+Art%C3%ADstico+-+ASCII+Cyber-Art)

**Link da Demonstração:** [Clique aqui para ver ao vivo](https://seu-dominio.com/char-count-artistico)

## ✨ Características Principais

- **Arte ASCII Generativa**: Transforma texto em arte visual usando caracteres
- **Código de Cores Inteligente**:
  - Vogais: 🌟 **Coral Neon** (#ff4d8d)
  - Consoantes: 🔵 **Ciano** (#00f3ff)
  - Números: 💛 **Amarelo** (#ffeb3b)
  - Pontuação: 💚 **Verde** (#00ff9d)
  - Espaços: 💜 **Roxo** (#b967ff)
- **5 Modos de Geração**:
  - **Rosto**: Cria retratos baseados em caracteres
  - **Símbolo**: Gera formas geométricas simbólicas
  - **Padrão**: Arte procedural baseada em hash do texto
  - **Abstrato**: Composições artísticas livres
  - **Espiral**: Texto organizado em padrões espirais
- **Interface Cyberpunk**: Design futurista com efeitos visuais avançados
- **Estatísticas em Tempo Real**: Contagem de caracteres, palavras e linhas
- **Exemplos Prontos**: Textos de exemplo para teste rápido

## 🚀 Como Usar

### 1. Abrir a Aplicação
```bash
# Clone o repositório
git clone https://github.com/seu-usuario/char-count-artistico.git

# Abra o arquivo index.html no navegador
open index.html
# ou
xdg-open index.html
# ou simplesmente arraste o arquivo para o navegador
```

### 2. Inserir Texto
- Digite ou cole texto na área de entrada
- Observe as estatísticas atualizando em tempo real
- A arte é gerada automaticamente conforme você digita

### 3. Explorar Modos
- Clique nos botões de modo para diferentes estilos de arte:
  - **Face**: Para retratos estilizados
  - **Symbol**: Para formas geométricas
  - **Pattern**: Para padrões procedurais
  - **Abstract**: Para arte abstrata
  - **Spiral**: Para padrões espirais

### 4. Experimentar Exemplos
- Use os botões de exemplo para testar rapidamente:
  - **Short**: Texto curto
  - **Poem**: Poema digital
  - **Code**: Código de exemplo
  - **Lorem Ipsum**: Texto de preenchimento
  - **Clear**: Limpar texto

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: 
  - Grid e Flexbox para layout
  - Gradientes e animações CSS
  - Glassmorphism e efeitos de iluminação
  - Design responsivo
- **JavaScript (ES6+)**:
  - Manipulação DOM
  - Algoritmos de arte generativa
  - Animações e transições
  - Análise de texto em tempo real

## 🎯 Funcionalidades Técnicas

### Sistema de Colorização
```javascript
function colorizeChar(char) {
  if (/[aeiou]/i.test(char)) return '<span style="color:#ff4d8d">' + char + '</span>';
  if (/[a-z]/i.test(char)) return '<span style="color:#00f3ff">' + char + '</span>';
  if (/\d/.test(char)) return '<span style="color:#ffeb3b">' + char + '</span>';
  if (/[\W_]/.test(char)) return '<span style="color:#00ff9d">' + char + '</span>';
  return '<span style="color:#b967ff">' + char + '</span>';
}
```

### Algoritmos de Geração
- **Espiral**: Usa algoritmo de espiral quadrada
- **Face**: Baseado em geometria circular com elementos faciais
- **Padrão**: Utiliza funções trigonométricas para criar texturas
- **Símbolo**: Implementa fórmulas matemáticas para formas geométricas

### Efeitos Visuais
- **Bloom/Glow**: Efeitos de brilho com gradientes radiais
- **Scanlines**: Animações de linhas de varredura
- **Glassmorphism**: Painéis com efeito de vidro fosco
- **Grid Animado**: Fundo com grade animada
- **Textura de Ruído**: Overlay sutil de textura

## 📁 Estrutura do Projeto

```
char-count-artistico/
│
├── index.html          # Arquivo principal
├── README.md           # Este arquivo
│
├── assets/             # (Opcional) Para versões futuras
│   ├── images/
│   ├── fonts/
│   └── sounds/
│
└── docs/               # Documentação adicional
    ├── screenshots/
    ├── wireframes/
    └── technical/
```

## 🎨 Paleta de Cores

| Cor | Código | Uso |
|-----|--------|-----|
| Ciano Neon | `#00f3ff` | Consoantes, elementos UI |
| Coral | `#ff4d8d` | Vogais, destaques |
| Amarelo | `#ffeb3b` | Números, ícones |
| Verde | `#00ff9d` | Pontuação, botões |
| Roxo | `#b967ff` | Espaços, elementos secundários |
| Espaço Profundo | `#0a0a12` | Fundo principal |
| Azul Espacial | `#101025` | Painéis |
| Roxo do Vácuo | `#1a0a2a` | Gradiente de fundo |

## 🌐 Compatibilidade

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Mobile browsers

## 📱 Responsividade

A aplicação é totalmente responsiva e se adapta a:
- Desktop (1920px+)
- Laptop (1366px)
- Tablet (768px)
- Mobile (360px)

## 🔧 Personalização

### Modificar Cores
Edite as variáveis CSS no `:root`:
```css
:root {
  --neon-cyan: #00f3ff;
  --neon-coral: #ff4d8d;
  /* ... outras cores */
}
```

### Adicionar Novos Modos
1. Adicione um botão no HTML:
```html
<button class="control-btn" id="modeNovo">
  <i class="fas fa-icon"></i> Novo Modo
</button>
```

2. Implemente a função no JavaScript:
```javascript
function generateNovoArt(text, analysis) {
  // Sua lógica aqui
}
```

3. Adicione ao switch statement:
```javascript
case 'novo':
  art = generateNovoArt(text, analysis);
  break;
```

## 🚀 Roadmap Futuro

- [ ] Exportar arte como PNG/SVG
- [ ] Modo escuro/claro
- [ ] Mais algoritmos de geração
- [ ] Efeitos sonoros generativos
- [ ] Compartilhamento em redes sociais
- [ ] API para integração
- [ ] Animações 3D WebGL
- [ ] Modo colaborativo em tempo real

## 🤝 Contribuindo

Contribuições são bem-vindas! Siga estes passos:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

## 👥 Autores

- **Seu Nome** - *Desenvolvimento Inicial* - [@seu-usuario](https://github.com/seu-usuario)

## 🙏 Agradecimentos

- Inspirado por projetos de arte generativa e ASCII art
- Fontes utilizadas: [Font Awesome](https://fontawesome.com/)
- Gradientes e efeitos inspirados no design cyberpunk
- Comunidade de creative coding

## 📞 Suporte

Para suporte, abra uma issue no GitHub ou entre em contato via email.

---

<div align="center">
  
**Transforme texto em arte. Cada caractere conta.** ✨

[⭐️ Dê uma estrela no GitHub se você gostou!](#)

</div>

## 📸 Capturas de Tela

### Modo Face
![Modo Face](https://via.placeholder.com/400x300/0a0a12/ff4d8d?text=Face+Mode)

### Modo Espiral
![Modo Espiral](https://via.placeholder.com/400x300/0a0a12/00f3ff?text=Spiral+Mode)

### Interface Desktop
![Interface Completa](https://via.placeholder.com/800x500/0a0a12/00ff9d?text=Full+Interface)

## 🎥 Demonstração em Vídeo

[![Assista a demonstração](https://img.youtube.com/vi/VIDEO_ID/0.jpg)](https://youtu.be/VIDEO_ID)

*Clique na imagem para assistir à demonstração em vídeo*

---

**Char Count Artístico** - Onde cada caractere se torna uma obra de arte.
