# prova-web-lb

## Descrição do projeto
implementar um site publicado em duas instâncias EC2 (web1 e web2) com Apache, atrás de um Application Load Balancer 
A página exibe o nome do aluno, a data e a identificação da instância para comprovar o balanceamento de carga

## Estrutura do repositório
- site/index.html
- site/style.css
- README.md

## Comandos utilizados para instalação do Apache

### Instalação
```bash
sudo apt update -y
sudo apt install -y apache2
