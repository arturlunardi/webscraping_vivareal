# Web Scraping VivaReal

Nesse repositório iremos extrair informações do site [VivaReal](https://www.vivareal.com.br/)

Esse projeto é de caráter totalmente educacional.

**Este scraper funciona em 19/11/2020**

# Bibliotecas

- [Re](https://docs.python.org/3/library/re.html)
- [Time](https://docs.python.org/3/library/time.html)
- [os](https://docs.python.org/3/library/os.html)
- [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Selenium](https://selenium-python.readthedocs.io/)
- [ChromeDriver](https://chromedriver.chromium.org/downloads)

# Sobre o projeto:

Inspirado no [VivaRealWebScraping](https://github.com/luiseduardobr1/VivaRealWebScraping):

Neste exemplo específico foram selecionados imóveis para locação na cidade de São Paulo/SP.

**O Web Scraper irá coletar informações sobre os imóveis no site VivaReal, as informações coletadas são:**

1. Link do site
2. Endereço
3. Bairro
4. Anunciante
5. Area
6. Tipologia
7. Quartos
8. Banheiros
9. Vagas
10. Preço

# Como utilizar:

- Instale todas as bibliotecas necessárias.
- Baixe o [ChromeDriver](https://chromedriver.chromium.org/downloads) mais atualizado de acordo com o seu sistema e coloque-o no mesmo diretório do script.
- Escolha o link inicial para inicializar o scraping, esse link deve ser retirado do site do VivaReal de acordo com os filtros desejados e alterado no script.
- Ao executar, o arquivo irá solicitar quantas páginas você deseja coletar, essa contagem será realizada a partir do link de página do filtro inicial.

# Resultado:

Será criado um arquivo CSV chamado VivaRealData.csv no mesmo diretório do arquivo contendo todas as informações.

![vivarealdata](https://user-images.githubusercontent.com/72626638/99709393-e1a68f80-2a7d-11eb-96c9-1efd168a647b.png)
