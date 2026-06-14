# 🖼 Wireframe Escopo Criador

> Crie wireframes de escopo visual diretamente no navegador — sem instalação, sem internet, sem IA.

![Desktop](docs/screenshot-desktop.png)

---

## ✨ O que é

**Wireframe Escopo Criador** é uma ferramenta 100% offline para montar rapidamente o escopo visual de um projeto web ou mobile. Você escolhe um modelo pronto ou monta do zero com mais de **135 componentes** em estilo de planta profissional (linha fina), reordena, personaliza e exporta a imagem — tudo sem precisar de conexão com a internet nem de IA.

É um **único arquivo HTML**. Abra no navegador e pronto.

> Ideal para apresentar o escopo ao cliente como uma **planta de baixa fidelidade** — ele entende a estrutura da página antes de qualquer linha de código.

---

## 🚀 Como usar

### 1. Abrir o app

Baixe o arquivo `index.html` e abra no seu navegador (Chrome, Firefox, Edge, Safari).

Ou acesse diretamente pelo GitHub Pages se disponível.

### 2. Começar rápido com um modelo pronto (opcional)

Clique em **✨ Modelos prontos** na barra superior para escolher um ponto de partida.
O modelo é carregado já montado — depois é só editar e exportar.

| Modelos disponíveis | |
|---|---|
| 💎 E-commerce 1 · Semijoias | 💅 Salão de Beleza / Estética |
| 👜 E-commerce 2 · Acessórios/Moda | 💈 Cabeleireiro / Barbearia |
| 🛒 E-commerce 3 · Loja geral | 🏠 Corretora de Imóveis |
| 🚀 Landing SaaS / Serviço | 🩺 Clínica / Consultório |
| 📊 Painel / Dashboard | |

![Modelos prontos](docs/screenshot-templates.png)

### 3. Montar o wireframe

- Clique em um componente na **Biblioteca** para adicionar à seção
- Use os botões **↑ ↓** para reordenar os componentes
- Ajuste o alinhamento (largura total / esquerda / centro / direita)
- Edite o título de cada seção e remova o que não quiser

### 4. Exportar

Clique em **⬇ Baixar PNG** no painel de exportação.

---

## 📱 Funciona no celular

O app foi otimizado para uso mobile. No celular, um botão flutuante **👁** aparece no canto inferior direito para abrir o preview em tela cheia.

| Mobile — modelos prontos | Mobile — biblioteca de componentes |
|:---:|:---:|
| ![Mobile](docs/screenshot-mobile.png) | ![Modal Mobile](docs/screenshot-mobile-modal.png) |

---

## 🖼 Exportação de imagem

A exportação é feita **100% no navegador**, sem depender de internet ou de nenhum serviço externo:

| Formato | Descrição |
|---------|-----------|
| **⬇ Baixar PNG** | Arquivo PNG em alta resolução (2.5× escala) |
| **⬇ Baixar SVG** | Arquivo SVG vetorial, escalável infinitamente |
| **📋 Copiar imagem** | Copia o PNG direto para a área de transferência |
| **⧉ Copiar base64** | Copia a string base64 (útil para e-mails, HTML, APIs) |

### Exemplo de saída (PNG exportado)

![Export](docs/screenshot-export.png)

> **Técnica**: O wireframe é montado como SVG, convertido para `<canvas>` via `drawImage`, e exportado com `canvas.toDataURL()`. Zero dependências externas.

---

## 📦 Biblioteca de componentes

Mais de **135 componentes** organizados em categorias — incluindo e-commerce, serviços/agendamento, saúde, imóveis e dashboard/app:

### Navegação
| Componente | Descrição |
|-----------|-----------|
| `topbar` | Barra de navegação superior clássica |
| `topbar_dark` | Navbar dark com logo e links |
| `topbar_social` | Barra com ícones de rede social |
| `nav_mobile` | Navegação bottom-tab para mobile |
| `breadcrumb` | Trilha de navegação |
| `pagination` | Controles de paginação |
| `sidebar` | Menu lateral |
| `tabs` | Abas horizontais |

### Cabeçalhos e Heróis
| Componente | Descrição |
|-----------|-----------|
| `hero` | Hero com texto + imagem lado a lado |
| `hero_centered` | Hero centralizado com CTA |
| `header_banner` | Banner de destaque com cor sólida |
| `section_header` | Título de seção com subtítulo |

