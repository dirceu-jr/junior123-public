<p align="center">
  <a target="_blank" href="https://junior123.com"><img width="700" src="https://github.com/dirceup/junior123-public/blob/master/junior123-sunshine.png" /></a>
</p>

Inicio do desenvolvimento: Fevereiro de 2019.

> No começo eu queria usar algumas _APIs_ e fazer um portal com busca, busca de imagens, notícias e compras. Mas eu não conseguiria fazer melhor que as páginas de resultado de busca (_SERP_) do Google ou notícias personalizadas que eles estão servindo então eu resolvi focar em uma experiência de "compras" diferente da disponível no mercado baseada em vídeos de reviews. -- Dirceu

## Protótipo

<img align="left" width="200" src="https://github.com/dirceup/junior123-public/blob/master/prototipo.png" /> Inicialmente, como pode ser visto na imagem ao lado (do dia 3 de Fevereiro de 2019), seria oferecido um menu com lista das categorias mais populares do _e-commerce_, o conteúdo principal seriam imagens em alta resolução de produtos mais vendidos em cada categoria e o menu do lado direito seria um atalho para a rolagem da página (para ir direto ao produto desejado).

## Atual

<img align="right" width="200" src="https://github.com/dirceup/junior123-public/blob/master/atual.png" /> Atualmente (8/5/2020) com versão única para o mercado brasileiro (pt-BR) é oferecido um menu com a lista de categorias mais populares do _e-commerce_, o conteúdo principal são vídeos do [YouTube](https://youtube.com/) dos produtos mais vendidos de cada categoria e o menu do lado direito são ofertas no _e-commerce_ do produto em destaque (para comparação de preços).
<br>
<br>

## Tech

<img align="left" width="62" src="https://github.com/dirceup/junior123-public/blob/master/header-ruby-logo@2x.png" /><img align="right" width="62" src="https://github.com/dirceup/junior123-public/blob/master/js.png" />Desenvolvido como um script em [Ruby](https://www.ruby-lang.org/) que usa tanto a biblioteca _HTTP_ padrão quanto [typhoeus](https://github.com/typhoeus/typhoeus) para acessar informações sobre categorias e produtos da _API_ do [Lomadee](https://developer.lomadee.com/) e vídeos da _API_ do [YouTube](https://developers.google.com/youtube/), são gerados arquivos estáticos que são armazenados e hospedados no Firebase Hosting para máxima performance e CDN. JavaScript é usado em algumas funções dinâmicas como carregamento assíncrono de conteúdo. O layout é fluído e responsivo.

## Desenvolvedores

<a href="https://github.com/mikaelcarrara">Mikael Moratto Carrara - UI Designer</a>

<a href="https://github.com/dirceup">Dirceu Pauka Junior - Software Developer</a>
