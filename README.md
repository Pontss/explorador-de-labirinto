# Explorador de Labirintos

Projeto desenvolvido para a disciplina de Teoria dos Grafos, com o objetivo de aplicar e comparar os algoritmos de busca BFS (Busca em Largura) e DFS (Busca em Profundidade).

O sistema permite gerar labirintos automaticamente e visualizar como cada algoritmo percorre os caminhos até encontrar a saída.

## Funcionalidades

- Geração automática de labirintos.
- Seleção de diferentes tamanhos de labirinto.
- Execução dos algoritmos BFS e DFS.
- Visualização animada dos caminhos explorados.
- Identificação do caminho encontrado até a saída.
- Comparação dos resultados entre os algoritmos.
- Exibição de informações como tempo de execução e quantidade de posições visitadas.
- Controle da velocidade da animação.

## Algoritmos utilizados

### BFS (Busca em Largura)

Explora o labirinto por níveis, verificando primeiro as posições mais próximas da entrada antes de avançar para as mais distantes.

Esse algoritmo garante encontrar o menor caminho possível em quantidade de movimentos.

### DFS (Busca em Profundidade)

Explora um caminho até não conseguir avançar. Quando encontra um bloqueio, retorna às posições anteriores e tenta outra direção.

Esse algoritmo encontra um caminho até a saída, mas não garante que seja o menor.

## Tecnologias utilizadas

- Python
- Tkinter
- Algoritmos de busca em grafos
- Teoria dos Grafos

## Como executar

1. Faça o download ou clone este repositório.
2. Certifique-se de ter o Python instalado.
3. Abra a pasta do projeto.
4. Execute o comando:

```bash
python main.py
```

## Experimentos

O projeto também possui um módulo de experimentos para executar testes com diferentes labirintos e comparar o desempenho dos algoritmos BFS e DFS.

Para executar:

```bash
python experimento.py
```

Os resultados são gerados automaticamente na pasta `resultados`.
