# ✅ To-Do List Acessível · Organização Pessoal

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Acessibilidade](https://img.shields.io/badge/WCAG_2.1-AA-4c1?style=for-the-badge)

Um aplicativo de lista de tarefas (**To-Do List**) construído com foco em **acessibilidade**, **design responsivo** e **código limpo**. Ideal para organização pessoal, o sistema permite adicionar, concluir, remover e filtrar tarefas por prioridade, tudo com uma interface intuitiva e feedback para leitores de tela.

---

## 📋 Funcionalidades

- ✅ **Adicionar tarefas** com descrição e prioridade (Alta, Média, Baixa)
- 🎯 **Marcar como concluída** via checkbox (com estilo riscado)
- ❌ **Remover tarefas** individualmente
- 🧹 **Limpar todas as tarefas concluídas** com um clique
- 📊 **Contador dinâmico** de tarefas totais e concluídas
- 🎨 **Estilização condicional** por prioridade (cores distintas na borda e badge)
- ♿ **Totalmente acessível**: navegação por teclado, leitor de tela (ARIA live regions), labels semânticas
- 📱 **Design responsivo** (funciona em dispositivos móveis, tablets e desktops)

---

## 🚀 Demonstração ao Vivo

Você pode testar a aplicação agora mesmo clicando no link abaixo (deploy na Vercel):

👉 **[Acessar To-Do List Acessível](https://seu-projeto.vercel.app)**  
*(substitua pelo link real após o deploy)*

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Finalidade |
|------------|------------|
| **HTML5**  | Estrutura semântica e acessível |
| **CSS3**   | Estilização moderna, responsividade e transições |
| **JavaScript (ES6+)** | Lógica de manipulação do DOM, estado da aplicação e interatividade |
| **ARIA / WCAG** | Recursos de acessibilidade para leitores de tela e navegação por teclado |

Nenhuma dependência externa ou framework — **puro HTML, CSS e JavaScript**.

---

## 📁 Estrutura do Projeto
📦 todo-list-acessivel
┣ 📄 index.html # Todo o código (HTML, CSS e JS) em um único arquivo
┗ 📄 README.md # Documentação do projeto

O arquivo `index.html` é auto-contido e pronto para ser servido em qualquer hospedagem estática.

---

## ⚙️ Como Executar Localmente

1. **Clone o repositório** ou faça o download do arquivo `index.html`.
2. Abra o arquivo `index.html` diretamente no seu navegador favorito.
3. Pronto! A aplicação estará funcionando.

*Não é necessário servidor local, mas você pode usar extensões como "Live Server" no VSCode para uma experiência melhor.*

---

## 🌐 Deploy na Vercel (ou qualquer hospedagem estática)

1. Crie um repositório no GitHub e faça o upload do arquivo `index.html`.
2. Acesse [Vercel](https://vercel.com) e importe o repositório.
3. A Vercel detectará automaticamente o arquivo HTML e fará o deploy.
4. Copie a URL fornecida e compartilhe!

*Também funciona perfeitamente no Netlify, GitHub Pages, Render ou qualquer serviço de hospedagem estática.*

---

## ♿ Acessibilidade (WCAG 2.1)

Este projeto foi desenvolvido com forte atenção às diretrizes de acessibilidade:

- **Labels semânticas**: todos os campos possuem `<label>` associado (inclusive labels visíveis apenas para leitores de tela).
- **Navegação por teclado**: todos os elementos interativos são focáveis e possuem indicador visual (`:focus-visible`).
- **ARIA Live Regions**: mudanças na lista (adição, conclusão, remoção) são anunciadas automaticamente para tecnologias assistivas.
- **Roles ARIA**: uso de `role="list"`, `role="listitem"`, `role="status"` para reforçar a semântica.
- **Contraste adequado**: as cores foram escolhidas para garantir legibilidade (conforme WCAG AA).

Testado com:
- Leitor de tela NVDA (Windows)
- VoiceOver (macOS)
- Navegação apenas por teclado (Tab, Enter, Espaço)

---

## 🧠 Reflexão do Desenvolvedor

> Este projeto foi uma oportunidade de aprofundar conceitos de **acessibilidade web** e **arquitetura de front-end**. Aprendi que acessibilidade não é um complemento, mas parte essencial da experiência do usuário. Além disso, a organização do código em funções modulares tornou a manutenção e a evolução muito mais simples.
>
> O uso de uma `aria-live` region para anunciar mudanças foi um diferencial que trouxe um feedback imediato para usuários de leitores de tela, algo frequentemente negligenciado em aplicações simples.

---

## 📝 Licença

Este projeto está sob a licença **MIT**. Sinta-se livre para usar, modificar e distribuir como desejar.

---

## 👤 Autor

Desenvolvido por [Seu Nome] como parte de um desafio prático de desenvolvimento front-end com foco em acessibilidade e usabilidade.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/seu-perfil)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/seu-usuario)

---

⭐ **Se este projeto te ajudou, considere dar uma estrela no repositório!** ⭐
