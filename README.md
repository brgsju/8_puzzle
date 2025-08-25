# 8_puzzle

🔹 8-Puzzle Solver

Este projeto implementa diferentes algoritmos de Inteligência Artificial para resolver o clássico problema do 8-Puzzle. O objetivo é levar o tabuleiro inicial até o estado final desejado, movimentando as peças em branco (espaço vazio) de forma válida.

📌 Algoritmos Implementados

O projeto contém implementações dos seguintes algoritmos de busca:

DFS (Depth-First Search – Busca em Profundidade)
Explora os nós até a maior profundidade possível antes de retroceder. Pode encontrar soluções rapidamente, mas não garante o caminho mais curto.

IDFS (Iterative Deepening Depth-First Search – Aprofundamento Iterativo)
Combina a estratégia da BFS e DFS. Faz buscas em profundidade com limites crescentes até encontrar a solução, garantindo completude e otimalidade.

BFS (Breadth-First Search – Busca em Largura)
Explora os nós nível por nível, garantindo encontrar a solução mais curta (ótima), mas pode consumir muita memória.

Busca Gulosa (Greedy Best-First Search)
Usa uma heurística para escolher o próximo nó, sempre tentando chegar o mais rápido possível ao objetivo. Nem sempre encontra o caminho mais curto.

A*
Combina custo do caminho real com uma heurística, balanceando exploração e custo estimado. É um dos algoritmos mais eficientes e garante otimalidade se a heurística for admissível.

⚙️ Heurísticas Utilizadas

Distância de Manhattan: Soma das distâncias horizontais e verticais que cada peça está de sua posição final.

Essa heurística foi usada nos algoritmos Guloso e A*.
