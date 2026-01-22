````md
# 🔢 Numerals

**Numerals** is a minimalist number-guessing game inspired by **Wordle**, developed for **educational purposes** using **HTML, CSS, and Vanilla JavaScript**.

**Numerals** é um jogo minimalista de adivinhação de números inspirado no **Wordle**, desenvolvido com fins **educacionais**, utilizando **HTML, CSS e JavaScript puro**.

---

## 🎯 Project Objective | Objetivo do Projeto

- Practice DOM manipulation  
- Understand game state management  
- Apply algorithmic reasoning  
- Reinforce separation of concerns (HTML / CSS / JS)  
- Build a complete mini-project without frameworks  

---

- Praticar manipulação do DOM  
- Compreender gerenciamento de estado do jogo  
- Aplicar raciocínio algorítmico  
- Reforçar separação de responsabilidades (HTML / CSS / JS)  
- Desenvolver um mini-projeto completo sem frameworks  

---

## 🎮 Game Rules | Regras do Jogo

- A random **5-digit number** is generated at the start of the game  
- The player has **4 attempts** to guess the number  
- Each guess must contain **exactly 5 numeric digits**  
- After each guess, feedback is provided for every digit  
- The game ends immediately when the number is guessed correctly  
- If all attempts are used, the game ends with **Game Over**  

---

- Um número aleatório de **5 dígitos** é gerado no início do jogo  
- O jogador possui **4 tentativas**  
- Cada tentativa deve conter **exatamente 5 números**  
- Após cada tentativa, há um feedback visual para cada dígito  
- O jogo termina imediatamente ao acertar o número  
- Caso todas as tentativas se esgotem, ocorre **Game Over**  

---

## 🟩 Feedback System | Sistema de Feedback

| Status   | Meaning (EN)                              | Significado (PT)                         |
|--------|--------------------------------------------|------------------------------------------|
| Correct | Correct digit in the correct position     | Dígito correto na posição correta        |
| Present | Digit exists but is in the wrong position | Dígito existe, mas está em outra posição |
| Absent  | Digit does not exist in the number        | Dígito não existe no número              |

---

## 🧠 Game Logic | Lógica do Jogo

1. Generate a random number when the page loads  
2. Initialize game state (attempts, current row, game status)  
3. On each guess:
   - Validate input
   - Compare with the secret number
   - Apply visual feedback
   - Update attempt counter
4. Check win or loss conditions  

---

1. Gerar um número aleatório ao carregar a página  
2. Inicializar o estado do jogo (tentativas, linha atual, status)  
3. A cada tentativa:
   - Validar entrada
   - Comparar com o número secreto
   - Aplicar feedback visual
   - Atualizar o contador de tentativas
4. Verificar condições de vitória ou derrota  

---

## 🧩 Project Structure | Estrutura do Projeto

```text
numerals/
│
├── easy.html        # Easy mode
├── medium.html     # Medium mode
├── hard.html       # Hard mode
│
├── css/
│   └── style.css   # Global styles and themes
│
├── img/
│   └── favicon.png
│
└── README.md
````

---

## 🖥️ Technologies | Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript (ES6)
* Font Awesome

---

## 🌙 Dark Mode | Modo Escuro

* Theme can be toggled using the moon icon
* Theme preference is stored in `localStorage`

---

* O tema pode ser alternado através do ícone de lua
* A preferência do tema é salva no `localStorage`

---

## 🧪 Input Validation | Validação de Entrada

* Only numeric input is accepted
* Input length is strictly enforced
* Invalid inputs do not consume attempts

---

* Apenas números são aceitos
* O tamanho da entrada é rigidamente validado
* Entradas inválidas não consomem tentativas

---

## 🔄 Restart Behavior | Reinício do Jogo

* Restart reloads the page
* A new number is generated every time

---

* Reiniciar recarrega a página
* Um novo número é gerado a cada reinício

---

## 🚧 Scope & Limitations | Escopo e Limitações

* No frameworks
* No backend
* No database
* Focus on logic clarity and learning

---

* Sem frameworks
* Sem backend
* Sem banco de dados
* Foco em clareza lógica e aprendizado

---

## 📚 Educational Purpose | Propósito Educacional

This project was designed to reinforce:

* Conditional logic
* Array manipulation
* Loop control
* DOM traversal
* State management

---

Este projeto foi desenvolvido para reforçar:

* Lógica condicional
* Manipulação de arrays
* Controle de loops
* Manipulação do DOM
* Gerenciamento de estado

---

## 📄 License | Licença

Free for learning, experimentation, and educational use.

Livre para estudo, experimentação e uso educacional.
