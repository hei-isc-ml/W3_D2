# Week 3 - Halfday 3-4

## Missions & Activities:

### Activity 1 – ~30 minutes
- **Peer Review and Validation of SVM (Halfdays 1-2)**: Work in pairs to review and compare your code and results. Exchange the outcome of the previous activity and discuss your approach. Write together 1-2 slides with a list of the key-differences concerning:
    - The result you had
    - The method you used to get to that results
- **Consolidation by the Professor**: After peer review, the professor will provide further clarification and consolidation of the concepts.

### Activity 2
- **Problem**: Use a Genetic Algorithm (GA) to find a quasi-optimal solution for a simple problem (suggestions are below).
- **Tools**: Pure python (suggested) or [DEAP](https://deap.readthedocs.io/en/master/) library or other libraries(e.g., [PyGAD](https://pygad.readthedocs.io/en/latest/))
- **New/Consolidation of ML Glossary**:
  - **Steps**: Initialization, selection, crossover, mutation, evaluation.
  - **Terminology**: Gene, individual (or chromosome), population, parents, children, elite, fitness scores.

## Expected Outcomes:
- **Halfday 3**:
    - Create 5-7 slides presenting Genetic Algorithms (GA). The content of your slides should enable you to answer the questions in the "Understanding GA" section below.
    - The content of your slides should enable you to answer the questions in the [Understanding GA](#understanding-ga-provide-these-answers-in-the-slides) section below.
- **Halfday 4**:
  - A Jupyter notebook for the optimization of a simple problem. Possible problems are proposed below.
  - In your notebook, systematically use markdown cells to:
    - Explain the goal of your code.
    - Comment on the results.
    - Provide **direct** answer the questions in the [Implementing GA](#implementing-ga-provide-these-answers-in-the-jupyter-notebook) section below.

## Tasks – Optimization

1. **Understanding GA**:
  - Explain the following concepts: initialization, selection, crossover, mutation, evaluation.
  - Discuss the terminology: gene, individual (or chromosome), population, parents, children, elite, fitness scores.

2. **Implementation of GA**:
  - Solve a mastermind game using GA:
    - Check the files: 
      - sentence_mastermind.py (a simple class providing the game logic: selecting hidden sentence, checking the guess, etc.)
      - example_mastermind.py (an example that shows how to call the methods in sentence_mastermind.py)
  - NOTE: you can use a GA library or implement GA yourself from scratch. The first is faster, the second will require some extra work but it will provide a better understanding of the implementation details of selection, crossover, mutation, etc. In any case, you can start from online examples. If you use the Deap library, check this [example](https://deap.readthedocs.io/en/master/examples/ga_onemax.html). If you want to code all, check this [example](https://machinelearningmastery.com/simple-genetic-algorithm-from-scratch-in-python/).

## Questions:
### Understanding GA (provide these answers in the slides)
- Explain the main GA steps: Initialization, selection, crossover, mutation, evaluation (1 slide per step)
    - Present at least two different *selection* methods
- Why do we refer to a "quasi-optimal" solution in the goals?
- What is "elitism" in GA? Discuss the advantages and disadvantages of using elitism.
    - What are the potential pitfalls or limitations of the use of elitism?

### Implementing GA (provide these answers in the jupyter notebook)
- Explain the main GA steps also in your code: Initialization, selection, crossover, mutation, evaluation (1 slide per step). Is there any difference compared to what you presented in the slides?
