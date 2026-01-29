# 💣 Campo Minado (Java Swing)

Recriação do clássico jogo desenvolvido em Java. 

<img width="747" height="484" alt="Image" src="https://github.com/user-attachments/assets/426545ea-d1c0-47c8-9211-583f8a18f01f" />

<img width="714" height="445" alt="Image" src="https://github.com/user-attachments/assets/e243172a-bfc0-445a-b089-332d388b4383" />

<img width="722" height="448" alt="Image" src="https://github.com/user-attachments/assets/fae09183-ead0-4099-8ef8-096cf5f57b6c" />

## 🧠 Desafios e Aprendizados

Este projeto foi fundamental para solidificar conceitos de algoritmos e Orientação a Objetos:

* **Recursividade:** Implementação do algoritmo "Flood Fill" (quando você clica em um espaço vazio e ele abre automaticamente todos os vizinhos seguros em cadeia).
* **Matrizes e Grids:** Lógica de posicionamento de minas e cálculo de vizinhança.
* **Tratamento de Exceções:** Controle de erros e fluxo de jogo.
* **Padrão Observer:** Para notificar a interface quando um campo muda de estado (marcado, aberto ou explodido).
* **Testes Unitários:** Uso do **JUnit** para garantir que a lógica dos campos (vizinhos, minas, objetivo) esteja correta antes de criar a interface.

## 🚀 Tecnologias

* **Java** 
* **Java Swing** (Biblioteca gráfica nativa)
* **JUnit 5** (Para testes unitários da lógica)

## 🎮 Como Jogar

1.  **Clique Esquerdo:** Abre o campo.
2.  **Clique Direito:** Marca/Desmarca uma suspeita de mina (Bandeira).
3.  **Objetivo:** Abrir todos os campos que **não** têm minas. Se abrir uma mina, Game Over!

## 💻 Como Executar

1.  Clone o repositório:
    ```bash
    git clone [https://github.com/JaneKaryelle/campo-minado.git](https://github.com/JaneKaryelle/campo-minado.git)
    ```
2.  Abra na sua IDE (IntelliJ / Eclipse).
3.  Execute a classe principal.

---
Desenvolvido por **[Jane Karyelle](https://github.com/JaneKaryelle)**
