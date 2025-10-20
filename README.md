# CalculadoraIMC

Uma aplicação simples em Python para calcular o **IMC (Índice de Massa Corporal)** utilizando **Tkinter**. O projeto permite que o usuário insira seu peso e altura, calcule o IMC e veja a classificação correspondente de forma intuitiva através de uma interface gráfica.

## Funcionalidades

* Cálculo do IMC a partir do peso (kg) e altura (m).
* Classificação do IMC segundo padrões internacionais:

  * Abaixo do peso
  * Peso normal
  * Sobrepeso
  * Obesidade grau I
  * Obesidade grau II
  * Obesidade grau III
* Interface gráfica simples e interativa com **Tkinter**.
* Mensagens de alerta em caso de entrada inválida.

## Pré-requisitos

* Python 3.x instalado
* Biblioteca `tkinter` (geralmente já incluída no Python)

## Como usar

1. Clone o repositório:

```bash
git clone https://github.com/marinakallybo/CalculadoraIMC.git
```

2. Entre na pasta do projeto:

```bash
cd .\CalculadoraIMC\
```

3. Execute o script principal:

```bash
python main.py
```

4. Insira seu **peso** e **altura** nos campos correspondentes e clique em **Calcular IMC**.
5. Uma janela exibirá o seu IMC e a classificação correspondente.

## Exemplo de Uso

![Exemplo da CalculadoraIMC](<img width="339" height="299" alt="image" src="https://github.com/user-attachments/assets/74190a48-bc3b-49e8-bcc0-f0a4bbc59d55" />
)

## Estrutura do Projeto

```
CalculadoraIMC/
│
├── main.py          # Script principal com a interface Tkinter
└── README.md        # Documentação do projeto
```

