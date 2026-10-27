# 📊 Rede Social com NetworkX

Este projeto implementa uma rede social fictícia em Python utilizando a biblioteca `networkx`, com visualização gráfica por meio de `matplotlib`.

---

## 🎯 Objetivo

O programa modela uma rede de amizades entre pessoas e aplica operações comuns em grafos, incluindo:

- criação de um grafo não direcionado;
- visualização da rede social;
- cálculo do grau de cada vértice;
- identificação do usuário mais conectado;
- busca de caminhos mínimos entre dois usuários;
- remoção de uma aresta e análise do impacto na conectividade;
- sugestão de amizades com base em amigos em comum.

---

## 👥 Estrutura da Rede

A rede é composta por pessoas como Ana, Bruno, Carla, Diego, Eduardo, Fernanda, Gabriel e Helena. As conexões entre os vértices representam relações de amizade e são modeladas como arestas em um grafo não direcionado.

---

## ⚙️ Funcionalidades Implementadas

1. Construção do grafo
2. Visualização da rede social
3. Cálculo do grau de cada usuário
4. Identificação do usuário mais conectado
5. Cálculo do caminho mais curto entre Ana e Helena
6. Remoção da amizade entre Carla e Fernanda
7. Sugestão de amizades com base em amigos em comum

---

## 🧰 Requisitos

- Python 3.x
- `networkx`
- `matplotlib`

---

## 🚀 Instalação

Instale as dependências com o comando:

```bash
pip install networkx matplotlib
```

---

## ▶️ Como Executar

No diretório do projeto, execute:

```bash
python rede_social
```

Se o arquivo estiver localizado em uma pasta específica, utilize:

```bash
python NetworkGrafos/rede_social
```

---

## 📝 Observações

- O código utiliza `plt.show()`. Em ambientes sem interface gráfica, pode ser necessário configurar o backend do `matplotlib` ou salvar a imagem em vez de exibí-la.
- O grafo é não direcionado, o que significa que a relação de amizade é mútua.

---

## 📌 Saída Esperada

Ao executar o programa, são exibidas informações como:

- grau de cada usuário;
- usuário com maior número de conexões;
- menor distância entre Ana e Helena;
- mensagem indicando se ainda existe caminho após a remoção de uma amizade;
- lista de sugestões de amizade com base em amigos em comum.

---

## 👨‍💻 Autor

Projeto desenvolvido para fins de estudo e prática em estruturas de dados e teoria dos grafos.
