# SOS Antiques
# Instruções de utilização

## Instalação do Site

O site em HTML/CSS/JS é um projeto estático, logo pode ser utilizado tanto em servidores...

## Histórico de versões

### [0.1.0] - DD/MM/AAAA
#### Adicionado
- Adicionado ...
- Para rodar o site é necessário ter as extensões 'HTML CSS Suport & Live Server' se for rodar pelo vscode.
- Caso não tenha ou não queira rodar pelo vscode pode rodar o site abrindo o arquivo index.html no seu navegador.

**Depois de Baixar o código ou clonar**


const userLogado = JSON.parse(localStorage.getItem('userLogado')) || [];

const desejos = anuncios.filter(item => item.isFavorite !== false && item.email !== userLogado.user && item);
