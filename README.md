# Bookspider

Este projeto é um web scraper desenvolvido com Scrapy, focado em extrair dados de livros do site [books.toscrape.com](http://books.toscrape.com). Ele foi criado com base no conteúdo do curso "Scrapy Course - Python Web Scraping for Beginners" oferecido pelo [freeCodeCamp.org](https://www.freecodecamp.org/).

### Tecnologias utilizadas
<div align="center" style="display: inline_block"><br>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original-wordmark.svg" width="50" height="50" alt="Python"/>
</div>

## Executando o projeto

Como executar o projeto localmente.

### Pré-requisitos

* Python 3.8+
* Um ambiente virtual (venv)
* As dependências listadas em `requirements.txt`

```
asttokens==3.0.0
attrs==25.3.0
Automat==25.4.16
certifi==2025.6.15
cffi==1.17.1
charset-normalizer==3.4.2
colorama==0.4.6
constantly==23.10.4
cryptography==45.0.4
cssselect==1.3.0
decorator==5.2.1
defusedxml==0.7.1
executing==2.2.0
filelock==3.18.0
hyperlink==21.0.0
idna==3.10
incremental==24.7.2
ipython==9.3.0
ipython_pygments_lexers==1.1.1
itemadapter==0.11.0
itemloaders==1.3.2
jedi==0.19.2
jmespath==1.0.1
lxml==5.4.0
matplotlib-inline==0.1.7
mysql==0.0.3
mysql-connector-python==9.3.0
mysqlclient==2.2.7
packaging==25.0
parsel==1.10.0
parso==0.8.4
prompt_toolkit==3.0.51
Protego==0.5.0
pure_eval==0.2.3
pyasn1==0.6.1
pyasn1_modules==0.4.2
pycparser==2.22
PyDispatcher==2.0.7
Pygments==2.19.2
pyOpenSSL==25.1.0
queuelib==1.8.0
requests==2.32.4
requests-file==2.1.0
Scrapy==2.13.2
service-identity==24.2.0
setuptools==80.9.0
stack-data==0.6.3
tldextract==5.3.0
traitlets==5.14.3
Twisted==25.5.0
typing_extensions==4.14.0
urllib3==2.5.0
w3lib==2.3.1
wcwidth==0.2.13
zope.interface==7.2
```

### Executando

1.  Clone o repositório
    ```sh
    git clone [https://github.com/seu-usuario/bookspider](https://github.com/seu-usuario/bookspider) # Substitua pelo link do seu repositório
    ```
2.  Crie e entre em um ambiente virtual (venv)
    ```sh
    # Para Windows
    python -m venv venv
    venv\scripts\activate

    # Para macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```
3.  Instale as dependências
    ```sh
    pip install -r requirements.txt
    ```
4.  Navegue até o diretório do Scrapy e execute o spider
    ```sh
    cd bookscraper
    scrapy crawl bookspider
    ```
### OBS:
- Por padrão, o spider salvará os dados extraídos em um arquivo `books.csv`.
- Você pode visualizar a lista de spiders disponíveis no projeto com o comando:
  ```sh
  scrapy list
  ```
