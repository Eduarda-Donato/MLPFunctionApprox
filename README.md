# Aproximação de Funções com Perceptron Multicamadas (MLP)

Projeto que utiliza uma **rede neural perceptron de múltiplas camadas (MLP)** para aproximar funções matemáticas contínuas. O objetivo é treinar a rede para aprender a relação entre entradas \(x\) e saídas \(f(x)\) e avaliar a precisão da aproximação.

## Funções a serem aproximadas

> Função trigonométrica:  
> f(x) = sin(2x) + cos(3x), 0 ≤ x ≤ 5

> Função polinomial:  
> f(x) = 10x^5 + 5x^4 + 2x^3 - 0.5x^2 + 3x + 2, 0 ≤ x ≤ 5




## Descrição do notebook

O notebook realiza as seguintes etapas:

1. **Geração de dados**: cria conjuntos de treinamento e teste para cada função.  
2. **Implementação da MLP**: configura e treina a rede perceptron de múltiplas camadas.  
3. **Treinamento e validação**: ajusta os pesos da rede e calcula o erro ao longo das épocas.  
4. **Visualização**:  
   - Gráficos comparando a **função real x função aproximada**.  
   - Curvas de **erro de treinamento e validação**.  

## Como executar

1. Clone o repositório:  
```bash
git clone https://github.com/seu_usuario/MLPFunctionApprox.git
cd MLPFunctionApprox
```
2. Instale as dependências:
```bash
pip install -r requirements.txt
```
3. Abra o Jupyter Notebook:
```bash
jupyter notebook MLP.ipynb
```
4. Execute as células na ordem para reproduzir os resultados.

## Estrutura dos dados

| x (entrada) | f(x) (saída) |
| ----------- | ------------ |
| 0.23        | 0.87         |
| 1.15        | -0.33        |
| ...         | ...          |

## Métricas de avaliação

Erro quadrático médio (MSE) – mede a diferença entre a saída real e a saída prevista.

## Referências
[Scikit-learn MLPRegressor Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPRegressor.html)
