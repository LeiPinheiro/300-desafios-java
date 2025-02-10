# Resolvendo 300 desafios em java 🐧
> [!WARNING]  
> **Planegei esses desafios e categorias com a IA DeepSeek, ou seja, alguns desafios podem estar muito fora da curva e até errados, caso eu veja que esse é o caso, vou só pular o desafio.**

Este reposítorio é um desafio pessoal onde documento 300 desafios de diferentes dificuldades resolvidos usando a linguagem Java. Resolvi fazer isso enquanto estudo sobre a linguagem para melhorar minha lógica e ao mesmo tempo melhorar meu entendimento em java.

Os desafios são separados em dificuldades (fácil, média e difícil), e dentro dessas dificuldades existem "categorias" de assuntos importantes para aprender.
**Cada dificuldade tem 100 desafios diferentes, 10 desafios são separados por categorias. Com o passar dos desafios mais difíceis eles ficam.**

## 📋 Categorias
- **Nível Fácil**: Arrays & Strings, Loops & Condicionais, OOP Básica, Recursão, Linked Lists, Matemática, Tratamento de Erros, Collections Framework, Manipulação de Arquivos, Threads.
- **Nível Médio**: Árvores & Grafos, Algoritmos de Ordenação, Programação Dinâmica, Design Patterns, Threads & Concorrência, Estruturas de Dados Avançadas, Algoritmos de Grafos, Problemas de Otimização, Sistemas Distribuídos, Machine Learning Básico.
- **Nível Difícil**: Algoritmos Avançados, Programação Dinâmica Avançada, Grafos Avançados, Estruturas de Dados Complexas, Concorrência Avançada, Sistemas Distribuídos, Machine Learning, Compiladores & Interpretadores, Segurança, Projetos Complexos.

## 📌 Como funciona?
- Todos os dias (ou nem sempre), resolvo alguns desafios em Java.
- Cada desafio resolvido é armazenado em uma pasta correspondente ao nome do desafio.
- O código de cada desafio é salvo com um nome descritivo.
- Um arquivo README.md acompanha cada arquivo, explicando os desafios e soluções.

## 📂 Estrutura do repositório
Tem bastante pasta, então deixei só uma parte do repositório todo.
```plaintext
📂300-desafios-java/
├── 📂dificuldade-fácil/
│   ├── 📂arrays&strings/
│     ├── 📂desafio-001/
│       ├── desafio_001.java
│       ├── README.md
├── README.md
```

## 🚀 Objetivos
- ✔️ Melhorar minha lógica de programação
- ✔️ Aprender e reforçar conceitos de Java
- ✔️ Criar uma rotina de estudos consistente

# 🗒️ Lista de desafios

Esta é uma lista de **300 desafios de programação** em Java, organizados por nível de dificuldade (fácil, médio e difícil). Cada desafio vem com uma dica para ajudar no começo.

---

## **Nível Fácil (100 Desafios)**

### **1. Arrays & Strings**
1. **Soma de Dois Números**: Receba dois números e retorne a soma.  
   **Dica**: Use operador `+`.

2. **Maior Elemento em um Array**: Encontre o maior número em um array.  
   **Dica**: Use um loop e uma variável temporária.

3. **Contar Vogais**: Conte o número de vogais em uma string.  
   **Dica**: Use `String.charAt()` e um loop.

4. **Inverter String**: Inverta uma string sem usar bibliotecas externas.  
   **Dica**: Use um loop reverso.

5. **Verificar Palíndromo**: Verifique se uma string é um palíndromo.  
   **Dica**: Compare caracteres do início e fim.

6. **Remover Duplicatas**: Remova elementos duplicados de um array.  
   **Dica**: Use `HashSet`.

7. **Soma de Elementos Pares**: Some apenas os números pares de um array.  
   **Dica**: Use `%` para verificar paridade.

8. **Encontrar Índice de um Elemento**: Retorne o índice de um elemento em um array.  
   **Dica**: Use um loop e `if`.

9. **Concatenar Arrays**: Concatene dois arrays em um.  
   **Dica**: Use `System.arraycopy()`.

10. **Contar Caracteres**: Conte quantas vezes um caractere aparece em uma string.  
    **Dica**: Use `String.charAt()` e um loop.

---

### **2. Loops & Condicionais**
11. **Fibonacci**: Imprima a sequência Fibonacci até N termos.  
    **Dica**: Use um loop e variáveis auxiliares.

