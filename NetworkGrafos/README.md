# Rede Social com NetworkX

Este projeto implementa uma rede social fictícia em Python usando a biblioteca `networkx`, com visualização gráfica em `matplotlib`.

## Objetivo

O script modela uma rede de amizades entre pessoas e realiza operações comuns em grafos, como:

- criação de um grafo não direcionado;
- visualização da rede;
- cálculo do grau de cada vértice;
- identificação do usuário mais conectado;
- busca de caminhos mínimos entre dois usuários;
- remoção de uma aresta e análise do impacto na conectividade;
- sugestão de amizades com base em amigos em comum.

## Estrutura do grafo

A rede inclui pessoas como Ana, Bruno, Carla, Diego, Eduardo, Fernanda, Gabriel e Helena, conectadas por arestas representando amizades.

## Funcionalidades implementadas

1. Construção do grafo
2. Visualização da rede social
3. Cálculo do grau de cada usuário
4. Descoberta do usuário mais conectado
5. Cálculo do caminho mais curto entre Ana e Helena
6. Remoção da amizade entre Carla e Fernanda
7. Sugestões de amizade por amigos em comum

## Requisitos

- Python 3.x
- `networkx`
- `matplotlib`

## Instalação

```bash
pip install networkx matplotlib
```

## Como executar

No diretório do projeto, execute:

```bash
python rede_social
```

Se o arquivo estiver em uma pasta específica, use:

```bash
python NetworkGrafos/rede_social
```

## Observações

- O código usa `plt.show()`, então em ambientes sem interface gráfica pode ser necessário configurar o backend do matplotlib ou salvar a imagem em vez de exibir.
- O grafo é não direcionado, ou seja, a relação de amizade é mútua.

## Exemplo de saída esperada

O programa imprime informações como:

- grau de cada usuário;
- usuário com maior número de conexões;
- menor distância entre Ana e Helena;
- mensagem indicando se ainda existe caminho após a remoção de uma amizade;
- lista de sugestões de amizade com base em amigos em comum.

## Autor

Projeto desenvolvido para fins de estudo de estruturas de dados e grafos.
