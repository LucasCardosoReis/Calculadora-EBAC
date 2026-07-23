Markdown# 🧮 Projeto Calculadora em Python & Shell Script

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Bash](https://img.shields.io/badge/Shell_Script-GNU_Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 📌 Sobre o Projeto

Este projeto foi desenvolvido como **atividade prática do curso de Analista de Dados da EBAC**. 

A aplicação consiste em uma calculadora interativa desenvolvida em um notebook **Python (Jupyter Notebook)**, integrada a um **Script Shell (Bash)** para automatizar a execução do projeto em ambientes Linux.

---

## 🎯 Objetivo

O objetivo deste projeto é praticar conceitos fundamentais de programação em Python, automação via scripts Bash no Linux, controle de versão com Git e publicação de projetos no GitHub.

---

## 🚀 Funcionalidades

- ➕ **Adição (+)**
- ➖ **Subtração (-)**
- ✖️ **Multiplicação (*)**
- ➗ **Divisão (/)** (com validação para evitar divisão por zero)
- 🔄 **Menu Interativo**: Permite realizar múltiplos cálculos em sequência até que o usuário escolha a opção de sair[cite: 3].

---

## 🛠️ Tecnologias Utilizadas

- **Python 3 / Jupyter Notebook** — Lógica do programa e operações matemáticas[cite: 3].
- **Shell Script (Bash)** — Automação da execução do arquivo no terminal[cite: 2].
- **Linux (Ubuntu / WSL)** — Ambiente de desenvolvimento e execução de comandos.
- **Git & GitHub** — Versionamento e hospedagem do código.

---

## 💻 Exemplo de Utilização

```text
1. Adição (+)
2. Subtração (-)
3. Multiplicação (*)
4. Divisão (/)
5. Sair do programa

Escolha a opção de (1-5): 2

Digite o primeiro número: 150000
Digite o segundo número: 10

[RESULTADO] A subtração de 150000.0 - 10.0 é igual a: 149990.0
(Fonte da execução no terminal)[cite: 3]📂 Estrutura do RepositórioPlaintextprojetocalculadora/
├── Calcudora-Python.ipynb # Notebook com a lógica da calculadora em Python
├── calculadora.sh         # Script Bash para execução do notebook
├── comandos.txt          # Anotações dos comandos Linux utilizados
├── .gitattributes         # Configuração de normalização de texto
└── README.md              # Documentação do projeto
(Estrutura de arquivos baseada nos arquivos do repositório)  🔧 Como ExecutarAbra o terminal e navegue até a pasta do projeto:Bashcd /caminho/para/projetocalculadora
Conceda permissão de execução ao script Shell:Bashchmod 744 calculadora.sh
(Você pode verificar as permissões com ls -l calculadora.sh)  Execute o programa:Bash./calculadora.sh
(O script executará automaticamente o notebook Python no terminal)[cite: 2].💡 Conceitos AplicadosDurante o desenvolvimento do projeto, foram praticados os seguintes tópicos de programação:Conversão de Tipos de Dados (float(), input())[cite: 3]Estruturas Condicionais (if, elif, else)[cite: 3]Laços de Repetição (while True com instrução break)[cite: 3]Tratamento de Exceções (validação de opção inválida e divisão por zero)[cite: 3]Automação via Terminal (gerenciamento de permissões com chmod e execução de scripts Bash)  🎓 Projeto desenvolvido durante a jornada do curso de Analista de Dados da EBAC.
