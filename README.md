# Formação ML com Python - Classificação

[Link da formação na Alura](https://cursos.alura.com.br/formacao-machine-learning-python-classificacao)

## Como se guiar pela formação

Os cursos estão separados por pastas, contendo os arquivos necessários para acompanhar as anotações e rodar os códigos em notebooks Jupyter. Em cada pasta, procure um arquivo com o nome de `notebook.ipynb` para ler as anotações de estudo e rodar os códigos. Eventualmente também haverá arquivos `desafio.ipynb` contendo a resolução para exercícios propostos em um curso.

- Os Jupyter Notebooks são uma forma de mesclar células (blocos) de texto (em formato Markdown) com células de códigos Python, sendo que os códigos podem ser executados no próprio notebook, tendo sua saída exibida logo abaixo da célula correspondente. Eles podem ser reconhecidos pela sua extensão `.ipynb`.

## Trilha da formação

Os cursos estão na seguinte ordem (clique no link para ir até a pasta do curso):

1. [Aprendendo a classificar dados com Machine Learning](/introducao-classificacao/)

2. [Validação de modelos e métricas de avaliação](/validacao-e-metricas/)

3. [Resolvendo problemas multiclasse](/classificacao-multiclasse/)

4. [Otimizando modelos de machine learning](/otimizacao-modelos/)

5. [Selecionando features](/selecao-features/)

6. [Combinando classificadores para a melhoria de performance](/bagging-boosting/)

7. [Melhorando o desempenho com XGBoost](/XGBoost/)

8. [Construindo modelos semi-supervisionados](/aprendizado-semisupervisionado/)

## Criando um ambiente virtual

Os instrutores utilizaram o [Google Colab](https://colab.research.google.com) como IDE, mas eu utilizei o VS Code. Somente em um curso tive resultados diferentes (métricas e hiperparâmetros com valores diferentes) por conta dessa escolha, e acredito que se deve ao Colab ter mais poder de computação e cálculo mais preciso de ponto flutuante.

No VS Code é possível criar um ambiente virtual no Python, de modo a poder instalar os packages/bibliotecas Python **localmente**. Com isso, posso ter diferentes ambientes virtuais, cada um com packages e versões específicas, sem correr o risco de conflitos de bibliotecas e versões entre os projetos.

1. Criação do ambiente virtual. Você pode escolher o nome que desejar em `nome_do_ambiente_virtual`

```
python -m venv nome_do_ambiente_virtual
```

2. É criada uma pasta com o nome que você escolheu. Essa pasta é grande, então **não** recomendo versioná-la.

3. Ative o ambiente virtual **antes** de começar a instalar as packages desejadas.

```
.\nome_do_ambiente_virtual\Scripts\activate
```

Observação: o VS Code possui uma [extensão para usar notebooks Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter). Com ela instalada, é possível selecionar um ambiente virtual e utilizá-lo para executar o notebook, sem a necessidade de ativar o ambiente virtual manualmente via terminal.

- Ao rodar um notebook utilizando um ambiente virtual, pode ser que o VS Code solicite a instalação de pacotes adicionais.

4. Instale as packages e versões que desejar. Exemplo instalando o Pandas na versão 1.5.3

```
pip install pandas==1.5.3
```

### Dicas

- Comando para desinstalar um package: `pip uninstall nome_do_pacote`;

- Comando para listar todos os packages instalados: `pip list`;

- Para desativar um ambiente virtual: `deactivate`.