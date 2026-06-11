Como vi o código HTML, CSS e JavaScript do projeto, o README pode ser mais específico sobre o que ele realmente faz. O projeto possui campos para peso e altura, botão de cálculo, exibição dinâmica do resultado e uma tabela de classificação do IMC.  

# 📊 Calculadora de IMC

Uma calculadora de IMC (Índice de Massa Corporal) desenvolvida com **HTML, CSS e JavaScript**, permitindo que o usuário informe seu peso e altura para descobrir sua classificação corporal de forma rápida e intuitiva.

## 🚀 Funcionalidades

* Inserção de peso em quilogramas (KG)
* Inserção de altura em centímetros (CM)
* Cálculo automático do IMC
* Exibição dinâmica do resultado
* Classificação do IMC de acordo com a tabela padrão
* Validação para impedir campos vazios
* Design responsivo para dispositivos móveis

---

## 🛠 Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript (Vanilla JS)

---

## 📂 Estrutura do Projeto

```bash
calculadora-imc/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 📖 Como Funciona

1. O usuário informa:

   * Peso (KG)
   * Altura (CM)

2. Ao clicar em **Calcular**, o sistema:

   * Verifica se os campos foram preenchidos.
   * Calcula o IMC.
   * Exibe os dados informados.
   * Mostra a classificação correspondente.

3. Caso algum campo esteja vazio, é exibida uma mensagem de erro.

---

## 🧮 Fórmula do IMC

```text
IMC = Peso / Altura²
```

Exemplo:

```text
Peso: 70 kg
Altura: 1,75 m

IMC = 70 / (1,75 × 1,75)
IMC = 22,86
```

Resultado:

```text
Peso Normal
```

---

## 📋 Tabela de Classificação

| IMC          | Classificação           |
| ------------ | ----------------------- |
| Menos de 17  | Muito abaixo do peso    |
| 17 a 18,49   | Abaixo do peso          |
| 18,5 a 24,99 | Peso Normal             |
| 25 a 29,99   | Acima do peso           |
| 30 a 34,99   | Obesidade I             |
| 35 a 39,99   | Obesidade II (severa)   |
| Acima de 40  | Obesidade III (mórbida) |

---

## 🎨 Interface

O projeto apresenta:

* Layout minimalista
* Campos destacados em rosa
* Resultado exibido dinamicamente
* Tabela visual para consulta rápida
* Responsividade para telas menores

---

## ▶️ Executando o Projeto

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/calculadora-imc.git
```

2. Entre na pasta:

```bash
cd calculadora-imc
```

3. Abra o arquivo `index.html` no navegador.

---

## 🎯 Objetivo

Este projeto foi desenvolvido para praticar:

* Manipulação do DOM
* Eventos em JavaScript
* Estruturas condicionais
* Cálculos matemáticos
* Responsividade com CSS
* Organização de projetos Front-End

---

## 👨‍💻 Autor

**Gustavo Santos**

Projeto desenvolvido para fins de estudo e prática de desenvolvimento web.
