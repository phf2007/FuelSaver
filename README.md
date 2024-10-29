# FuelSaver

> Um aplicativo Android simples que funcione como uma calculadora de consumo de combustível.

## 📱 Descrição

O **FuelSaver** permite ao usuário calcular o consumo de combustível e o custo da viagem com a distância percorrida em Km, o consumo médio do veículo em Km/L e o preço do combustível por litro.

## 🔧 Funcionalidades

- [x] 1 Tela que fará toda a conta
- [x] Um TextView abaixo do botão que exibe o resultado
- [x] Fórmula simples
- [x] Interface simples e intuitiva
- [ ] Tema claro e escuro (planejado para futuras versões)

## 🚀 Tecnologias Utilizadas

- [x] **Android Studio** (Bumblebee | 2021.1.1)
- [x] **Java** para desenvolvimento
- [x] **ConstraintLayout** para interface responsiva
- [x] **TextView**, **Button** e **EditText**

## 🛠️ Como Rodar o Projeto

Siga os passos abaixo para rodar o projeto localmente:


1. Clone este repositório:
    ```bash
    git clone https://github.com/phf2007/FuelSaver/Fuelsaverdopedro.zip
    ```

2. Abra o projeto no Android Studio.

3. Compile e execute o projeto em um emulador ou dispositivo físico.

## 📂 Estrutura do Projeto

Fuelsaverdopedro
├── app
│   ├── main
│   │   ├── java/br.ulbra.Fuelsaverdopedro
│   │   │   ├── MainActivity.java                  # Atividade principal onde está elaborado as fórmulas
│   │   ├── res
│   │   │   ├── layout
│   │   │   │   ├── activity_main.xml              # Layout da tela principal
│   │   │   └── values
│   │   │       ├── strings.xml                    # Strings usadas no app
│   │   │       ├── colors.xml                     # Cores definidas no projeto
│   └── build.gradle                               # Configuração do Gradle
└── README.md                                      # Este arquivo



## 🎨 Design e Prototipagem 

A interface do app foi criada usando **ConstraintLayout** para manter a responsividade em diferentes tamanhos de tela. 

O design é minimalista e fácil de usar, com foco na simplicidade.

 ## 🖥️ Telas do Aplicativo

**Tela Principal** 

Na tela principal, teremos caixas de textos para colocar o nome do veículo, o número da placa, a distância que será percorrida em Km, o consumo médio do veículo em Km/L e o preço do combustível por litro. a fórmula para o consumo de combustível é: Distância/Consumo; enquanto o custo da viagem é: Combustível necessário*Preço por litro

## 👨‍💻 Desenvolvedores – 
Pedro Henrique Fontes - Desenvolvedor - [GitHub](https://github.com/phf2007)
