#  Bitcoin Creative - Design System

Guia de estilo visual para projetos do Bitcoin Creative.

---

##  Paleta de Cores

### Cores Primárias

| Cor | Hex | RGB | Uso |
|-----|-----|-----|-----|
|  **Bitcoin Orange** | `#F7931A` | `rgb(247, 147, 26)` | Cor principal, CTAs, destaques |
|  **Bitcoin Black** | `#000000` | `rgb(0, 0, 0)` | Textos, fundos escuros |
|  **Pure White** | `#FFFFFF` | `rgb(255, 255, 255)` | Fundos claros, textos em dark mode |

### Cores Secundárias

| Cor | Hex | RGB | Uso |
|-----|-----|-----|-----|
|  **Dark Gray** | `#4D4D4D` | `rgb(77, 77, 77)` | Textos secundários |
|  **Light Gray** | `#E5E5E5` | `rgb(229, 229, 229)` | Bordas, divisores |
|  **Near Black** | `#1A1A1A` | `rgb(26, 26, 26)` | Fundos de cards |

### Cores de Apoio

| Cor | Hex | Uso |
|-----|-----|-----|
|  **Success Green** | `#10B981` | Confirmações, sucesso |
|  **Error Red** | `#EF4444` | Erros, alertas |
|  **Info Blue** | `#3B82F6` | Links, informações |

---

##  Tipografia

### Fontes Recomendadas

| Fonte | Uso | Alternativa |
|-------|-----|-------------|
| **Montserrat** | Títulos, headlines | Inter, Poppins |
| **Inter** | Corpo de texto | Roboto, Open Sans |
| **JetBrains Mono** | Código, dados técnicos | Fira Code, Source Code Pro |
| **VT323** | Estilo retro/pixel | Press Start 2P |

### Hierarquia Tipográfica

```css
/* Títulos */
h1 { font-size: 48px; font-weight: 700; line-height: 1.2; }
h2 { font-size: 36px; font-weight: 600; line-height: 1.3; }
h3 { font-size: 24px; font-weight: 600; line-height: 1.4; }
h4 { font-size: 20px; font-weight: 500; line-height: 1.4; }

/* Corpo */
body { font-size: 16px; font-weight: 400; line-height: 1.6; }
small { font-size: 14px; font-weight: 400; line-height: 1.5; }
```

---

##  Espaçamento

| Token | Valor | Uso |
|-------|-------|-----|
| `space-xs` | 4px | Micro espaçamentos |
| `space-sm` | 8px | Espaçamento entre elementos relacionados |
| `space-md` | 16px | Espaçamento padrão |
| `space-lg` | 24px | Separação de seções |
| `space-xl` | 32px | Espaçamento de blocos |
| `space-2xl` | 48px | Separação de seções principais |
| `space-3xl` | 64px | Margens de página |

---

##  Componentes

### Botões

```css
/* Botão Primário */
.btn-primary {
    background: #F7931A;
    color: #000000;
    padding: 12px 24px;
    border-radius: 8px;
    font-weight: 600;
}

.btn-primary:hover {
    background: #E8850F;
}

/* Botão Secundário */
.btn-secondary {
    background: transparent;
    color: #F7931A;
    border: 2px solid #F7931A;
    padding: 12px 24px;
    border-radius: 8px;
}
```

### Cards

```css
.card {
    background: #1A1A1A;
    border-radius: 16px;
    padding: 24px;
    border: 1px solid #4D4D4D;
}

.card:hover {
    border-color: #F7931A;
}
```

---

##  Ícones e Símbolos

```
  - Símbolo Bitcoin (U+20BF)
 - Lightning Network
 - Segurança/Custódia
 - Crescimento/Adoção
```

### Recursos
- [Bitcoin Icons](https://bitcoinicons.com/)
- [Heroicons](https://heroicons.com/)
- [Lucide Icons](https://lucide.dev/)

---

##  Responsividade

| Nome | Largura | Dispositivo |
|------|---------|-------------|
| `mobile` | < 640px | Smartphones |
| `tablet` | 640px - 1024px | Tablets |
| `desktop` | 1024px - 1280px | Laptops |
| `wide` | > 1280px | Monitores grandes |

---

##  Aplicação

### Dark Mode (Recomendado)
- Fundo: `#000000` ou `#1A1A1A`
- Texto: `#FFFFFF`
- Destaque: `#F7931A`

### Light Mode
- Fundo: `#FFFFFF`
- Texto: `#000000`
- Destaque: `#F7931A`

---

<div align="center">

**Bitcoin Creative Design System v1.0**

*"Good design is orange."* 

</div>
