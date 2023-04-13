# Gerador de senhas aleatórias

Este projeto consiste em um gerador de senhas aleatórias de até 30 caracteres, usando a biblioteca Qt Design (PyQt5) para criar a interface gráfica do usuário. Além disso, uma API REST foi criada para retornar senhas aleatórias contendo caracteres maiúsculos, minúsculos, números e caracteres especiais.

<div align="center">
<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExYThkYjI1ZDcxNDFhNGQzZjhmNDNiYzlhYjA1NTQwZjAxYWUwODU2NyZjdD1n/iEE6S2s2QHUAPti3hf/giphy.gif">
</div>

## Funcionalidades

<ul>
<li>Gerar senhas aleatórias de até 30 caracteres</li>
<li>Usar a interface gráfica para gerar senhas facilmente</li>
</ul>

## Como usar

1. Compila o código ou <a href="https://github.com/MateusSanchesRodriguez/Gerador-de-Senha/releases/tag/Latest">download</a> da versão compilada.
   - Para utilizar o gerador de senhas aleatórias, basta executar o arquivo `Gerador de Senha.exe`.

Caso queira fazer alguma alteração no código

1. Copie o código com  `git clone --recursive https://github.com/MateusSanchesRodriguez/Gerador-de-Senha.git`.

Ou se so quiser testar ou usar a API o projeto esta <a href=https://github.com/MateusSanchesRodriguez/Gerador_de_senha_API>aqui</a>

1. Você pode obter uma senha aleatória no formato JSON usando a API REST ao enviar uma solicitação GET para `https://gerador-de-senha.onrender.com/password?length=?`, substituindo o ponto de interrogação pelo tamanho da senha que você deseja. Além disso, é possível visualizar todos os métodos HTTP disponíveis pela API acessando `https://gerador-de-senha.onrender.com/docs`.

### Exemplo de uso da API REST

Copie ou clique na url
curl https://gerador-de-senha.onrender.com/password?length=10

Response

<img src="https://images-ext-2.discordapp.net/external/Uu2gfxIAy-vgowUfrY8UgbluVsltCtF0J39Oo6hfW34/https/i.imgur.com/beD2Y8Bh.jpg">

## Contribuindo

Este projeto está aberto para contribuições! Sinta-se à vontade para enviar pull requests ou abrir issues relatando bugs ou sugestões de melhoria.

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo LICENSE para obter mais informações.
