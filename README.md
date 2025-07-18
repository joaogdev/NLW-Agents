# NLW Agents – Assistente de Meta para Jogos

Este projeto é um assistente de meta para jogos, desenvolvido durante o NLW Agents. Ele utiliza a API Gemini da Google para responder perguntas sobre estratégias, builds e dicas para jogos populares como Valorant, Counter-Strike e Fortnite.

## Funcionalidades

- Interface web responsiva e moderna
- Integração com a API Gemini (Google AI)
- Respostas em Markdown convertidas para HTML
- Suporte a múltiplos jogos
- Validação de campos e feedback visual ao usuário

## Tecnologias Utilizadas

- **HTML5** e **CSS3** (com reset e estilização customizada)
- **JavaScript** (ES6+)
- [Showdown.js](https://github.com/showdownjs/showdown) para conversão de Markdown em HTML
- API Gemini (Google Generative Language)

## Como usar

1. **Clone o repositório:**
   ```bash
   git clone <url-do-repositorio>
   cd NLW
   ```

2. **Abra o arquivo `index.html` em seu navegador.**

3. **Obtenha uma API KEY do Gemini**  
   - Acesse [Google AI Studio](https://aistudio.google.com/app/apikey) e gere sua chave.

4. **Preencha o formulário:**
   - Insira sua API KEY
   - Selecione o jogo desejado
   - Escreva sua pergunta e clique em "Perguntar"

5. **Veja a resposta da IA**  
   - A resposta aparecerá logo abaixo do formulário, formatada em Markdown.

## Estrutura do Projeto

```
NLW/
├── assets/
│   └── logo.png
├── css/
│   ├── reset.css
│   └── style.css
├── js/
│   └── script.js
├── index.html
└── README.md
```
## Visualização Do Projeto
- https://joaogdev.github.io/NLW-Agents/

## Observações

- Este projeto é apenas para fins educacionais.
- Certifique-se de não expor sua API KEY publicamente.
- O assistente responde apenas perguntas relacionadas aos jogos suportados.

---

Projeto desenvolvido por João Gulherme durante o NLW Agents 🚀