12. **Fatorial**: Calcule o fatorial de um número.  
    **Dica**: Use recursão ou loop.

13. **Tabuada**: Imprima a tabuada de um número.  
    **Dica**: Use um loop `for`.

14. **Números Primos**: Verifique se um número é primo.  
    **Dica**: Use um loop até `Math.sqrt(n)`.

15. **IMC**: Calcule o Índice de Massa Corporal.  
    **Dica**: Use `Scanner` para entrada.

16. **Soma de Dígitos**: Some os dígitos de um número.  
    **Dica**: Use `%` e `/`.

17. **Divisores de um Número**: Liste todos os divisores de um número.  
    **Dica**: Use um loop até `n`.

18. **Múltiplos de 3 e 5**: Some todos os múltiplos de 3 e 5 abaixo de N.  
    **Dica**: Use `%` e `||`.

19. **Padrão de Números**: Imprima um padrão de números (ex: pirâmide).  
    **Dica**: Use loops aninhados.

20. **Conversão de Temperatura**: Converta Celsius para Fahrenheit.  
    **Dica**: Use fórmula `(C * 9/5) + 32`.

---

### **3. OOP Básica**
21. **Classe `Pessoa`**: Crie uma classe `Pessoa` com atributos `nome` e `idade`.  
    **Dica**: Use getters e setters.

22. **Herança**: Crie uma classe `Animal` e subclasses `Cachorro` e `Gato`.  
    **Dica**: Use `extends`.

23. **Método Estático**: Crie um método estático para calcular a área de um círculo.  
    **Dica**: Use `Math.PI`.

24. **Encapsulamento**: Crie uma classe `ContaBancaria` com saldo privado.  
    **Dica**: Use `private` e métodos públicos.

25. **Construtor**: Crie uma classe `Carro` com construtor para `marca` e `modelo`.  
    **Dica**: Use `this`.

26. **Sobrecarga de Métodos**: Crie métodos com o mesmo nome mas parâmetros diferentes.  
    **Dica**: Use diferentes assinaturas.

27. **Interface `Forma`**: Crie uma interface com método `calcularArea()`.  
    **Dica**: Implemente em classes como `Círculo` e `Quadrado`.

28. **Polimorfismo**: Use uma superclasse para referenciar objetos de subclasses.  
    **Dica**: Use `Animal animal = new Cachorro()`.

29. **Singleton**: Implemente uma classe Singleton.  
    **Dica**: Use construtor privado e método estático.

30. **Enum**: Crie um enum `DiaDaSemana` com métodos.  
    **Dica**: Use `enum` e `switch`.

---

### **4. Recursão**
31. **Soma Recursiva**: Some os números de 1 a N.  
    **Dica**: Use recursão com caso base `n == 1`.

32. **Fatorial Recursivo**: Calcule o fatorial de um número.  
    **Dica**: Use recursão com caso base `n == 0`.

33. **Fibonacci Recursivo**: Implemente a sequência Fibonacci.  
    **Dica**: Use recursão com casos base `n == 0` e `n == 1`.

34. **Potência Recursiva**: Calcule `a^b` usando recursão.  
    **Dica**: Use `a * potencia(a, b-1)`.

35. **Contagem Regressiva**: Imprima números de N a 1.  
    **Dica**: Use recursão com caso base `n == 0`.

36. **Soma de Dígitos Recursiva**: Some os dígitos de um número.  
    **Dica**: Use `n % 10 + somaDigitos(n / 10)`.

37. **Inverter String Recursivo**: Inverta uma string.  
    **Dica**: Use `charAt()` e recursão.

38. **MDC Recursivo**: Calcule o máximo divisor comum.  
    **Dica**: Use o algoritmo de Euclides.

39. **Torre de Hanoi**: Resolva o problema com recursão.  
    **Dica**: Mova discos entre torres.

40. **Busca Binária Recursiva**: Implemente busca binária.  
    **Dica**: Divida o array ao meio.

---

### **5. Listas Ligadas**
41. **Inserir no Início**: Insira um nó no início de uma lista ligada.  
    **Dica**: Atualize o `head`.

42. **Inserir no Fim**: Insira um nó no fim de uma lista ligada.  
    **Dica**: Percorra até o último nó.

43. **Remover do Início**: Remova o primeiro nó.  
    **Dica**: Atualize o `head`.

44. **Remover do Fim**: Remova o último nó.  
    **Dica**: Percorra até o penúltimo nó.

