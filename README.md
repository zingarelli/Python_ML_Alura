# Formação ML com Python - Classificação

[Link da formação na Alura](https://cursos.alura.com.br/formacao-machine-learning-python-classificacao)

## Trilha da formação

Os cursos estão na seguinte ordem:

1. [Aprendendo a classificar dados com Machine Learning](/introducao-classificacao/)

2. [Validação de modelos e métricas de avaliação](/validacao-e-metricas/)

3. [Resolvendo problemas multiclasse](/classificacao-multiclasse/)

4. [Otimizando modelos de machine learning](/otimizacao-modelos/)

5. [Selecionando features](/selecao-features/)

6. [Combinando classificadores para a melhoria de performance](/bagging-boosting/)

7. [Melhorando o desempenho com XGBoost](/XGBoost/)

8. Construindo modelos semi-supervisionados

## Criando um ambiente virtual

Os cursos foram ensinados utilizando o [Google Colab](https://colab.research.google.com) como IDE, mas eu utilizei o VS Code.

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

Observação: o VS Code possui uma [extensão para usar notebooks Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter). Com ela instalada, é possível selecionar um ambiente virtual e utilizá-lo para executar o notebook, sem a necessidade de ativar o ambiente virtual os comandos via terminal.
- Ao rodar um notebook utilizando um ambiente virtual, pode ser que o VS Code solicite a instalação de pacotes adicionais.

4. Instale as packages que desejar. Exemplo instalando o Pandas na versão 1.5.3

```
pip install pandas==1.5.3
```

### Dicas

- Comando para desinstalar um package: `pip uninstall nome_do_pacote`.

- Comando para listar todos os packages instalados: `pip list`

- Para desativar um ambiente virtual: `deactivate`.