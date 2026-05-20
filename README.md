<h1 align="center">
🧬 Algoritmo Genético em Python
</h1>

<p align="center">
Projeto acadêmico desenvolvido utilizando conceitos de Algoritmos Genéticos para encontrar uma sequência secreta de números.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue" />
  <img src="https://img.shields.io/badge/Status-Concluído-green" />
  <img src="https://img.shields.io/badge/Projeto-Acadêmico-orange" />
</p>

---

# 📌 Objetivo

O objetivo deste projeto é implementar um **Algoritmo Genético** capaz de encontrar uma sequência secreta composta por:

- 10 números
- valores entre 1 e 20
- sem repetição
- em ordem crescente

O algoritmo utiliza técnicas inspiradas na evolução natural para evoluir soluções ao longo das gerações até encontrar a sequência ideal.

---

# 🧬 Sobre Algoritmos Genéticos

Os Algoritmos Genéticos são técnicas de otimização inspiradas na teoria da evolução de Charles Darwin.

A ideia principal consiste em:

1. Criar uma população de soluções aleatórias
2. Avaliar quais soluções são melhores
3. Selecionar os melhores indivíduos
4. Realizar cruzamentos entre eles
5. Aplicar mutações
6. Repetir o processo até encontrar uma solução satisfatória

---

# ⚙️ Funcionamento do Projeto

O algoritmo segue as seguintes etapas:

## 1️⃣ População Inicial

São gerados indivíduos aleatórios contendo:

- 10 números únicos
- entre 1 e 20
- ordenados em ordem crescente

### Exemplo

```python
[1, 3, 5, 7, 9, 10, 12, 15, 18, 20]
