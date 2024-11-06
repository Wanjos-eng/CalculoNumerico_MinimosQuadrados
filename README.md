# Questão 3: Interpolação Polinomial/Mínimos Quadrados

## Descrição

Este repositório contém a solução da **Questão 3** do trabalho, focada em **Interpolação Polinomial** e **Mínimos Quadrados**. Nesta questão, utilizamos o método dos mínimos quadrados para ajustar diferentes modelos (reta, parábola, e exponencial) aos dados fornecidos.

O objetivo desta questão é encontrar a melhor representação dos dados por meio de três ajustes diferentes:
- **Ajuste Linear**: \( f(x) = a \cdot x + b \)
- **Ajuste Quadrático**: \( f(x) = a \cdot x^2 + b \cdot x + c \)
- **Ajuste Exponencial**: \( f(x) = a \cdot e^{b \cdot x} \)

Além disso, calculamos o **erro quadrático** de cada ajuste para determinar qual modelo é mais apropriado.

### Imagem da Questão

![Imagem da Questão](docs/Questao3.png)

## Estrutura do Projeto

- **`src/`**: Código-fonte da solução em Python.
  - `main.py`: Arquivo principal contendo a implementação dos ajustes e a visualização gráfica dos dados.
- **`docs/`**: Documentos de apoio, incluindo a imagem da questão.
  - `questao.png`: Imagem fornecida que descreve a questão.

## Como Rodar o Projeto

Para executar o código da solução, siga os passos abaixo:

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git
