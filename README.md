# Calculadora-desperdicio-volume

## 📄 Descrição
Programa em C que calcula o volume inicial de um cilindro, um volume final simplificado e o volume desperdiçado com base no raio e comprimento informados pelo usuário.

## 📌 Funcionalidades
- Cálculo do volume de um cilindro
- Cálculo de um volume final alternativo
- Cálculo do volume desperdiçado
- Entrada de dados pelo usuário

## 🧮 Fórmulas utilizadas
- Volume inicial:  
  V = π * r² * comprimento

- Volume final:  
  V = 2 * r² * comprimento

- Volume desperdiçado:  
  desperdício = volume_inicial - volume_final

## 💻 Exemplo de execução

    Insira o valor do raio: 3
    Insira o valor do comprimento: 10

    O volume inicial é 282.74 
    O volume final é 180.00 
    O volume desperdiçado é 102.74

## ⚙️ Requisitos
- Compilador C (recomendado: gcc)
- Biblioteca matemática (`math.h`)

## ▶️ Como compilar e executar

    gcc main.c -o volume -lm
    ./volume

> O parâmetro `-lm` é necessário para linkar a biblioteca matemática.

## 📚 Conceitos aplicados
- Linguagem C
- Entrada e saída de dados (`scanf`, `printf`)
- Operações matemáticas (`pow`)
- Uso de variáveis do tipo `float`

## 🚀 Possíveis melhorias
- Validação de entrada de dados
- Uso de `double` para maior precisão
- Interface gráfica simples
- Execução em loop para múltiplos cálculos

## ✍️ Autor
Rafael Lima Ribeiro dos Santos
