# TRABALHANDO-COM-WEB
código interativo onde nao vamos usar editor  e sim #python3.

⚠️ Uso exclusivo para fins educacionais • Desenvolvido por M!ss s3c

📝 Guia: Explorando sites em Python (modo interativo)

1. Abrir o Python interativo

No terminal, digite:

python3


Você verá o prompt interativo >>>.

2. Importar a biblioteca Requests
>>> import requests

3. Acessar um site
>>> site = requests.get("http://nome do site aqui.com.br")

4. Ver conteúdo da página
>>> site.content

5. Ver cabeçalhos HTTP
>>> site.headers

6. Verificar status da resposta
>>> site.status_code

7. Consultar o servidor usado pelo site
>>> site.headers['Server']

8. Sair do modo interativo
>>> exit()

👉 O que você aprendeu aqui

requests.get() → faz uma requisição HTTP ao site.

.content → retorna o conteúdo HTML da página.

.headers → retorna os cabeçalhos HTTP.

.status_code → retorna o código de status HTTP.

.headers['Server'] → identifica o servidor web utilizado pelo site.

O Python interativo é útil para testes rápidos sem criar arquivos.
