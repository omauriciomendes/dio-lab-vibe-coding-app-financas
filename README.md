# 💸 App de Organização de Finanças Pessoais para pessoas de todas as idades com leitura de extratos e comprovantes com Vibe Coding

Aprenda a **criar soluções com IA** de forma criativa, guiando ferramentas como o **Copilot** e o **Lovable** com uma comunicação simples e natural. O foco é desenvolver o conceito de um **App de Organização de Finanças Pessoais**, mas, acima de tudo, aprender o **jeito Vibe de programar com IA**.

## ✨ O que é Vibe Coding

**Vibe Coding** é uma forma leve e criativa de desenvolver com IA, baseada em **conversas naturais e bem estruturadas**. Você não precisa escrever código linha por linha. Em vez disso, aprende a **guiar a IA** descrevendo suas ideias de forma clara, com **intenção e contexto**. Em outras palavras:

> Você mostra a vibe da sua ideia e a IA transforma em solução (ou em um caminho para ela).

## 
```txt
# PRD – App de Finanças por Conversa com Design Universal

## 1. Visão Geral
Aplicativo de organização financeira que funciona por conversa e leitura de imagens/PDFs.  
O usuário registra gastos conversando ou enviando fotos de notas, comprovantes e extratos.  
O app deve ser simples, acessível e utilizável por pessoas de todas as idades e níveis de familiaridade com tecnologia.

Princípio central: **Design Universal**.  
Se alguém que “não entende de celular” consegue usar, o app está bem projetado.

---

## 2. Problema
Apps financeiros atuais exigem muito esforço:
- Campos demais para preencher
- Telas poluídas
- Termos técnicos
- Falta de acessibilidade
- Pouco suporte para fotos/PDFs

Isso causa abandono rápido.  
O objetivo é remover atrito e simplificar o controle financeiro para qualquer pessoa.

---

## 3. Público-Alvo
Usuários de todas as idades e perfis:
- Iniciantes em finanças
- Idosos
- Pessoas com baixa escolaridade
- Usuários com pouca experiência tecnológica
- Pessoas que preferem conversar, não preencher formulários
- Quem guarda fotos/prints de comprovantes

Design Universal: simples, flexível e acolhedor.

---

## 4. Proposta de Valor
“Controle suas finanças conversando ou enviando uma foto.”

Benefícios:
- Registro rápido via chat
- Leitura automática de notas, comprovantes e PDFs
- Relatórios simples
- Metas acessíveis
- Dicas personalizadas
- Interface limpa e acessível

---

## 5. Princípios de Design Universal

### 5.1 Clareza
- Frases simples
- Textos curtos
- Sem jargão técnico
- Exemplos constantes

### 5.2 Flexibilidade
- Suporte a texto, fotos, documentos
- (Futuro) entrada por voz

### 5.3 Perceptibilidade
- Fonte mínima 16px
- Alto contraste
- Ícones universais
- Botões grandes

### 5.4 Baixa Carga Cognitiva
- Telas minimalistas
- Chat como interface principal
- Relatórios simples e diretos

### 5.5 Tolerância a Erros
- IA pergunta quando não entender
- Usuário sempre pode editar valores
- Processos guiados

### 5.6 Consistência
- Padrões visuais e de linguagem fixos
- Mesmas cores, botões e ícones

---

## 6. Funcionalidades-Chave

### 6.1 Registro via Conversa
O usuário digita frases como:
- “Gastei 35 no iFood”
- “Paguei 200 de energia ontem”
- “Recebi 1500 do freela”

App interpreta:
- Valor
- Categoria
- Data
- Tipo (gasto/receita)

E confirma:
“Identifiquei um gasto de R$ 35 em Alimentação. Confirmar?”

---

### 6.2 Leitura de Fotos, Notas, Comprovantes e PDFs
Usuário pode enviar:
- Foto de recibo
- Nota fiscal
- Comprovante de PIX
- Print de extrato
- PDF da fatura

App extrai:
- Valor
- Data
- Estabelecimento
- Categoria
- Lista de várias transações (se houver)

Exemplos:
- “Encontrei um gasto de R$ 42,90 no Mercado Preço Bom. Confirmar?”
- “Encontrei 7 transações neste extrato. Adicionar todas?”

Se a foto estiver ruim:
“Não consegui ler o valor. Pode tentar outra foto ou digitar apenas o valor?”

---

### 6.3 Classificação Automática
O sistema sugere categorias e aprende com correções.

---

### 6.4 Metas Simples
Exemplos:
- “Quero guardar 300 este mês.”
- “Limitar delivery a 200.”

App acompanha e avisa com clareza:
“Você já usou 60% da sua meta de delivery.”

---

### 6.5 Dicas Inteligentes
Baseadas no comportamento real:
- “Seu gasto com transporte subiu 20% esta semana.”
- “Você economizou R$ 90 na última semana. Bom trabalho!”

Tom sempre amigável, nunca julgador.

---

### 6.6 Relatórios Simples
- Total gasto
- Total recebido
- Saldo
- Top categorias
- Gráfico minimalista

---

## 7. Requisitos Não Funcionais

### Acessibilidade
- Contraste adequado (WCAG)
- Botões grandes
- Fonte ampliada opcional

### Performance
- OCR rápido
- Chat responsivo

### Segurança
- Dados privados
- Documentos podem ser apagados após leitura

---

## 8. Telas do MVP

### 8.1 Tela de Chat
- Entrada por texto
- Botão para enviar fotos/PDFs
- Mensagens rápidas sugeridas

### 8.2 Tela de Revisão de Documento
- Valores detectados
- Confirmar / Editar / Cancelar

### 8.3 Tela de Resumo
- Totais do mês
- Gráfico simples

### 8.4 Tela de Metas
- Criar e acompanhar metas

---

## 9. Sucesso do MVP

Métricas:
- % de transações registradas sem erro
- % de fotos/PDFs lidos corretamente
- Retenção de 7 dias
- Nota de usabilidade (0–10)
- Engajamento semanal

---

## 10. Declaração Oficial sobre Design Universal
“O aplicativo será projetado com base em **Design Universal**, garantindo uso fácil e intuitivo por pessoas de todas as idades, níveis de escolaridade e experiências com tecnologia. A interface deve ser clara, acessível, com linguagem simples e diversas formas de interação, incluindo texto, fotos e documentos.”


```
Interaçãos com o Lovable:

