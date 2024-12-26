# Desafio Técnico Aleon

O contaúdo desse repositório é minha solução proposta ao desafio técnico do programa de estágio da empresa Aleon AI. 

## Decisões tomadas durante o projeto

A API escolhida para a extração dos dados foi [Marvel](https://developer.marvel.com), devido à grande possíbilidades de análises possíveis, já que é uma grande base de dados, e à demonstração do uso e administração de chaves privadas.

A biblioteca usada para a visualização dos dados será [Vega Altair](https://altair-viz.github.io), devido à sua grande possíbilidade de customização de gráficos e visualização iterativa.


## Execução

Para executar o projeto, crie um ambiente virtual Python, ative-o e instale as dependências. Utilize esses comandos no sistema Windows:

```
python -m venv venv
.\venv\Scripts\activate.bat
pip install -r requirements.txt
```

E esses nos sistemas Linux:

```
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Feito isso, use a sua interface de escolha para executar o Jupyter Notebook.