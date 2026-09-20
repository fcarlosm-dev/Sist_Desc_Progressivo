# 💰 Sist_Desc_Progressivo

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Reposit%C3%B3rio-181717?style=for-the-badge&logo=github&logoColor=white)
![Energia](https://img.shields.io/badge/Feito%20com-Energia%20%E2%9A%A1-FFD700?style=for-the-badge)

> 🛒 Sistema em Python que aplica **Desconto Progressivo** conforme o valor total da compra, oferecendo uma experiência simples, validada e amigável ao usuário.

---

## 📌 Índice

-[Sobre o Projeto](#-sobre-o-projeto)
-[Regras de Desconto](#-regras-de-desconto)
-[Funcionalidades](#-funcionalidades)
-[Tecnologias Utilizadas](#-tecnologias-utilizadas)
-[Como Executar](#-como-executar)
-[Exemplo de Uso](#-exemplo-de-uso)
-[Estrutura do Projeto](#-estrutura-do-projeto)

---

## 🎯 Sobre 

O **Sist_Desc_Progressivo** é um sistema desenvolvido em **Python** que calcula o desconto aplicado a uma compra com base no valor total informado pelo usuário. O sistema aplica **descontos progressivos**, ou seja, quanto maior o valor da compra, maior o percentual de desconto.

### ✨ Objetivo

Fornecer uma solução simples, interativa e confiável para cálculo de descontos progressivos em vendas, sendo útil para **PDVs, e-commerces e Sistemas de caixa**, permitindo que o cliente visualize claramente o percentual aplicado, o valor economizado e o total a pagar.

---

## 📊 Regras de Desconto

O sistema aplica as faixas de desconto conforme o valor total da compra:

| 💵 Valor da Compra                 | 🎁 Desconto Aplicado |
|:-----------------------------------:|:--------------------:|
| Menor que **R$ 200,00**             | **5%** |
| Entre **R$ 200,00** e **R$ 299,99** | **10%** |
| Maior ou igual a **R$ 300,00**      | **15%** |

---

## ⚙️ Funcionalidades

✅ **Entrada de dados** — apenas valores numéricos positivos são aceitos.
✅ **Cálculo automático** do percentual e valor do desconto.
✅ **Exibição do valor final** a ser pago pelo cliente.
✅ **Repetição de compras** — o sistema pergunta se o usuário deseja informar um novo valor.
✅ **Tratamento de erros** — entradas inválidas solicitam nova digitação.
✅ **Dicas econômicas** — informa quanto falta para o cliente atingir a próxima faixa de desconto.

### 🚫 Restrições

❌ **Não aceita valores negativos.**
🔢 **Usa ponto (`.`)** como separador decimal. Exemplo: `199.99`

---

## 🧰 Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)

- 🐍 **Python 3.14-64** — Linguagem principal do projeto.
- 💻 **Visual Studio Code** — Editor recomendado.
- 🔧 **Git e GitHub** — Controle de versão e hospedagem do código.

---

## 🚀 Como Executar

### 📋 Pré-requisitos

- Ter o **Python 3.14-64 ou superior** instalado em sua máquina.
- Verificar a instalação com o comando:

```bash
python --3.14-64
```

### 📥 Passo a passo

1. **Clone o repositório:**

```bash
git clone https://github.com/fcarlosm-dev/Sist_Desc_Progressivo.git
```

2. **Acesse a pasta do projeto:**

```bash
cd Sist_Desc_Progressivo
```

3. **Execute o programa:**

```bash
python FlavioMartins_Ag6_DS_I.py
```

4. **Siga as instruções na tela:**

```text
Digite o valor total da compra: R$ 250.00
```

5. **Informe se deseja continuar:**

```text
Deseja informar novo valor de compra? S / N 
```

---

## 💻 Exemplo de Uso

```text
==================================================
       SISTEMA DE DESCONTO PROGRESSIVO
==================================================

Regras de desconto:
- Compras abaixo de R$ 200,00: 5% de desconto
- Compras entre R$ 200,00 e R$ 299,99: 10% de desconto
- Compras acima de R$ 300,00: 15% de desconto
==================================================

Digite o valor total da compra: R$ 250.00

==================================================
          RESULTADO DO CÁLCULO
==================================================
Valor total da compra:     R$ 250.00
Percentual de desconto:    10%
Valor do desconto:         R$ 25.00
Valor a pagar:             R$ 225.00
==================================================

💡 Compre mais R$ 50.00 para ganhar 15% de desconto!

Deseja informar novo valor de compra? (S/N): N

==================================================
   Agradeçemos sua visita. Volte sempre!!
==================================================
```

---

## 📁 Estrutura do Projeto

```text
Sist_Desc_Progressivo/
│
├── sist_desc_progressivo.py   # Código-fonte principal
├── README.md                  # Documentação do projeto
                  
---

## 🏷️ Badges do Projeto

![Made in Brazil](https://img.shields.io/badge/Made%20in-Brazil%20%F0%9F%87%A7%F0%9F%87%B7-green?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)

---

## 👨‍💻 Autor

Desenvolvido por **Flavio Martins**

[![GitHub](https://img.shields.io/badge/GitHub-Seu%20Perfil-181717?style=for-the-badge&logo=github)](https://github.com/fcarlosm-dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Seu%20Perfil-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/flaviocarlosmartins)

---

  Se este projeto é útil para voce e faz sentido, deixe sua ⭐ no repositório! Obrigado.

