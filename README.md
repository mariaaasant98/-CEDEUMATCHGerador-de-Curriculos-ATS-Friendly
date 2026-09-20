# -CEDEUMATCHGerador-de-Curriculos-ATS-Friendly
Um app que te faz dar match com a vaga dos sonhos! Otimizado para primeiro emprego, estágio e emprego pós graduação
PRD refinado com Gemini
# NOME DO APP: CÊDEUMATCH - Seu Primeiro Match Profissional

## 1. Visão Geral e Propósito
- **Público-Alvo:** Estudantes buscando estágio, jovens em busca do primeiro emprego e recém-formados (pós-graduação).
- **Problema:** Candidatos sem vasta experiência profissional são invisíveis para os robôs do RH (ATS) e não conseguem nem chegar na fase de entrevista.
- **Solução & Grande Objetivo:** Fazer o candidato **SE DESTACAR** nas vagas. O app compara o perfil (projetos, trabalhos acadêmicos, voluntariado, habilidades) com a vaga desejada, identifica lacunas e reformula o currículo para destacar o potencial máximo do usuário.
- **Regra de Ouro (Inviolável):** O app NUNCA inventa experiências que o usuário não tem. Ele aprende a "traduzir" vivências reais (TCC, trabalhos de faculdade, cursos) para a linguagem e termos que o RH valoriza.

## 2. Design System & Identidade Visual (Confortável e Acolhedora)
- **Framework:** React, Tailwind CSS e componentes `shadcn/ui`.
- **Atmosfera/Conceito Visual:** Ambiente confortável, humano, motivador e acessível. Tira o peso e a ansiedade da busca por emprego.
- **Paleta de Cores:**
  - **Fundo / Base:** Tom creme bem suave ou off-white quente (`#FAF8F5` ou `amber-50/10`) para criar um ambiente visualmente confortável e sem cansar os olhos.
  - **Cor Primária (Laranja Quente / Sunset):** Usada em botões principais, destaques e chamadas de ação (`orange-500` / `#F97316`) — transmite energia e entusiasmo.
  - **Cor Secundária (Rosa Acolhedor / Soft Pink):** Usada em cards de destaque, badges e detalhes amigáveis (`rose-400` / `#FB7185`) — transmite empatia e acolhimento.
  - **Cor de Destaque / Accent (Amarelo Iluminado / Sol):** Usada para pontuar vitórias, palavras-chave encontradas e métricas de match (`amber-400` / `#FBBF24`) — simboliza brilho, destaque e otimismo.
  - **Texto:** Grafite suave (`slate-800`) para excelente leitura sem o contraste agressivo do preto puro.

## 3. Estrutura da Interface e Telas (Single Page / Dashboard)

### Header (Cabeçalho Confortável)
- Logo e Nome do App: **PrimeMatch ATS**
- Slogan: *"Transforme seu potencial em destaque no RH."*
- Badge em degradê (Rosa/Laranja): *"Otimizado para Estágio e Primeiro Emprego"*

### Passo 1: Área de Entrada (Com visual leve e acolhedor)
- **Painel Duplo em Cards Flutuantes com bordas suaves:**
  1. *Lado Esquerdo (A Vaga):* Área de texto para colar a Descrição do Estágio ou Vaga Júnior.
  2. *Lado Direito (Seu Perfil):* Área de texto para colar o Currículo Atual ou listar projetos da faculdade, cursos, voluntariado e TCC.
- **Seletor de Perfil (Badges clicáveis em tom Amarelo/Laranja):**
  - [ ] Buscando Estágio
  - [ ] Primeiro Emprego
  - [ ] Primeiro Emprego Pós-Graduação
- **Botão Principal (Laranja radiante com efeito hover):** "Analisar e Me Fazer Destacar no RH" 🚀

### Passo 2: Painel "Como Se Destacar" (Dashboard do Match)
- **Score de Destaque (Match ATS):** Gráfico circular em tons de Laranja e Amarelo mostrando o nível de aderência (ex: 82% de Compatibilidade).
- **Diagnóstico de Palavras-Chave (Badges estilizadas):**
  - *Seus Pontos de Destaque (Amarelo/Verde):* O que você já tem e que o RH ama.
  - *O que falta para você brilhar (Rosa/Laranja):* Termos essenciais da vaga que você deve incluir se tiver o conhecimento.
- **Dicas Ouro de Diferenciação (Cards em tom Rosa Suave):**
  - Orientação direta de como transformar trabalhos acadêmicos e atividades extras em "experiência prática" valorizada.

### Passo 3: O Currículo em Destaque (Resultado Final)
- **Pré-visualização do Currículo ATS-Friendly:** Formatação limpa, elegante e 100% legível para os robôs do RH.
- **Sessões Reorganizadas para Impacto:**
  - *Resumo Profissional de Alto Impacto (Focado em Potencial e Objetivos).*
  - *Projetos e Conquistas em Evidência (TCC, Projetos Integradores, Voluntariado).*
  - *Competências-Chave alinhadas diretamente às exigências da vaga.*
- **Barra de Ações:**
  - Botão "Copiar Texto Formatado" (com confirmação em toast rosa/amarelo).
  - Botão "Exportar em PDF".

## 4. Requisitos de UX e Detalhes
- Usar ícones acolhedores e modernos da biblioteca `lucide-react` (ex: `Sparkles`, `Target`, `HeartHandshake`, `FileCheck`).
- Mensagem de encorajamento fixa no rodapé: *"Seu valor não depende de anos de carteira assinada. Vamos fazer o RH enxergar o seu talento!"*

