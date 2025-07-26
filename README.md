# Otimização de Enturmação de Alunos com Algoritmo Genético

Este projeto tem como objetivo aplicar técnicas de **Inteligência Artificial**, especificamente **Algoritmo Genético (GA)**, para resolver o problema de **enturmação de alunos**, maximizando afinidades entre os grupos gerados com base em dados fornecidos.

## 🎯 Objetivo

Criar turmas otimizadas de alunos com base em informações como amizades e desempenho acadêmico, buscando minimizar conflitos e maximizar o rendimento coletivo.

## 📊 Tecnologias e Bibliotecas Utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- DEAP (Distributed Evolutionary Algorithms in Python)

## 🚀 Etapas do Projeto

1. **Leitura e preparação dos dados**
   - Simulação de dados de afinidade entre alunos
   - Criação de matriz de amizade
   - Definição de parâmetros para enturmação

2. **Implementação do Algoritmo Genético**
   - Codificação da população inicial
   - Função de fitness baseada na afinidade entre os membros das turmas
   - Operadores de cruzamento, mutação e seleção

3. **Execução e análise dos resultados**
   - Visualização da evolução das soluções
   - Comparação entre indivíduos (soluções) com melhor desempenho
   - Análise das turmas geradas

4. **Visualização**
   - Gráficos de performance da evolução
   - Histogramas das afinidades internas nas turmas

## ✅ Resultados

- Formação de turmas otimizadas com base em critérios definidos (como amizade ou desempenho)
- Solução baseada em evolução populacional que busca o melhor agrupamento possível
- Redução de afinidades negativas e maximização das positivas entre alunos da mesma turma

## 🧠 Aprendizados

- Aplicação prática de algoritmos genéticos para resolver problemas de agrupamento
- Importância da modelagem correta da função de fitness
- Equilíbrio entre diversidade genética e pressão seletiva no GA
