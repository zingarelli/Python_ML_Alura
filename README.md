# Formação ML com Python - Classificação

[Link da formação na Alura](https://cursos.alura.com.br/formacao-machine-learning-python-classificacao)

## Criando um ambiente virtual

Seguirei os estudos pelo VS Code. É possível criar um ambiente virtual no Python, de modo a poder instalar os packages/bibliotecas Python **localmente**. Com isso, posso ter diferentes ambientes virtuais, cada um com packages e versões específicas, sem correr o risco de conflitos entre os projetos.

1. Criação do ambiente virtual. Você pode escolher o nome que desejar em `nome_do_ambiente_virtual`

```
python -m venv nome_do_ambiente_virtual
```

2. É criada uma pasta com o nome que você escolheu. Essa pasta é grande, então **não** recomendo versioná-la.

3. Ative o ambiente virtual **antes** de começar a instalar as packages desejadas

```
.\nome_do_ambiente_virtual\Scripts\activate
```

4. Instale as packages que desejar. Exemplo instalando o Pandas na versão 1.5.3

```
pip install pandas==1.5.3
```

### Dicas

- Comando para desinstalar um package: `pip uninstall nome_do_pacote`.

- Comando para listar todos os packages instalados: `pip list`

- Para desativar um ambiente virtual: `deactivate`.

- O VS Code possui uma extensão para usar notebooks Jupyter. Com a extensão instalada, é possível usar a tela do VS para selecionar um ambiente virtual e utilizá-lo em seus notebooks, sem a necessidade de rodar os comandos via terminal.

    - Ao rodar um notebook utilizando um ambiente virtual, pode ser que o VS Code solicite a instalação de pacotes adicionais).