### Conteúdo
| Componente | Descrição |
|-----------|-----------|
| `card_grid` | Grid de cards (3 colunas) |
| `card_h` | Card horizontal (imagem + texto) |
| `feature_row` | Linha de features com ícones |
| `features_zigzag` | Seção alternando imagem e texto |
| `value_props` | Proposta de valor em 3 colunas |
| `testimonials` | Depoimentos de clientes |
| `blog_grid` | Grid de posts de blog |
| `image_gallery` | Galeria de imagens |
| `video_player` | Player de vídeo |
| `rich_text` | Bloco de texto longo |
| `accordion` | FAQ em acordeão |
| `timeline` | Linha do tempo |

### Produtos e E-commerce
| Componente | Descrição |
|-----------|-----------|
| `product_detail` | Página de detalhe de produto |
| `product_card_h` | Card de produto horizontal |
| `price_tag` | Etiqueta de preço com destaque |
| `price_table` | Tabela de preços / planos |
| `spec_list` | Lista de especificações técnicas |
| `cart_summary` | Resumo do carrinho |

### Formulários e Interação
| Componente | Descrição |
|-----------|-----------|
| `form_contact` | Formulário de contato |
| `form_login` | Tela de login |
| `form_register` | Tela de cadastro |
| `search_bar` | Barra de busca |
| `newsletter` | Caixa de inscrição por e-mail |
| `newsletter_footer` | Newsletter no rodapé |
| `chat_widget` | Widget de chat flutuante |
| `promo_popup` | Pop-up de promoção |

### Dados e Tabelas
| Componente | Descrição |
|-----------|-----------|
| `table` | Tabela de dados |
| `data_chart` | Gráfico de barras |
| `stats_row` | Linha de métricas / KPIs |
| `map` | Placeholder de mapa |

### Rodapé
| Componente | Descrição |
|-----------|-----------|
| `footer` | Rodapé com colunas e links |
| `footer_cta` | Rodapé com call-to-action |
| `footer_minimal` | Rodapé simples |

### Utilitários
| Componente | Descrição |
|-----------|-----------|
| `divider` | Divisor horizontal |
| `spacer` | Espaçamento em branco |
| `tag_cloud` | Nuvem de tags / filtros |
| `badge_row` | Linha de badges / chips |
| `avatar_row` | Linha de avatares de usuário |
| `progress_bar` | Barra de progresso |
| `notification` | Banner de notificação |
| `empty_state` | Estado vazio com CTA |
| `skeleton` | Esqueleto de carregamento |

---

## 💾 Salvar e Carregar

- **💾 Salvar** — salva o projeto no `localStorage` do navegador
- **📂 Abrir** — carrega um projeto salvo (ou importa um arquivo `.json`)
- **Novo** — limpa a tela para começar do zero

> O projeto é salvo como JSON com a lista de componentes e seus rótulos.

---

## 🛠 Tecnologias

| Recurso | Detalhes |
|---------|----------|
| **HTML/CSS/JS** | Nenhuma dependência externa, nenhum bundler |
| **SVG** | Todos os componentes são desenhados em SVG puro |
| **Canvas API** | Conversão SVG → PNG para exportação |
| **localStorage** | Persistência de projetos no navegador |
| **CSS Variables** | Tema consistente com `--accent`, `--grad`, `--bg-1` |
| **Media Queries** | Layout responsivo em 1020px e 640px |

---

## 📐 Arquitetura

```
index.html
│
├── Biblioteca de ícones SVG (objeto I{})
│   └── 135+ componentes com viewBox proporcional
│
├── buildSVG()
│   └── Monta o wireframe completo como SVG standalone
│       (mesmo SVG usado para preview e exportação)
│
├── Preview em tempo real
│   └── <div id="preview"> renderiza buildSVG() ao vivo
│
└── Exportação
    ├── downloadPNG()   → SVG → Canvas → toDataURL() → download
    ├── downloadSVG()   → Blob SVG → download
    ├── copyImage()     → Canvas → ClipboardItem → clipboard
    └── copyBase64()    → toDataURL() → clipboard (string)
```

---

## 📸 Screenshots

### Desktop

![Desktop Screenshot](docs/screenshot-desktop.png)

### Mobile

![Mobile Screenshot](docs/screenshot-mobile.png)

---

## 🤝 Contribuindo

1. Faça um fork do repositório
2. Edite o `index.html`
3. Abra o arquivo no navegador para testar
4. Crie um pull request com a descrição do que foi adicionado

Para adicionar um novo componente, adicione uma entrada no objeto `I` seguindo o padrão:

```js
nome_componente: `<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 200 60">
  <!-- seu SVG aqui -->
</svg>`
```

A proporção `viewBox` define automaticamente a altura do componente no wireframe (ex.: `200×60` = componente com 30% de altura em relação à largura).

---

## 📄 Licença

MIT — use, modifique e distribua à vontade.

---

<p align="center">Feito com ♥ para quem precisa de wireframes rápidos, sem enrolação.</p>
