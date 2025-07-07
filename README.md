# 🧙‍♀️ Jogo RPG de Tabuleiro com IA 

## Descrição do Projeto

Jogo de tabuleiro interativo jogável diretamente no navegador, onde o jogador assume o controle de um herói que se movimenta em um mapa 5x5 e enfrenta um inimigo controlado por uma Inteligência Artificial.  
O diferencial deste projeto é que o inimigo **reage em tempo real** aos movimentos do herói, utilizando IA generativa via **OpenAI + n8n + FastAPI**, integrados ao frontend em **Vue 3** com **Tailwind CSS**.

O projeto foi desenvolvido como um experimento criativo de **aplicação de IA em jogos web**, com foco em interatividade, acessibilidade e arquitetura modular.

---

## Funcionalidades do Projeto

- 🔁 **Tabuleiro interativo 5x5** com movimentação em tempo real
- 🧍 **Controle do herói** com botões direcionais
- ⚔️ **Sistema de ataque** baseado no tipo de personagem (guerreiro, mago, arqueiro)
- 🧠 **IA inimiga com comportamento dinâmico**, consumindo uma API n8n conectada ao ChatGPT (OpenAI)
- 💬 Respostas e estratégias do inimigo adaptativas conforme a posição do jogador
- 📱 Interface responsiva, com design limpo e escuro
- 🎯 Arquitetura frontend limpa, separada por componentes

---

## Testes de Software

Foram realizados os seguintes testes para garantir a robustez do projeto:

### ✅ Teste de Depuração
- Testes manuais com `console.log` e breakpoints no VSCode para monitorar movimentações e respostas da IA.
- Verificação de limites de movimentação (bordas do tabuleiro).

### ✅ Teste de Funcionamento
- Teste completo dos fluxos de movimento, ataque e resposta da IA em diferentes cenários:
  - Movimentação repetida nos cantos do tabuleiro
  - IA reagindo a cada turno
  - Mudança de tipo de herói

### ✅ Teste de Segurança
- Validação da API do n8n para aceitar apenas requisições POST autenticadas
- CORS controlado no backend
- Sanitização dos dados recebidos antes do envio à IA

---

## Tecnologias e Linguagens

| Tecnologia     | Descrição                              |
|----------------|------------------------------------------|
| `JavaScript`   | Lógica do jogo no frontend (Vue)         |
| `Vue 3`        | Framework reativo usado na interface     |
| `HTML5`        | Estrutura base do app                    |
| `CSS3 + Tailwind` | Estilização com utilitários e responsividade |
| `Node.js`      | Ambiente de execução e build             |
| `n8n`          | Automação e roteamento para IA           |
| `OpenAI`       | Lógica de tomada de decisão da IA inimiga|
| `FastAPI`      | Backend auxiliar com API REST opcional   |

---

## Bibliotecas e Frameworks

<p>
  <img src="https://img.shields.io/badge/-Vue-4FC08D?style=flat&logo=vue.js&logoColor=white" />&nbsp;
  <img src="https://img.shields.io/badge/-Vite-646CFF?style=flat&logo=vite&logoColor=white" />&nbsp;
  <img src="https://img.shields.io/badge/-TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white" />&nbsp;
  <img src="https://img.shields.io/badge/-OpenAI-412991?style=flat&logo=openai&logoColor=white" />&nbsp;
  <img src="https://img.shields.io/badge/-n8n-FF6A3D?style=flat&logo=n8n&logoColor=white" />&nbsp;
  <img src="https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
</p>


---

> ✅ *Projeto pratico e simples desenvolvido em ambiente Windows com terminal Git Bash + PowerShell e totalmente funcional via navegador, sem necessidade de banco de dados.*


