# Publicação do site
## Nível escolhido
Nível 2 - Intermédio

## Rota escolhida
Apache

## Ficheiros criados
- index.html
- sobre.html
- style.css
## Local de publicação
`/var/www/html/topico-03/`

## Comandos principais utilizados
- **mkdir** para criar as pastas:
  - ex: `sudo mkdir topico-03` - foi utilizador para criar a pasta topico-03 dentro do local da publicação, por isso, a utilização do `sudo` porque a referida localização propriedade do utilizador **root**.

- **cp** para copiar ficheiros:
  - ex: `sudo cp -r /home/andsemedo/skodji-digital/m3-linux/linux-seguranca-cloud/topico-03/atividade-individual/site/* /var/www/html/topico-03/` - este comando foi utilizado para copiar os ficheiros `index.html`, `about.html` e `style.css` dentro da pasta **site** para o local da publicação.

- **curl** para acessar o site publicado:
  - ex: `curl -I http://172.31.172.101/topico-03/` - utilizado para retornar os headers (cabeçalhos) do site publicado.

## Resultado obtido
- Consegui publicar e aceder ao site com sucesso.
## Limitações encontradas
- Não foram encontradas nenhuma limitação.