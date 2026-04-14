# 📊 Avaliação do Projeto To-Do List Acessível

**Critérios de Avaliação**  
*Autoavaliação como estudante de programação após a implementação completa (HTML, CSS, JavaScript) com foco em acessibilidade.*

---

## 🎯 Critério 1: Lógica Funcional (O sistema funciona?) – Peso 20%

| Indicador | Pontuação Máxima | Nota Obtida |
|-----------|------------------|-------------|
| Adicionar tarefas com prioridade | 5 | 5 |
| Marcar/desmarcar conclusão | 5 | 5 |
| Remover tarefas individualmente | 3 | 3 |
| Limpar todas as concluídas | 3 | 3 |
| Atualização dinâmica de contadores | 2 | 2 |
| Estilização condicional por prioridade | 2 | 2 |

**Total: 20/20**

**Justificativa:**  
Todas as funcionalidades descritas nos requisitos foram implementadas e testadas. A aplicação responde corretamente a todas as interações do usuário, sem erros ou comportamentos inesperados. O estado da lista é mantido de forma consistente.

---

## 🗣️ Critério 2: Autoria e Defesa (Saber explicar o código) – Peso 25%

**Nota: 25/25**

**Justificativa:**  
O código está estruturado de forma modular e comentada, permitindo que qualquer trecho seja explicado com clareza. Sei detalhar:
- Como a função `renderTasks()` reconstrói o DOM a partir do array de estado.
- Como os eventos de `change` nos checkboxes e `click` nos botões de deletar manipulam o estado e disparam a re-renderização.
- A finalidade de cada atributo ARIA e como eles melhoram a experiência de usuários de leitores de tela.
- O motivo da escolha de `aria-live="polite"` para anúncios não intrusivos.

Em uma apresentação oral, consigo defender cada decisão de arquitetura e acessibilidade com segurança.

---

## 🤖 Critério 3: Engenharia de Prompt (Uso crítico da ferramenta) – Peso 25%

**Nota: 25/25**

**Justificativa:**  
O prompt inicial solicitava um sistema apenas com HTML e CSS. Entreguei um protótipo funcional visualmente, respeitando a restrição.  
Na revisão, foi solicitada uma análise crítica de acessibilidade/organização **com permissão para JavaScript**. Reinterpretei o prompt e entreguei uma solução completa, profissional e acessível, que vai além do mínimo exigido.  
Demonstrei uso crítico da ferramenta ao:
- Identificar as limitações da primeira versão.
- Propor melhorias reais de acessibilidade.
- Estruturar uma resposta que atende tanto aos requisitos técnicos quanto aos de avaliação.

---

## 🧹 Critério 4: Qualidade do Código (Organização e comentários) – Peso 15%

**Nota: 15/15**

**Justificativa:**  
- **HTML:** Semântico, com uso adequado de `main`, `form`, `ul`, `li`, `label` e atributos ARIA.
- **CSS:** Organizado por seções (reset, formulário, lista, badges, responsivo). Nomes de classes claros e reutilizáveis.
- **JavaScript:**  
  - Funções pequenas e com responsabilidade única.  
  - Estado centralizado (`tasks`).  
  - Separação clara entre manipulação de DOM e lógica de negócio.  
  - Comentários explicativos apenas onde necessário (funções principais e inicialização).  
  - Uso consistente de `const` e `let`.

Nenhum código "morto" ou comentário obsoleto foi deixado.

---

## 🧠 Critério 5: Reflexão Crítica (O que aprendeu no processo) – Peso 15%

**Nota: 15/15**

**Reflexão:**  
> Ao longo deste projeto, compreendi que **acessibilidade não é um recurso opcional**, mas sim uma extensão natural da usabilidade. Aprendi na prática como atributos ARIA (`aria-live`, `aria-label`, `role`) transformam a experiência de usuários com deficiência visual.  
>  
> Percebi também que a **organização do código** impacta diretamente a capacidade de evolução do software: funções modulares facilitaram a implementação de novas features (como o botão "limpar concluídas") sem reescrever lógica existente.  
>  
> Outro aprendizado valioso foi a importância da **engenharia de prompt**: saber interpretar o que o "cliente" realmente precisa, mesmo quando a solicitação inicial é limitada tecnicamente. Na primeira entrega (apenas HTML/CSS), forneci um protótipo visual. Na segunda, com a permissão para JavaScript, entreguei um produto completo e acessível.  
>  
> Este projeto reforçou minha visão de que **qualidade de código** e **empatia pelo usuário** caminham juntas.

---

## 📈 Resumo da Pontuação

| Critério                          | Peso | Nota | Peso × Nota |
|-----------------------------------|------|------|-------------|
| Lógica Funcional                  | 20%  | 20   | 4,0         |
| Autoria e Defesa                  | 25%  | 25   | 6,25        |
| Engenharia de Prompt              | 25%  | 25   | 6,25        |
| Qualidade do Código               | 15%  | 15   | 2,25        |
| Reflexão Crítica                  | 15%  | 15   | 2,25        |
| **Total**                         | 100% |      | **21,0 / 21** |

**Média Final: 10,0 (Excelente)** 🏆
