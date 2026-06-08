## Elementos do grupo (Breckout 7):
- Anderson Semedo
- Gilson Carvalho
- Veronica Andrade
- Maria Moniz
- Silvania Correia

## Servidor Web Escolhido
- Apache

## Rota de publicação:
- `/var/www/html/index.html`

## Comandos utilizados na instalação e configuração do servidor:
1. **Instalar o servidor**
```bash
sudo apt install apache2 -y
```

2. **Verificar se o apache está funcionando:**
```bash
sudo systemctl status apache2
```

2. **Habilitar apache para iniciar juntamente com o sistema:**
```bash
sudo systemctl enable apache2
```