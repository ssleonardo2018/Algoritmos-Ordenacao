ALUNO: Leonardo S Silva | MAT. : 202422983

# 📊 Algoritmos de Ordenação em Python

Este repositório contém implementações em **Python** de diversos **algoritmos de ordenação** clássicos, cada um com seus comentários explicando **vantagens** e **desvantagens**. O objetivo é fornecer um material simples e didático para quem deseja entender como esses algoritmos funcionam internamente.

---

## ✅ Algoritmos Implementados


🔷 1. Selection Sort (Ordenação por Seleção)
Como funciona:
Pensa que você está escolhendo os menores objetos e colocando em ordem um por um. A cada passo, você acha o menor e coloca na frente.

Exemplo:
Para a lista [5, 3, 8, 6, 2], o algoritmo vai trocando o menor número com o primeiro da parte desorganizada. No fim, tudo estará em ordem.

✅ Vantagens:

Simples de entender e implementar.
Não precisa de memória extra.
❌ Desvantagens:

Lento para listas grandes.
Complexidade: O(n²) (bem lento com muitos dados).


🔷 2. Bubble Sort (Ordenação por Bolha)
Como funciona:
Compara dois números vizinhos e troca se estiverem na ordem errada. Vai fazendo isso até a lista estar ordenada. Como bolhas subindo à superfície, os maiores "flutuam" para o fim.

✅ Vantagens:

Muito fácil de entender.
Ótimo para ensinar lógica de comparação e troca.
❌ Desvantagens:

Extremamente lento para listas grandes.
Complexidade: O(n²).


🔷 3. Insertion Sort (Ordenação por Inserção)
Como funciona:
Imagina que você está organizando cartas na mão. Pega uma carta de cada vez e insere na posição certa entre as já organizadas.

✅ Vantagens:

Funciona muito bem com listas pequenas ou quase ordenadas.
Fácil de implementar.
❌ Desvantagens:

Também lento com listas grandes.
Complexidade: O(n²).


🔷 4. Merge Sort (Ordenação por Mistura)
Como funciona:
Divide a lista em várias partes pequenas, ordena cada parte e depois junta tudo em ordem. Como montar um quebra-cabeça de pedaços já organizados.

✅ Vantagens:

Muito eficiente com listas grandes.
Complexidade: O(n log n).
Estável (não muda a ordem de valores iguais).
❌ Desvantagens:

Usa memória extra (mais espaço na máquina).


🔷 5. Quick Sort (Ordenação Rápida)
Como funciona:
Escolhe um número como referência (chamado de "pivô") e divide a lista em menores, iguais e maiores que ele. Depois faz o mesmo com cada parte.

✅ Vantagens:

Muito rápido na prática.
Complexidade média: O(n log n).
❌ Desvantagens:

Pode ser lento no pior caso (O(n²)).
Instável (pode trocar a ordem de elementos iguais).


🔷 6. Heap Sort
Como funciona:
Transforma a lista em uma estrutura chamada “heap” (tipo uma árvore de prioridades), e vai retirando os maiores ou menores elementos para ordenar.

✅ Vantagens:

Sempre tem bom desempenho: O(n log n).
Não usa memória extra.
❌ Desvantagens:

Não mantém a ordem de valores iguais (instável).


🔷 7. Counting Sort (Ordenação por Contagem)
Como funciona:
Conta quantas vezes cada número aparece e monta a lista final com base nessas contagens.

✅ Vantagens:

Super rápido para listas de números inteiros pequenos.
❌ Desvantagens:

Não funciona com números negativos.
Ineficiente se os números forem muito grandes ou variados.


🔷 8. Radix Sort
Como funciona:
Ordena os números dígito por dígito (começando pelas unidades, depois dezenas, centenas...). Usa uma técnica parecida com o Counting Sort em cada passo.

✅ Vantagens:

Muito rápido para inteiros grandes com número fixo de dígitos.
❌ Desvantagens:

Só funciona com inteiros.
Não funciona bem com números negativos ou decimais.


🔷 9. Bucket Sort
Como funciona:
Divide os dados em "baldes" (grupos), coloca os valores parecidos juntos, ordena cada balde separadamente (normalmente com Insertion Sort), e junta tudo no fim.

✅ Vantagens:

Muito eficiente quando os números estão bem distribuídos.
❌ Desvantagens:

Pode ser difícil ajustar para distribuições irregulares.
Nem sempre é mais rápido que os outros.


Cada algoritmo está disponível em um arquivo individual. Clique nos links abaixo para ver o código-fonte:

| Algoritmo             | Arquivo                    | Complexidade Média | Estável | In-place |
|-----------------------|----------------------------|--------------------|---------|----------|
| Selection Sort        | [selection_sort.py](selection_sort.py) | O(n²)               | ❌       | ✅        |
| Bubble Sort           | [bubble_sort.py](bubble_sort.py)       | O(n²)               | ✅       | ✅        |
| Insertion Sort        | [insertion_sort.py](insertion_sort.py) | O(n²)               | ✅       | ✅        |
| Merge Sort            | [merge_sort.py](merge_sort.py)         | O(n log n)          | ✅       | ❌        |
| Quick Sort            | [quick_sort.py](quick_sort.py)         | O(n log n)          | ❌       | ✅        |
| Heap Sort             | [heap_sort.py](heap_sort.py)           | O(n log n)          | ❌       | ✅        |
| Counting Sort         | [counting_sort.py](counting_sort.py)   | O(n + k)            | ✅       | ❌        |
| Radix Sort            | [radix_sort.py](radix_sort.py)         | O(nk)               | ✅       | ❌        |
| Bucket Sort           | [bucket_sort.py](bucket_sort.py)       | O(n + k)            | ✅       | ❌        |

---

## 📚 Descrição Rápida

- **Estável**: Mantém a ordem de elementos iguais.
- **In-place**: Não usa espaço extra significativo.

---

## 🧪 Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/Algoritmos-Ordenacao.git
   cd Algoritmos-Ordenacao