45. **Buscar Elemento**: Verifique se um valor está na lista.  
    **Dica**: Percorra a lista.

46. **Tamanho da Lista**: Calcule o número de nós.  
    **Dica**: Use um contador.

47. **Inverter Lista**: Inverta a ordem dos nós.  
    **Dica**: Use três ponteiros.

48. **Remover Duplicatas**: Remova nós duplicados.  
    **Dica**: Use `HashSet`.

49. **Unir Listas**: Concatene duas listas ligadas.  
    **Dica**: Anexe a segunda lista ao fim da primeira.

50. **N-ésimo Nó**: Retorne o nó na posição N.  
    **Dica**: Percorra até a posição.

---

### **6. Matemática**
51. **Média de Números**: Calcule a média de um array.  
    **Dica**: Some e divida pelo tamanho.

52. **MDC**: Calcule o máximo divisor comum.  
    **Dica**: Use o algoritmo de Euclides.

53. **MMC**: Calcule o mínimo múltiplo comum.  
    **Dica**: Use `MDC(a, b) * MMC(a, b) = a * b`.

54. **Números Primos até N**: Liste todos os primos até N.  
    **Dica**: Use o crivo de Eratóstenes.

55. **Potência de 2**: Verifique se um número é potência de 2.  
    **Dica**: Use `(n & (n - 1)) == 0`.

56. **Fatorial de Números Grandes**: Calcule fatorial para números grandes.  
    **Dica**: Use `BigInteger`.

57. **Soma de Séries**: Calcule a soma de uma série (ex: 1 + 1/2 + 1/3 + ...).  
    **Dica**: Use um loop.

58. **Conversão de Base**: Converta um número decimal para binário.  
    **Dica**: Use divisões sucessivas.

59. **Números Amigos**: Verifique se dois números são amigos.  
    **Dica**: Compare a soma dos divisores.

60. **Números Perfeitos**: Verifique se um número é perfeito.  
    **Dica**: Compare a soma dos divisores com o número.

---

### **7. Tratamento de Erros**
61. **Divisão por Zero**: Trate exceção de divisão por zero.  
    **Dica**: Use `try-catch`.

62. **Conversão de String para Inteiro**: Trate exceção de conversão inválida.  
    **Dica**: Use `Integer.parseInt()`.

63. **Leitura de Arquivo**: Trate exceção de arquivo não encontrado.  
    **Dica**: Use `FileReader` e `try-catch`.

64. **Validação de Entrada**: Valide se a entrada é um número.  
    **Dica**: Use `Scanner.hasNextInt()`.

65. **Exceção Personalizada**: Crie uma exceção personalizada.  
    **Dica**: Estenda `Exception`.

66. **Finally**: Use `finally` para liberar recursos.  
    **Dica**: Feche `Scanner` ou `FileReader`.

67. **Multi-catch**: Capture múltiplas exceções em um bloco.  
    **Dica**: Use `catch (Exception1 | Exception2 e)`.

68. **Lançamento de Exceção**: Lance uma exceção manualmente.  
    **Dica**: Use `throw new Exception()`.

69. **Exceção em Métodos**: Declare exceções em métodos.  
    **Dica**: Use `throws`.

70. **Recuperação de Erros**: Recupere-se de uma exceção e continue.  
    **Dica**: Use `try-catch` em um loop.

---

### **8. Collections Framework**
71. **ArrayList**: Adicione e remova elementos de um `ArrayList`.  
    **Dica**: Use `add()` e `remove()`.

72. **HashSet**: Verifique se um elemento está em um `HashSet`.  
    **Dica**: Use `contains()`.

73. **HashMap**: Conte a frequência de palavras em um texto.  
    **Dica**: Use `put()` e `get()`.

74. **Ordenação de Lista**: Ordene uma lista de strings.  
    **Dica**: Use `Collections.sort()`.

75. **Iteração com Iterator**: Itere sobre uma lista com `Iterator`.  
    **Dica**: Use `hasNext()` e `next()`.

76. **LinkedList**: Implemente uma fila com `LinkedList`.  
    **Dica**: Use `addLast()` e `removeFirst()`.

77. **TreeSet**: Armazene elementos ordenados em um `TreeSet`.  
    **Dica**: Use `add()`.

78. **PriorityQueue**: Implemente uma fila de prioridade.  
    **Dica**: Use `Comparator`.

79. **Stream API**: Filtre números pares de uma lista.  
    **Dica**: Use `filter()` e `collect()`.

