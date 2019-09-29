# Image-Hunter
 Python - Simples Scrapper que captura imagens em um site.

### Instalação
1. Você precisará ter instalado o Python na sua máquina: https://www.python.org/
2. Você precisará instalar o seguinte pacote: https://pypi.org/project/requests/

Para instalar o pacote `requests` basta rodar o seguinte comando no seu terminal:

	pip install requests

### Rodando o script
Basta realizar os passos a seguir:
1. Clone este repositório
2. Abra o terminal no local repositório clonado em sua máquina
3. Execute o seguinte comando no terminal `python main.py`
4. Insira a URL do site alvo no campo `Insira a URL aqui:` que aparece no console

Feito isso será exibido uma lista de links contendo imagens do site

### Observações:
* O Código pode não funcionar em 100% dos sites, pois é um algoritimo relativamente simples feito por mim apenas com fins de aprendizado;
* O Código não vai funcionar em `Sites Reativos` (React, Angular, Vue...), pelo simples fato de que o scrapping não executa JavaScript e lê apenas o HTML retornado pela url inserida no terminal, ou seja, funcionará apenas em sites estáticos e SSR.