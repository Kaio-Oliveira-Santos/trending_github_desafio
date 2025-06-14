# trending_github_desafio
Este repositório contém um script Python para extrair os 10 repositórios mais populares do GitHub Trending e salvar os dados em um arquivo CSV para análise.


Trending GitHub Repositories Scraper:

Para que serve?

* Obtém os 10 primeiros repositórios trending do GitHub.
* 
Extrai informações como:
* Nome do repositório (usuário/repo)
* Linguagem principal
* Número de estrelas ⭐
* Número de forks 🍴
* Salva os dados extraídos no arquivo github.csv.

Como Funciona?
O script realiza as seguintes etapas:

1. Faz uma requisição HTTP para obter a página do GitHub Trending.

2. Usa BeautifulSoup para extrair os dados dos repositórios.

3. Formata os dados e os organiza corretamente.

4. Salva tudo em um arquivo CSV para análise posterior.

Quais as tecnologias utilizadas?
Python 🐍!!

Mais especificamente:
BeautifulSoup4 (para parsing do HTML)

Requests (para requisições HTTP)

CSV (para salvar os dados)
