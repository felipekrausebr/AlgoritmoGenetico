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
```

---

## 2️⃣ Função de Aptidão (Fitness)

A função fitness calcula quantos números do indivíduo estão presentes na sequência secreta.

### Exemplo

```python
Sequência alvo:
[1,2,3,4,5,6,7,8,9,10]

Indivíduo:
[1,3,5,7,11,12,13,14,15,16]

Fitness = 4
```

---

## 3️⃣ Seleção

Foi utilizada a técnica de **Seleção por Torneio**.

O algoritmo:

- escolhe dois indivíduos aleatórios
- compara os fitness
- seleciona o melhor indivíduo

---

## 4️⃣ Cruzamento

O cruzamento mistura genes de dois pais para gerar um novo indivíduo.

### Exemplo

```python
Pai 1 = [1,2,3,4,5]
Pai 2 = [6,7,8,9,10]

Filho = [1,2,3,9,10]
```

---

## 5️⃣ Mutação

A mutação altera aleatoriamente um gene do indivíduo.

Essa etapa ajuda o algoritmo a:

- evitar estagnação
- explorar novas possibilidades
- aumentar diversidade genética

---

## 6️⃣ Elitismo

O melhor indivíduo da geração é preservado para a próxima geração.

Isso garante que boas soluções não sejam perdidas durante a evolução.

---

# 🛠️ Tecnologias Utilizadas

- Python 3
- Biblioteca `random`

---

# ▶️ Como Executar

## 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

---

## 2. Acesse a pasta do projeto

```bash
cd seu-repositorio
```

---

## 3. Execute o projeto

```bash
python main.py
```

---

# 📊 Exemplo de Saída

```bash
Geração 0
Melhor indivíduo: [1, 3, 5, 7, 8, 10, 12, 15, 18, 20]
Fitness: 5

Geração 1
Fitness: 6

Geração 15
Fitness: 9

Geração 22
Fitness: 10

✅ SOLUÇÃO ENCONTRADA!
```

---

# 📚 Conceitos Aplicados

Durante o desenvolvimento deste projeto foram aplicados os seguintes conceitos:

- Computação Evolutiva
- Inteligência Artificial
- Algoritmos Genéticos
- Busca Heurística
- Otimização

---

# 🎯 Melhorias Futuras

Algumas melhorias que podem ser implementadas futuramente:

- Interface gráfica
- Gráfico da evolução do fitness
- Seleção por roleta
- Mutação adaptativa
- Diferentes estratégias de cruzamento
- Exportação de resultados

---

# 📁 Estrutura do Projeto

```bash
algoritmo-genetico/
│
├── main.py
├── README.md
└── requirements.txt
```

---

# 👨‍🎓 Autor

Projeto desenvolvido por **Felipe Krause** para fins acadêmicos e aprendizado em Inteligência Artificial e Algoritmos Genéticos.

---

# 📌 Considerações Finais

Este projeto teve como objetivo aplicar na prática os conceitos vistos em sala de aula relacionados à Computação Evolutiva e Inteligência Artificial.

A implementação permitiu compreender melhor como algoritmos inspirados na natureza podem ser utilizados para resolver problemas de busca e otimização.
