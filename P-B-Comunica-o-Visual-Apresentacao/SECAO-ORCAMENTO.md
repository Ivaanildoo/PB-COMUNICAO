# 📊 Seção de Orçamento Adicionada

**Data:** 22 de abril de 2026  
**Versão:** apresentacao.html (agora com 8 slides)

## Resumo das Alterações

### ✅ Nova Seção Criada: S8 - Orçamento

Foi adicionada uma nova seção profissional de orçamento e condições de pagamento, posicionada estrategicamente como Slide 8/08 (penúltimo slide antes de um possível CTA final).

### 📋 Conteúdo da Seção S8

**Título Principal:**
> "Investimento e Condições."

**Subtítulo:**
> "Tabela de preços para desenvolvimento de home page profissional com todas as otimizações apresentadas."

#### Card 1: Serviço
- **Título:** Home Page Premium
- **Valor:** R$ 6.000,00
- **Inclui:**
  - ✓ Design responsivo com identidade visual
  - ✓ Otimização de velocidade e Core Web Vitals
  - ✓ Blog integrado (4 artigos iniciais)
  - ✓ 21 imagens do portfólio profissional
  - ✓ SEO técnico completo
  - ✓ Hospedagem em CDN global

#### Card 2: Condições de Pagamento (Destaque)
- **Badge:** FACILITADO
- **Título:** Condições de Pagamento
- **Destaque:** Parcelado em até **3x**
- **Parcelamento:**
  - ✓ Primeira parcela: 50%
  - ✓ Segunda parcela: 25%
  - ✓ Terceira parcela: 25%
  - ✓ Sem juros
  - ✓ Entrega progressiva
  - ✓ Suporte técnico 30 dias

**CTA:** Botão "Solicitar Proposta ↗" (link: mailto:contato@pbcomunicacao.com.br)

---

## 🎨 Estilos Adicionados

### CSS para Pricing:
```css
.pricing-card {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 18px;
  flex: 1;
  margin: 20px 0;
}

.pricing-item {
  background: linear-gradient(135deg, rgba(39,169,33,.08) 0%, rgba(12,45,131,.04) 100%);
  border: 1.5px solid rgba(39,169,33,.2);
  border-radius: var(--r);
  padding: 20px 22px;
}

.pricing-item.highlight {
  border-color: var(--verde);
  background: linear-gradient(135deg, rgba(39,169,33,.12) 0%, rgba(39,169,33,.05) 100%);
  position: relative;
}

.pricing-badge {
  position: absolute;
  top: -10px;
  right: 16px;
  background: var(--verde);
  color: #fff;
  padding: 4px 12px;
  font-size: .65rem;
  font-weight: 700;
  border-radius: 20px;
  text-transform: uppercase;
}
```

**Cores Utilizadas:**
- Verde (badge, checkmarks): `#27A921` (--verde)
- Azul (texto de valor): `#0C2D83` (--azul)
- Branco: `#FFFFFF` (--branco)
- Gradientes com transparência: rgba(39,169,33,.08) até rgba(12,45,131,.04)

---

## 🔄 Alterações Também Realizadas

### 1️⃣ Barra de Progresso → Azul
- **De:** `linear-gradient(90deg, var(--verde), var(--verde-claro))`
- **Para:** `linear-gradient(90deg, var(--azul), #1a3fa6)`
- **Afetado:** `#prog` (barra fixa no topo)

### 2️⃣ Barra de Dados (.bar-g) → Azul
- **De:** `linear-gradient(90deg, var(--verde), var(--verde-claro))`
- **Para:** `linear-gradient(90deg, var(--azul), #1a3fa6)`
- **Usado em:** Gráficos de evolução/progresso

### 3️⃣ Contador de Slides
- **De:** "1 / 12"
- **Para:** "1 / 08"
- **Obs:** Dinâmico, atualiza-se com JavaScript automaticamente

---

## 📊 Estrutura do Arquivo Agora

```
Slide 1 (01/08) - Capa com Logo
Slide 2 (02/08) - Antes/Depois
Slide 3 (03/08) - Velocidade
Slide 4 (04/08) - Palavras-chave
Slide 5 (05/08) - Blog
Slide 6 (06/08) - Projeção de Tráfego
Slide 7 (07/08) - CTA Principal
Slide 8 (08/08) - Orçamento e Condições ✨ NOVO
```

---

## 🎯 Tom e Posicionamento

**Estratégia:**
- Seção profissional e técnica (B2B)
- Informações comerciais claras e diretas
- Design com dois cards: um técnico (esquerda), um comercial (direita)
- Badge "FACILITADO" destaca a flexibilidade de pagamento
- Suporta navegação completa (⬅️ ➡️, dots, teclado)

**Responsividade:**
- Grid 2 colunas em desktop
- Adapta-se automaticamente com CSS media queries
- Mantém proporções em tablets e mobile

---

## ✨ Próximas Sugestões (Opcional)

1. **Slide Final (S9):** Poderia incluir formulário ou outro CTA
2. **Animações:** Adicionar reveal animations ao scroll dos cards
3. **Versões:** Criar versões com mais opções de pacotes (Básico, Premium, Enterprise)
4. **FAQ:** Seção de perguntas frequentes sobre pagamento

---

**Status:** ✅ Implementado e Funcional
**Compatibilidade:** HTML5, CSS3, Vanilla JS
**Testado em:** Desktop (responsividade verificada)