80. **ConcurrentHashMap**: Use `ConcurrentHashMap` para thread-safety.  
    **Dica**: Use `putIfAbsent()`.

---

### **9. Manipulação de Arquivos**
81. **Leitura de Arquivo**: Leia um arquivo linha por linha.  
    **Dica**: Use `BufferedReader`.

82. **Escrita em Arquivo**: Escreva texto em um arquivo.  
    **Dica**: Use `FileWriter`.

83. **Copiar Arquivo**: Copie o conteúdo de um arquivo para outro.  
    **Dica**: Use `FileInputStream` e `FileOutputStream`.

84. **Contar Linhas**: Conte o número de linhas em um arquivo.  
    **Dica**: Use `BufferedReader`.

85. **Buscar Palavra**: Verifique se uma palavra está em um arquivo.  
    **Dica**: Use `contains()`.

86. **Serialização**: Serialize um objeto para um arquivo.  
    **Dica**: Use `ObjectOutputStream`.

87. **Desserialização**: Desserialize um objeto de um arquivo.  
    **Dica**: Use `ObjectInputStream`.

88. **Compactar Arquivo**: Compacte um arquivo usando ZIP.  
    **Dica**: Use `ZipOutputStream`.

89. **Descompactar Arquivo**: Descompacte um arquivo ZIP.  
    **Dica**: Use `ZipInputStream`.

90. **Manipulação de Diretórios**: Liste arquivos em um diretório.  
    **Dica**: Use `File.listFiles()`.

---

### **10. Threads**
91. **Thread Simples**: Crie uma thread que imprime números.  
    **Dica**: Estenda `Thread` ou implemente `Runnable`.

92. **Sincronização**: Sincronize threads para evitar race conditions.  
    **Dica**: Use `synchronized`.

93. **Wait e Notify**: Implemente produtor-consumidor com `wait()` e `notify()`.  
    **Dica**: Use um buffer compartilhado.

94. **Thread Pool**: Use `ExecutorService` para gerenciar threads.  
    **Dica**: Use `Executors.newFixedThreadPool()`.

95. **Callable e Future**: Retorne um valor de uma thread.  
    **Dica**: Use `Callable` e `Future`.

96. **Deadlock**: Simule um deadlock com duas threads.  
    **Dica**: Use bloqueios mútuos.

97. **Thread Local**: Use `ThreadLocal` para variáveis locais.  
    **Dica**: Armazene dados específicos por thread.

98. **TimerTask**: Agende uma tarefa com `Timer`.  
    **Dica**: Use `Timer.schedule()`.

99. **Atomic Variables**: Use `AtomicInteger` para operações atômicas.  
    **Dica**: Evite sincronização manual.

100. **ForkJoinPool**: Divida uma tarefa em subtarefas.  
     **Dica**: Use `RecursiveTask`.

---

## **Nível Médio (100 Desafios)**

### **1. Árvores & Grafos**
1. **Altura de uma Árvore Binária**: Calcule a altura de uma árvore.  
   **Dica**: Use recursão e `Math.max()`.

2. **Verificar BST**: Verifique se uma árvore é uma BST válida.  
   **Dica**: Use limites mínimos e máximos.

3. **Percurso em Ordem**: Implemente o percurso em ordem (in-order).  
   **Dica**: Use recursão.

4. **Percurso em Nível (BFS)**: Implemente o percurso em nível.  
   **Dica**: Use uma fila (`Queue`).

5. **Caminho Mais Curto em Grafo**: Implemente BFS para encontrar o caminho mais curto.  
   **Dica**: Use `Queue` e marque nós visitados.

6. **Detectar Ciclos em Grafo**: Verifique se um grafo tem ciclos.  
   **Dica**: Use DFS e marque nós visitados.

7. **Topological Sort**: Ordene nós de um grafo direcionado acíclico (DAG).  
   **Dica**: Use DFS e uma pilha.

8. **Árvore de Menor Custo (MST)**: Implemente o algoritmo de Kruskal.  
   **Dica**: Use `PriorityQueue` e Union-Find.

9. **Caminho Mais Longo em DAG**: Encontre o caminho mais longo em um DAG.  
   **Dica**: Use topological sort e relaxamento.

10. **Componentes Conectados**: Conte o número de componentes conectados em um grafo.  
    **Dica**: Use DFS ou BFS.

---

### **2. Algoritmos de Ordenação**
11. **Merge Sort**: Implemente o Merge Sort.  
    **Dica**: Divida o array e combine com arrays temporários.

