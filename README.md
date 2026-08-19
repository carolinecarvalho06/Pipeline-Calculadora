# 🧮 Pipeline Calculadora

Projeto desenvolvido para a atividade de **Pipeline com GitHub Actions**, utilizando Python e pytest.

O objetivo é criar uma calculadora simples, realizar testes automatizados para cada operação e executar esses testes automaticamente através de uma pipeline de CI/CD.

## 📋 Funcionalidades

A calculadora possui as seguintes operações:

- ➕ Soma
- ➖ Subtração
- ✖️ Multiplicação
- ➗ Divisão

## 🛠️ Tecnologias utilizadas

- Python 3.12
- Pytest
- Git
- GitHub
- GitHub Actions

## 📁 Estrutura do projeto

```text
Pipeline-Calculadora/
│
├── calculadora.py
│
├── test_soma.py
├── test_subtracao.py
├── test_multiplicacao.py
├── test_divisao.py
│
└── .github/
    └── workflows/
        └── testes.yml
