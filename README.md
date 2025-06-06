# 🎓 Java Student Grade Calculator

Este é um projeto simples em Java que calcula a nota final de um estudante com base em três avaliações. O programa também verifica se o aluno foi aprovado ou reprovado.

## 🧠 Conceitos Utilizados

- Programação Orientada a Objetos (POO)
- Estrutura condicional
- Entrada de dados via terminal
- Cálculos e formatação de ponto flutuante
- Encapsulamento da lógica na classe `Student`

## 📂 Estrutura do Projeto
src/
├── application/
│ └── Program.java
└── entities/
└── Student.java
## ✅ Funcionalidades

- Entrada do nome do aluno e das três notas.
- Cálculo automático da nota final.
- Verificação se o aluno passou (nota ≥ 60).
- Exibição de quantos pontos faltam, caso o aluno não tenha alcançado a média.

## ▶️ Como Executar

1. Compile os arquivos:
   ```bash
   javac application/Program.java entities/Student.java
2. Execute o programa:
   java application.Program
3. Digite os dados solicitados no terminal.

💡 Exemplo de Entrada/Saída:
    Alex Green
  27.00
  31.00
  32.00
  FINAL GRADE = 90.00
  PASS

  Maria Brown
  17.00
  20.00
  15.00
  FINAL GRADE = 52.00
  FAILED
  MISSING 8.00 POINTS

🛠️ Classe Student
A classe Student deve conter:

Atributos:

name: nome do aluno

grade1, grade2, grade3: notas das avaliações

Métodos:

finalGrade(): retorna a soma das três notas

missingPoints(): calcula quantos pontos faltam para alcançar a média 60

toString(): pode ser implementado para formatar a saída de forma personalizada

📄 Licença
Projeto educacional para prática de lógica condicional e orientação a objetos em Java.
