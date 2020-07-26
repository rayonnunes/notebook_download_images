# python_download_images
Script para download automático de imagens a partir de uma lista

## Pré Requisitos

[python3](https://www.python.org/downloads/) - A maioria das distros linux já possui tanto o python quanto python3 instalados nativamente

[pip](https://pip.pypa.io/en/stable/installing/) - instalador de pacotes para Python.\
`sudo apt install python3-venv python3-pip`

[pipenv](https://github.com/pypa/pipenv) - Ambiente de densenvolvimento virtual, evita problemas de dependencias não encontradas.\
`pip3 install pipenv`

[Selenium WebDriver](https://www.selenium.dev/documentation/en/getting_started_with_webdriver/browsers/) - Para emular o navegador pelo selenium, tenha instalado o driver correspondente do seu navegador preferido, este projeto utilizará como webdriver padrão o [geckodriver](https://github.com/mozilla/geckodriver/).\
`pip3 install selenium`

[Jupyter Notebook](https://jupyter.org/install) - Ambiente de Desenvolvimento interativo para Testes.<br/>`pip3 install jupyterlab && pip3 install notebook`

## Getting Started
Após a instalação dos pré-requisitos obrigatórios, com o terminal na pasta raiz do projeto.
Para utilizar o ambiente virtual, execute o comando:
`pipenv shell`\
E para instalar as dependencias a partir do arquivo Pipfile.lock, execute:
`pipenv install`

Todo o script está descrito no notebook `notebook.ipynb`, para executá-lo utilize:\
`jupyter notebook notebook.ipynb`
