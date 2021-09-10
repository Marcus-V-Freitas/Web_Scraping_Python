## :clipboard: Requerimentos
Ter instalado o Python 3 e as bibliotecas Requirements, BeautifulSoup e Pandas e a ferramenta Selenium.
### :wrench: Instalando no Windows
1. **Python 3:** baixe o [instalador](https://www.python.org/downloads/) e siga as instruções;
2. **Bibliotecas:**
     - Requests: `$ python -m pip install requests`
     - BeautifulSoup 4: `$ python -m pip install beautifulsoup4`
     - Pandas: `$ python -m pip install pandas`
3. **Selenium:** `$ python -m pip install selenium`
### :wrench: Instalando no Linux
1. **Python 3:** `$ sudo apt-get install python3`
2. **Bibliotecas:**
     - Requests: `$ sudo pip3 install requests`
     - BeautifulSoup 4: `$ sudo pip3 install beautifulsoup4`
     - Pandas: `$ sudo pip3 install pandas`
3. **Selenium:** `$ sudo pip3 install selenium`
> Observação: note que você vai precisar do **gerenciador de pacotes pip**. <br> Se você não tiver, use o comando `$ sudo apt-get install python3-pip`
## :heavy_check_mark: Como Executar
No **cmd/terminal**, abra o diretório onde o arquivo se encontra e use o comando: `$ python nome_arquivo.py`.
> Os arquivos a serem executados podem ser: 
> - [WebScraper-EventsUFSM.py](/WebScraper-EventsUFSM.py);
> - [WebScraper-BusSchedule.py](/WebScraper-BusSchedule.py); e 
> - [ExampleClick.py](/ExampleClick.py).
## :pencil: Composição
Este repositório é composto pelos seguintes arquivos:
| Arquivo | Descrição |
| :--- | :--- |
| [WebScraper-EventsUFSM.py](/WebScraper-EventsUFSM.py) | Arquivo principal que para buscar os eventos |
| [WebScraper-BusSchedule.py](/WebScraper-BusSchedule.py) | Arquivo principal que busca os horários dos ônibus |
| [ExampleClick.py](/ExampleClick.py) | Exemplo de uma simulação de click. |
| [GetSoup.py](/GetSoup.py) | Arquivo arquivo com função auxiliar para buscar o soup. |
| [SearchEvent.py](/SearchEvent.py) | Arquivo com função auxiliar para buscar os eventos. |
| [Horarios.json](/Horarios.json) | Arquivo gerado através do código. |

### :pushpin: ExampleClick.py e o Driver
Para executar o arquivo [ExampleClick.py](/ExampleClick.py) você deve ter o **driver** do navegador que for utilizar. Por padrão, está definido o chrome na linha 13 (`driver = webdriver.Chrome(options=option)`), com a importação na linha 3 (`from selenium.webdriver.chrome.options import Options`). Pode-se substituir pelo Firefox, Edge, etc., devendo ser alteradas essas linhas de acordo, mas ainda será necessário o driver.
- [Download driver Chrome](https://chromedriver.chromium.org/downloads);
- [Download driver Edge](https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/);
- [Download driver Firefox](https://github.com/mozilla/geckodriver/releases/tag/v0.28.0);
- [Download driver Safari](https://webkit.org/blog/6900/webdriver-support-in-safari-10/).
