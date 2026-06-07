# Guia: Usando o Template de Pitch

## 📋 Visão Geral

O arquivo `pitch-template.html` é um template profissional e reutilizável para criar apresentações de projetos. Ele pode ser customizado para qualquer tipo de projeto que necessite um pitch estruturado.

## 🎯 Como Usar

### Passo 1: Copiar o Template

Faça uma cópia do `pitch-template.html` para seu novo projeto:

```bash
cp pitch-template.html pitch-novo-projeto.html
```

### Passo 2: Customizar Placeholders

Abra o arquivo em um editor de texto e substitua todos os placeholders (entre colchetes `[]`) pelos seus dados. Exemplos:

| Placeholder | Substitua por |
|-------------|--------------|
| `[TITULO_PRINCIPAL]` | Ex: "Sistema de Gestão de Feiras Livres" |
| `[SUBTITULO_DESCRITIVO]` | Ex: "Modernizando a administração das feiras livres de Fortaleza" |
| `[EMOJI]` | Um emoji relacionado (ex: 🏪, 🎓, 🚀, etc) |
| `[DESAFIO_1]`, `[DESAFIO_2]`, etc | Listagem dos principais problemas |
| `[PERSONA_1]`, `[PERSONA_2]`, etc | Seus públicos-alvo principais |

### Passo 3: Customizar Cores

Localize a seção de estilos CSS e substitua os placeholders de cor:

```html
<style>
    header {
        background: linear-gradient(135deg, [COR_PRINCIPAL_ESCURA] 0%, [COR_PRINCIPAL] 100%);
    }
</style>
```

**Placeholders de Cor:**
- `[COR_PRINCIPAL]` - Cor principal do projeto
- `[COR_PRINCIPAL_ESCURA]` - Versão escura da cor principal
- `[COR_SECUNDARIA]` - Cor secundária
- `[COR_SECUNDARIA_CLARA]` - Versão clara da cor secundária
- `[COR_FUNDO_CARDS]` - Cor de fundo dos cards

**Exemplo de Paleta:**
```
Cor Principal: #0057B8
Cor Principal Escura: #003B7A
Cor Secundária: #4A90E2
Cor Secundária Clara: #DCEBFA
Cor Fundo Cards: #F5F7FA
```

### Passo 4: Adicionar Logos

Descomente e adicione as tags de imagem no header e footer:

```html
<!-- No Header -->
<img src="assets/images/seu-logo.png" alt="Logo do Projeto">

<!-- No Footer -->
<img src="assets/images/logo-instituicao.png" alt="Logo Instituição">
```

### Passo 5: Estruturar o Conteúdo

O template possui 7 seções principais. Complete cada uma:

1. **Problema** - Desafios principais (6 cards padrão)
2. **Público-alvo** - 4 personas com características
3. **Solução Proposta** - Visão geral e características
4. **Funcionalidades Principais** - Grupos de funcionalidades (3 grupos padrão)
5. **Demonstração do Protótipo** - 3 telas principais
6. **Benefícios e Impacto** - Benefícios por público + impacto geral
7. **Próximos Passos** - Roadmap (5 passos padrão)

## 📝 Placeholders Comuns

### Estruturais
- `[TITULO_PROJETO]` - Nome do projeto
- `[EMOJI]` - Emoji relacionado ao projeto
- `[INSTITUICAO_DISCIPLINA]` - Ex: "Disciplina de Requisitos - Universidade de Fortaleza"
- `[ANO]` - Ano atual

### Conteúdo
- `[DESCRIÇÃO_...]` - Descrições de seções ou itens
- `[ICONE]` - Emojis para os cards
- `[DESAFIO_N]`, `[BENEFICIO_N]` - Numeração de itens
- `[PERSONA_N]`, `[FUNCIONALIDADE_N]` - Nomes de personas/features

### Cores
- `[COR_PRINCIPAL]` - Cor dominante
- `[COR_PRINCIPAL_ESCURA]` - Cor para headers
- `[COR_SECUNDARIA]` - Cor de destaques
- `[COR_SECUNDARIA_CLARA]` - Cor de fundos suaves
- `[COR_FUNDO_CARDS]` - Cor de fundo dos containers

## 🎨 Personalizando Cores Globalmente

Se quiser mudar todas as cores de uma vez, use find & replace:

1. **Find:** `[COR_PRINCIPAL]`
   **Replace:** `#0057B8`

2. **Find:** `[COR_PRINCIPAL_ESCURA]`
   **Replace:** `#003B7A`

E assim por diante...

## 📊 Dicas de Conteúdo

### Para a Seção "Problema"
- Use 5-6 desafios principais
- Cada desafio deve ter um ícone/emoji representativo
- Seja conciso: máximo 2-3 linhas por desafio

### Para a Seção "Público-alvo"
- Mantenha 3-4 personas principais
- Inclua: Descrição, Necessidade e Prioridade
- Use badges para destacar importância (Alta, Média, Baixa)

### Para a Seção "Funcionalidades"
- Agrupe funcionalidades por domínio (Ex: Gestão, Relatórios, Segurança)
- Use numeração (1️⃣, 2️⃣, etc) para grupos
- Mantenha descrições simples e diretas

### Para a Seção "Benefícios"
- Separe por público-alvo
- Use emojis para tornar mais visual
- Foque no impacto prático

## 🚀 Exportando o Pitch

### Como PDF
1. Abra o HTML no navegador
2. Use `Ctrl+P` (Windows) ou `Cmd+P` (Mac)
3. Selecione "Salvar como PDF"

### Como imagem
1. Use ferramentas como Puppeteer ou Playwright
2. Ou capture screenshots da página

## 📦 Estrutura Recomendada

```
seu-projeto/
├── pitch.html (ou pitch-seu-projeto.html)
├── pitch-template.html (manter para referência)
├── assets/
│   └── images/
│       ├── logo-projeto.png
│       └── logo-instituicao.png
└── PITCH_INSTRUCOES.md
```

## ✅ Checklist Final

Antes de apresentar, verifique:

- [ ] Todos os placeholders `[]` foram preenchidos
- [ ] Cores foram customizadas
- [ ] Logos foram adicionados
- [ ] Links de navegação funcionam
- [ ] Conteúdo foi revisado (ortografia, gramática)
- [ ] Design responsivo em mobile (teste em navegador)
- [ ] Todas as seções têm conteúdo relevante
- [ ] Próximos Passos estão definidos

## 💡 Exemplos de Projetos

Este template funciona bem para:
- Pitches de startups e MVPs
- Apresentações de disciplinas universitárias
- Propostas de sistemas para órgãos públicos
- Apresentações de projetos internos
- Produtos e serviços digitais

## 🔗 Referências

- Paleta de cores: Customize conforme identidade visual
- Tipografia: Segoe UI (Microsoft), Google Fonts (alternativa)
- Emojis: [Emoji List](https://unicode.org/emoji/charts/full-emoji-list.html)

---

**Versão:** 1.0  
**Última atualização:** 2026-06-07
