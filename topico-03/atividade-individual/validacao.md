# Validação
## URLs testados
- `http://<MEU_IP>/topico-03/` ou `http://<MEU_IP>/topico-03/index.html`
  - Acessar a pagina inicial. O que vimos é o que está no ficheiro `index.html`.
- `http://<MEU_IP>/topico-03/about.html`
  - Acessar a pagina sobre. O que vimos é o que está no ficheiro `about.html`.

## Resultado dos testes
- Consegui acessar as paginas com sucesso.
- Tambem consegui navegar de uma pagina para outra.

## Evidências

**Pagina inicial**
![Pagina inicial](./evidencias/accessing-website-via-browser.png)

**Pagina sobre**
![Pagina sobre](./evidencias/about-page.png)

**Retornando os headers do site utilizado o curl**
![headers do site](./evidencias/accessing-website-via-curl.png)
- o `HTTP/1.1 200 OK` diz-nos que foi possivel aceder o site com sucesso.

**Criar a pasta topico-03 e copiar os ficheiros do site para essa pasta**
![Copiar ficheiro utilizando cp](./evidencias/copy-files-to-publication-folder.png)

## Observações