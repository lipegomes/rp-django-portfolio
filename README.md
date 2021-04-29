# rp-django-portfolio

## Requerimentos:
- Ter a versão 3.xx do python instalada no notebook ou pc.
- Ter o pipenv instalado.
```console
pip install pipenv
```
- Criar o ambiente virtual na pasta do projeto e instalar os requirements:
  
  Criar o .venv, instalar as dependências e ativar o shell do ambiente virtual:
    ```console
    pipenv sync
    pipenv shell
    ```
    Instalar somente as dependências de desenvolvimento:
    ```console
    pipenv sync -d
    ```
## Verificar qualidade de código:
```console
flake8
```

## Rodar a aplicação:
```console
python manage.py runserver
```

## Ferramentas utilizadas:

Ambiente virtual:
1. [Pipenv](https://pipenv.pypa.io/en/latest/)

Frameworks:
1. [Django](https://www.djangoproject.com/)
2. [Bootstrap](https://getbootstrap.com/)

Deploy:
1. [Git](https://git-scm.com/)

Testes e qualidade do código:
1. [PyTest](https://docs.pytest.org/en/stable/)
2. [Flake8](https://flake8.pycqa.org/en/latest/)

## Licença

Este projeto é licenciado sobre a licença MIT - veja [LICENSE](https://github.com/lipegomes/rp-django-portfolio/blob/main/LICENSE) para mais informações.