12. **Quick Sort**: Implemente o Quick Sort.  
    **Dica**: Use partição e recursão.

13. **Heap Sort**: Implemente o Heap Sort.  
    **Dica**: Use uma heap máxima.

14. **Counting Sort**: Implemente o Counting Sort.  
    **Dica**: Use um array de contadores.

15. **Radix Sort**: Implemente o Radix Sort.  
    **Dica**: Use buckets para cada dígito.

16. **Bucket Sort**: Implemente o Bucket Sort.  
    **Dica**: Divida o array em intervalos.

17. **Ordenação de Objetos**: Ordene uma lista de objetos por um atributo.  
    **Dica**: Use `Comparator`.

18. **Ordenação Estável**: Implemente uma ordenação estável.  
    **Dica**: Use Merge Sort.

19. **Ordenação em Listas Ligadas**: Ordene uma lista ligada.  
    **Dica**: Use Merge Sort.

20. **Ordenação Externa**: Ordene um arquivo grande que não cabe na memória.  
    **Dica**: Use divisão e intercalação.

---

### **3. Programação Dinâmica**
21. **Fibonacci com Memoização**: Calcule Fibonacci usando memoização.  
    **Dica**: Use um array para armazenar resultados.

22. **Problema da Mochila**: Resolva o problema da mochila.  
    **Dica**: Use uma matriz de estados.

23. **Maior Subsequência Comum (LCS)**: Encontre a maior subsequência comum entre duas strings.  
    **Dica**: Use uma matriz de estados.

24. **Maior Subarray Contíguo**: Encontre o subarray com a maior soma.  
    **Dica**: Use o algoritmo de Kadane.

25. **Troco Mínimo**: Encontre o número mínimo de moedas para um valor.  
    **Dica**: Use programação dinâmica.

26. **Caminhos em Grade**: Conte o número de caminhos em uma grade.  
    **Dica**: Use uma matriz de estados.

27. **Quebra de Palavras**: Verifique se uma string pode ser quebrada em palavras válidas.  
    **Dica**: Use memoização.

28. **Maior Subsequência Crescente**: Encontre a maior subsequência crescente.  
    **Dica**: Use uma matriz de estados.

29. **Problema do Corte de Hastes**: Maximize o valor de cortes em uma haste.  
    **Dica**: Use programação dinâmica.

30. **Edit Distance**: Calcule a distância de edição entre duas strings.  
    **Dica**: Use uma matriz de estados.

---

### **4. Design Patterns**
31. **Singleton**: Implemente uma classe Singleton thread-safe.  
    **Dica**: Use construtor privado e método estático.

32. **Factory Method**: Implemente o padrão Factory Method.  
    **Dica**: Crie uma interface e classes concretas.

33. **Observer**: Implemente o padrão Observer.  
    **Dica**: Use `Subject` e `Observer`.

34. **Decorator**: Implemente o padrão Decorator.  
    **Dica**: Adicione funcionalidades dinamicamente.

35. **Strategy**: Implemente o padrão Strategy.  
    **Dica**: Use interfaces para algoritmos intercambiáveis.

36. **Adapter**: Implemente o padrão Adapter.  
    **Dica**: Adapte uma interface para outra.

37. **Proxy**: Implemente o padrão Proxy.  
    **Dica**: Controle o acesso a um objeto.

38. **Command**: Implemente o padrão Command.  
    **Dica**: Encapsule comandos em objetos.

39. **Template Method**: Implemente o padrão Template Method.  
    **Dica**: Defina esqueletos de algoritmos.

40. **State**: Implemente o padrão State.  
    **Dica**: Mude o comportamento com base no estado.

---

### **5. Threads & Concorrência**
41. **Produtor-Consumidor**: Implemente o problema do produtor-consumidor.  
    **Dica**: Use `wait()` e `notify()`.

42. **Leitores-Escritores**: Implemente o problema dos leitores-escritores.  
    **Dica**: Use `ReentrantReadWriteLock`.

43. **Thread Pool**: Crie um thread pool personalizado.  
    **Dica**: Use `BlockingQueue`.

44. **Callable e Future**: Retorne um valor de uma thread.  
    **Dica**: Use `Callable` e `Future`.

45. **Sincronização com Semáforos**: Use semáforos para controlar acesso.  
    **Dica**: Use `Semaphore`.

