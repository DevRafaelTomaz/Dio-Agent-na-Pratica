# DIO Agent na Prática

Desafio de Projeto da [DIO](https://dio.me): configure o [DIO Agent](https://github.com/digitalinnovationone/dio-agent) e use as skills dele para estudar, praticar e planejar a sua carreira.

## Como fazer

1. Clique em **Use this template** para criar a sua cópia deste repositório.
2. Siga os passos abaixo, copiando cada prompt para o DIO Agent.
3. Preencha a seção [Minha entrega](#minha-entrega) e entregue o link da sua cópia na DIO.

## 1. Configure o DIO Agent

- Instale um harness. Recomendamos o [Google Antigravity](https://antigravity.google/docs), mas qualquer um [da lista do DIO Agent](https://github.com/digitalinnovationone/dio-agent#-comece-em-3-passos) funciona.
- Baixe o [DIO Agent](https://github.com/digitalinnovationone/dio-agent) em **Code**, **Download ZIP**, e extraia.
- No harness, abra a pasta que tem o arquivo `AGENTS.md` e mande:

```
Oi!
Quem é você e como pode me ajudar nos meus estudos na DIO?
```

Se ele se apresentar como DIO Agent, está tudo certo.

## 2. Estudar

Troque o conceito pelo que você quer entender:

```
Me explica o que é uma skill de um agente de IA.
Meu nível: uso IA no dia a dia, mas nunca configurei um agente.
```

## 3. Praticar

Use um desafio em que você travou ou este exemplo:

```
Estou travado em um Desafio de Código da DIO.
O desafio pede a soma de todos os números de 1 até N.
Meu código imprime só o último número, não a soma:
let n = parseInt(gets());
let soma = 0;
for (let i = 1; i <= n; i++) {
  soma = i;
}
print(soma);
Me ajuda a destravar sem dar a resposta pronta.
```

## 4. Planejar

Preencha os colchetes com a sua Trilha:

```
Quero montar um plano de estudos.
Trilha: [link do seu Bootcamp ou Formação]
Objetivo: concluir em [4 semanas].
Meu nível: [iniciante, intermediário ou avançado].
Tempo: [1 hora por dia, de segunda a sexta].
```

## Bônus: seu próximo passo

Se você quer construir com IA:

```
Quero escolher meu próximo passo na Carreira AI Builder.
Quero construir: [um app para os pedidos do meu negócio].
Programação: [nenhuma, o básico ou trabalho com isso].
Objetivo: [tirar uma ideia do papel].
```

---

## Minha entrega

Edite este README pelo lápis, role até aqui e cole (Ctrl+V) um print de cada passo, sem dados pessoais.

### Configure

_Cole o print do DIO Agent se apresentando._
🎉 Oi, tudo bem?
Eu sou o DIO Agent, seu mentor de tecnologia aqui na DIO. Estou pronto para te ajudar a aprender, criar projetos incríveis e transformar suas ideias em realidade – sempre com muita energia e um toque de empolgação! 🚀

### Estudar

Como o DIO Agent pode ser o seu parceiro de estudos 🎓✨
O que eu faço	Como isso ajuda você
Responder dúvidas	Pergunte sobre conceitos de programação, IA, cloud, design etc. Eu explico de forma simples, com exemplos e analogias.
Montar planos de estudo	Uso a skill study‑plan para criar um cronograma personalizado (módulos da DIO, carga horária, marcos semanais) de acordo com seu objetivo, tempo disponível e nível.
Destravar desafios	Se ficar preso em um Desafio de Código, Projeto ou Criativo, aciono a skill unblock‑challenge e dou dicas passo‑a‑passo sem entregar a solução completa.
Explicar conceitos	A skill explain‑concept gera explicações curtas, exemplos de código e comparações para que o aprendizado fique sólido.
Revisar portfólio / GitHub	Com a skill portfolio‑review analiso seu repositório, dou feedback de qualidade de código, boas práticas e sugestões de melhorias.
Orientar a carreira AI Builder	Se quiser escolher a próxima formação (IA na prática, IA aplicada a negócios, SaaS com Claude Code, Orquestração de agentes), uso a skill ai‑builder‑path para recomendar o caminho certo.
Pesquisar na web (quando necessário)	Quando precisar de informações atualizadas (versões de libs, notícias de mercado), executo a skill web‑search de forma segura.
Acompanhar progresso	Recomendo a ferramenta Meta de Estudo da DIO para registrar metas diárias, acompanhar o avanço e receber lembretes.
### Praticar

## Mini‑aula de Prompting 🎯  

### 1️⃣ Conceitos rápidos
| Conceito | Dica prática |
|----------|--------------|
| **Objetivo claro** | Comece a frase dizendo exatamente o que você quer (ex.: “Resumo”, “Lista”, “Código”). |
| **Contexto suficiente** | Forneça ao modelo as informações que ele precisa para entender a tarefa (dados, exemplos, restrições). |
| **Formato de saída** | Especifique como a resposta deve ser estruturada (lista‑bullet, JSON, código, tabela). |
| **Exemplos (few‑shot)** | Quando precisar de um padrão, mostre 1‑2 exemplos antes da sua pergunta. |
| **Limite de ambiguidade** | Evite termos vagos; seja específico sobre o que deve ser incluído ou excluído. |

---

## 2️⃣ Exercício prático

Vou dar **três desafios** de prompting.  
Para cada um, escreva o prompt que você acha que vai gerar a resposta ideal.  
Depois envie o seu prompt aqui que eu dou o feedback e, se quiser, mostro o resultado esperado (simulado).

### Desafio A – Resumo executivo
> **Tarefa:** Resumir um artigo de 800 palavras sobre “Uso de IA em e‑commerce” em até 3 frases, destacando os benefícios principais.

**Seu prompt deve:**
1. Indicar claramente que quer um *resumo executivo*.
2. Limitar a resposta a **3 frases**.
3. Pedir foco nos **benefícios**.

### Desafio B – Classificação de sentimentos
> **Tarefa:** Classificar a frase abaixo como **Positivo**, **Negativo** ou **Neutro**.  
> *Frase:* “O novo site ficou rápido, mas ainda falta integração com o pagamento.”

**Seu prompt deve:**
1. Declarar a tarefa de classificação.
2. Fornecer a frase a ser analisada.
3. Pedir a resposta apenas com a palavra da classe.

### Desafio C – Código de extração de dados (Python)
> **Tarefa:** Gerar uma função Python que recebe uma lista de dicionários `orders` e devolve a soma dos valores da chave `total_price`.

**Seu prompt deve:**
1. Explicar que precisa de **código Python** funcional.
2. Definir a assinatura da função (`def total(orders):`).
3. Pedir que o código inclua comentários breves.

---

### Como responder

1. Copie o desafio que quiser (ou todos) e escreva seu prompt logo abaixo.  
2. Envie a mensagem; eu revisarei e apontarei melhorias.  
3. Se quiser, eu mostro a resposta que o modelo produziria (texto ou código) para que você compare com a sua intenção.

---

## 3️⃣ Dica extra – Prompt “Chain‑of‑Thought”

Quando a tarefa é complexa, peça ao modelo **“pense passo a passo”** antes da resposta final:

```
Explique passo a passo como calcular a média ponderada de três notas
e depois mostre o resultado final.
```

Isso costuma melhorar a clareza e a precisão.

---

### 🚀 Seu turno
Escolha um (ou mais) dos desafios acima, escreva o prompt e compartilhe comigo! Estou pronto para dar o feedback e avançarmos no domínio dos LLMs.

### Planejar

Plano de Estudos – Criação de um App de Pedidos (12 semanas)
Semana	Formação / Módulo	Atividades principais	Horas estimadas
1‑2	Inteligência Artificial na Prática – Fundamentos de IA	• Vídeo‑aulas introdutórias (conceitos, prompt‑engineering).
• Exercício: criar seu primeiro prompt no Playground da DIO.	4 h/sem
3	IA na Prática – IA generativa e casos de uso	• Estudo de cases de negócio.
• Mini‑projeto: gerar respostas automáticas para um exemplo de pedido.	4 h
4‑5	Inteligência Artificial Aplicada a Negócios – No‑code & automação	• Tutorial n8n (workflow básico).
• Construir fluxo: formulário Google → planilha de pedidos.	6 h
6‑7	AI Aplicada – IA no atendimento	• Integração LLM via n8n para classificar texto do pedido.
• Testes com 5‑10 exemplos reais do seu negócio.	6 h
8	AI Aplicada – Dashboard e métricas	• Conectar planilha ao Google Data Studio ou Metabase.
• Criar gráficos de volume de pedidos e tempo de resposta.	5 h
9‑10	AI Aplicada – Integração com canais	• Webhooks n8n → WhatsApp Business / Telegram para receber pedidos por mensagem.
• Testar fluxo completo (recebimento → classificação → gravação).	7 h
11	Projeto Final – Montar o app de pedidos	• Revisar todo o workflow.
• Documentar passos (README).
• Publicar workflow n8n (link compartilhável).	5 h
12	Revisão & Próximos passos	• Avaliar resultados (taxa de classificação, tempo de resposta).
• Planejar aprofundamento (JavaScript no n8n ou migração para SaaS).	4 h
Marcos de progresso
Fim da Semana 3: Você domina prompts e gera respostas automáticas.
Fim da Semana 7: Seu workflow classifica pedidos com IA e grava em planilha.
Fim da Semana 10: O app aceita pedidos via WhatsApp/Telegram e alimenta o dashboard.
Fim da Semana 12: Fluxo completo, documentado e pronto para uso no negócio.
Dicas rápidas
Meta de Estudo DIO: registre o plano na ferramenta Meta de Estudo das formações para receber lembretes diários.
Comunidade: participe dos fóruns da Formação “AI Aplicada a Negócios” para tirar dúvidas e compartilhar seu workflow.
Primeiros testes: experimente com pedidos de amigos/família antes de abrir ao público.

### Como foi para você

Muito legal a experiências 