>Crie um app de finanças pessoais com base nesse PRD: {PRD}
>Crie uma tela de loguin segura com senha e usuário para ter maior controle
> Sim (Crie uma tela de loguin segura com senha e usuário para ter maior controle)

Resultado Final no Lovable: https://conversa-financas.lovable.app

<img width="2560" height="1080" alt="image" src="https://github.com/user-attachments/assets/a087e47e-4d1a-4c83-9e1f-035532a0f088" />



# 📱 Resumo do que o App de Finanças Pessoais faz

O **Minhas Finanças** é um assistente financeiro inteligente que te ajuda a organizar seu dinheiro de forma simples, rápida e sem complicação.  
Tudo acontece através de uma conversa natural, como se você estivesse falando com alguém que realmente entende suas finanças.

### O app permite que você:

- **Registre gastos e receitas conversando**, usando frases do dia a dia  
  - Ex.: “Gastei 50 no mercado”, “Recebi 300 do Pix”
- **Envie fotos, notas, comprovantes ou PDFs**, e o app lê automaticamente os valores e datas
- **Acompanhe um resumo claro** do mês, com total gasto, total recebido e saldo
- **Crie metas financeiras acessíveis**, como “guardar 200 por mês” ou “limitar delivery”
- **Veja suas categorias de gastos** de forma simples e visual
- **Use botões rápidos** para acelerar ações comuns
- Aproveite uma interface com **Design Universal**, acessível para pessoas de todas as idades e perfis

👉 Em poucas palavras:  
**Você conversa, envia uma foto se quiser, e o app organiza suas finanças por você. Fácil, rápido e para todo mundo.**

# 🧠 Reflexão Sobre o Processo

## ✅ O que funcionou bem?

- A comunicação clara com a IA permitiu construir rapidamente um protótipo funcional.
- O PRD estruturado serviu como guia e evitou pontos de confusão.
- O Lovable interpretou bem os requisitos principais e criou uma interface simples e intuitiva.
- O fluxo de conversa ficou natural e fácil de entender.
- A adição de botões de ações rápidas tornou o uso mais prático.
- A abordagem de Design Universal funcionou como base sólida para um app acessível.

---

## ⚠️ O que não funcionou como o esperado?

- Algumas interpretações da IA exigiram retrabalho, especialmente em instruções mais complexas.
- A leitura de documentos ainda não é perfeita e pode exigir ajustes manuais.
- Nem todas as funcionalidades descritas no PRD foram implementadas exatamente como planejado.
- Em certos momentos, foi preciso redizer instruções de forma mais objetiva para a IA compreender.
- Algumas limitações do Lovable impediram automações mais avançadas no MVP.

---

## 🎓 O que aprendi sobre conversar com IAs?

- Quanto mais direto e específico for o comando, melhor o resultado.
- Exemplos práticos ajudam muito a IA a entender a intenção.
- A IA não preenche lacunas — tudo precisa ser explicado claramente.
- Iterar, testar e refinar é essencial para chegar ao resultado desejado.
- Conversar com IA é uma habilidade: quanto mais você pratica, mais entende como guiá-la.
- Aprendi a pensar como “gerente de produto”, não só como usuário.
- A IA é excelente para gerar, mas depende totalmente da sua comunicação para direcionar.

👉 **Conclusão:** Guiar uma IA é como liderar um desenvolvedor — quando você comunica bem, ela constrói melhor.


## 💬 Conclusão

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