46. **Barreira de Threads**: Sincronize threads em uma barreira.  
    **Dica**: Use `CyclicBarrier`.

47. **Exchanger**: Troque dados entre threads.  
    **Dica**: Use `Exchanger`.

48. **StampedLock**: Use `StampedLock` para otimizar leituras.  
    **Dica**: Use `tryOptimisticRead()`.

49. **ForkJoinPool**: Divida uma tarefa em subtarefas.  
    **Dica**: Use `RecursiveTask`.

50. **Atomic Variables**: Use variáveis atômicas para operações seguras.  
    **Dica**: Use `AtomicInteger`.

---

### **6. Estruturas de Dados Avançadas**
51. **Árvore AVL**: Implemente inserção e rotações.  
    **Dica**: Mantenha o balanceamento.

52. **Árvore Rubro-Negra**: Implemente inserção e balanceamento.  
    **Dica**: Use regras de coloração.

53. **Trie**: Implemente uma Trie para armazenar palavras.  
    **Dica**: Use nós com filhos.

54. **Segment Tree**: Implemente uma árvore de segmentos.  
    **Dica**: Use divisão e conquista.

55. **Fenwick Tree**: Implemente uma árvore de Fenwick.  
    **Dica**: Use operações de bits.

56. **Union-Find**: Implemente Union-Find com compressão de caminho.  
    **Dica**: Use arrays para pais e ranks.

57. **Deque**: Implemente uma fila de duas pontas.  
    **Dica**: Use `ArrayDeque`.

58. **Bloom Filter**: Implemente um filtro de Bloom.  
    **Dica**: Use múltiplas funções de hash.

59. **Skip List**: Implemente uma skip list.  
    **Dica**: Use níveis de ponteiros.

60. **Graph Adjacency List**: Implemente um grafo usando lista de adjacência.  
    **Dica**: Use `HashMap` e `LinkedList`.

---

### **7. Algoritmos de Grafos**
61. **Dijkstra**: Implemente o algoritmo de Dijkstra.  
    **Dica**: Use `PriorityQueue`.

62. **Bellman-Ford**: Implemente o algoritmo de Bellman-Ford.  
    **Dica**: Relaxe arestas repetidamente.

63. **Floyd-Warshall**: Implemente o algoritmo de Floyd-Warshall.  
    **Dica**: Use uma matriz de distâncias.

64. **Kruskal**: Implemente o algoritmo de Kruskal.  
    **Dica**: Use Union-Find.

65. **Prim**: Implemente o algoritmo de Prim.  
    **Dica**: Use `PriorityQueue`.

66. **Tarjan**: Implemente o algoritmo de Tarjan para componentes fortemente conectados.  
    **Dica**: Use DFS e pilha.

67. **Kosaraju**: Implemente o algoritmo de Kosaraju.  
    **Dica**: Use DFS duas vezes.

68. **Eulerian Path**: Verifique se um grafo tem um caminho euleriano.  
    **Dica**: Conte graus dos nós.

69. **Hamiltonian Path**: Verifique se um grafo tem um caminho hamiltoniano.  
    **Dica**: Use backtracking.

70. **Bipartite Graph**: Verifique se um grafo é bipartido.  
    **Dica**: Use coloração com BFS.

---

### **8. Problemas de Otimização**
71. **Knapsack 0/1**: Resolva o problema da mochila 0/1.  
    **Dica**: Use programação dinâmica.

72. **Problema do Caixeiro Viajante (TSP)**: Resolva o TSP com backtracking.  
    **Dica**: Use recursão e marque nós visitados.

73. **Alocação de Recursos**: Otimize a alocação de recursos.  
    **Dica**: Use programação linear.

74. **Agendamento de Tarefas**: Agende tarefas para minimizar o tempo total.  
    **Dica**: Use algoritmos gananciosos.

75. **Problema do Corte de Hastes**: Maximize o valor de cortes.  
    **Dica**: Use programação dinâmica.

76. **Problema do Troco**: Encontre o número mínimo de moedas.  
    **Dica**: Use programação dinâmica.

77. **Problema da Mochila Fracionária**: Resolva o problema da mochila fracionária.  
    **Dica**: Use algoritmos gananciosos.

78. **Problema do Escalonamento de Intervalos**: Escalone intervalos sem sobreposição.  
    **Dica**: Use algoritmos gananciosos.

79. **Problema 

## 🏆 Progresso
1. ### Nível Dificíl:
   - 📅 Desafio 01 - ✅

