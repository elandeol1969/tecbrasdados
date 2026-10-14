# TecBras — Soberania, Segurança e Independência Digital do Brasil

Página web institucional do projeto **TecBras (Empresa Brasileira de Tecnologia e Mídias Sociais S.A.)**, uma proposta de criação de empresa estatal (Sociedade de Economia Mista) voltada à soberania digital brasileira, com infraestrutura própria de nuvem, rede social pública, mensageria segura e inteligência artificial nacional.

> ⚠️ **Aviso**: conteúdo meramente propositivo, sem vínculo oficial com o Governo Federal.

---

## 📁 Estrutura de Arquivos

```
pagina/
├── index.html         → Página principal (estrutura, estilos e scripts)
├── favicon.png        → Logotipo exibido no cabeçalho (canto superior esquerdo)
├── TecBrasLogo.png    → Arquivo de imagem da marca (reserva/uso geral)
├── textoProjeto.pdf   → Texto completo do projeto (baixável via botão no hero)
└── README.md          → Este arquivo
```

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Uso |
|---|---|
| **HTML5** | Estrutura da página (arquivo único) |
| **Tailwind CSS (CDN)** | Estilização utilitária e responsividade |
| **Lucide Icons** | Ícones vetoriais da interface |
| **Google Fonts** | Plus Jakarta Sans (geral), JetBrains Mono (logo/código) e Roboto (menu) |
| **JavaScript (vanilla)** | Menu mobile, estado ativo dos links e ícones |

Não há processo de build nem dependências locais: basta abrir o `index.html` em um navegador.

## 📄 Seções da Página

| Âncora | Seção | Conteúdo |
|---|---|---|
| `#inicio` | Hero | Preâmbulo do projeto e botões de ação (Explorar Proposta, Ver Anteprojeto e **Baixar PDF**) |
| `#cenario` | 1. Cenário Atual | Diagnóstico da dependência estrutural das Big Techs |
| `#problema` | 2. O Problema | Impactos sobre dados pessoais, instituições e debate democrático |
| `#proposta` | 3. Proposta de Valor | Nuvem soberana, rede social pública, mensageria segura e IA nacional |
| `#publico` | 4. Público-Alvo | Cidadãos, instituições públicas e ecossistema de tecnologia |
| `#recursos` | 5. Recursos e Orçamento | Viabilidade: SERPRO/DATAPREV, FUST/FISTEL, capital misto e P&D |
| `#anteprojeto` | 6. Anteprojeto de Lei | Resumo estruturado dos Artigos 1º a 5º da proposta legislativa |

## ✨ Funcionalidades Implementadas

- **Menu de navegação fixo** com efeito de vidro (`backdrop-blur`) e links de âncora com rolagem suave.
- **Estado ativo persistente**: ao clicar em um link do menu, seu fundo permanece destacado (`.nav-link-active` / `.nav-cta-active`) até outro clique.
- **Menu mobile** (hambúrguer) com abertura/fechamento e recolhimento automático ao clicar em um link.
- **Botão de download** do arquivo `textoProjeto.pdf` — ao lado de "Ver Anteprojeto de Lei" no desktop e abaixo dele no mobile (layout `flex-col sm:flex-row`).
- **Logotipo em imagem** (`favicon.png`) no cabeçalho, nas mesmas dimensões do ícone original (44×44 px).
- **Cards interativos** com elevação e sombra suave no hover (`.card-hover`).
- **Layout totalmente responsivo** (breakpoints `sm`, `lg` do Tailwind).

## 🎨 Identidade Visual

### Paleta de Cores

| Cor | Hex | Uso |
|---|---|---|
| Scarlet 600 | `#DC143C` | Destaques e bordas |
| Scarlet 700 | `#B22222` | Botões, ícones e textos de ênfase |
| Scarlet 800 | `#8B0000` | Hover de botões e elementos escuros |
| Off-white | `#F8F9FA` | Fundo da página |
| Charcoal 900 | `#1A1A1A` | Textos principais e bloco de código |

### Tipografia

| Fonte | Aplicação |
|---|---|
| **Plus Jakarta Sans** | Textos gerais, títulos e parágrafos |
| **JetBrains Mono** | Logotipo textual e bloco do Anteprojeto de Lei |
| **Roboto** | Exclusivamente os textos dos links do menu de navegação |

## ▶️ Como Executar

1. Certifique-se de que todos os arquivos estejam na mesma pasta.
2. Abra o arquivo `index.html` diretamente em qualquer navegador moderno (duplo clique) — não é necessário servidor.
3. Para o botão de download funcionar, o arquivo `textoProjeto.pdf` deve permanecer na mesma pasta do `index.html`.

> Dica: para recarregar CDNs (Tailwind, Lucide, Google Fonts) é necessária conexão com a internet.

## 📝 Convenções de Conteúdo

- A marca é escrita **"TecBras"** (sem acento agudo) em todo o código e conteúdo.
- Fundamentação jurídica citada: **LGPD (Lei nº 13.709/2018)** e **Lei das Estatais (Lei nº 13.303/2016)**.
