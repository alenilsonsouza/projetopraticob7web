# Teste para vaga de Estagiário Dev Web

O objetivo deste teste é entender o candidato, sua experiência e sua capacidade de resolução de problemas com dúvidas e detalhes que serão exigidos no dia-a-dia como Estagiário em Desenvolvimento Web.
O teste é baseado em questionamentos e problemas a serem resolvidos.

### Como será feito o teste?
O teste é dividido em 2 etapas:
- Questões teóricas.
- Projeto prático, quer seja correção de bug ou criação do mesmo.

O candidato precisa criar um repositório próprio com a seguinte estrutura:
- No README serão respondidas as questões teóricas (pergunta e resposta), de forma organizada e explicada.
- No próprio repositório estará o projeto prático, corrigido e/ou criado.

Após a finalização, o candidato deve enviar um e-mail para suporte@b7web.com.br com o link do repositório original (este) bem como o link do repositório pessoal com a resolução.

## Questões Teóricas

1. Qual a função do "head" no HTML?
- A tag head tem a função de conter as tag de título, meta, link, script. conteúdo que não aparece para o usuário na página, mas que serve para auxiliar com linkagem e informações sobre a página atual.
2. Quando uma página é criada, ela automaticamente se adapta a todos os tipos de tela? Por que?
- A página só vai se adaptar a todos os tipos de tela se as médias queries estiverem devidamente estilizadas.
3. O código HTML e CSS é renderizado no servidor e repassado para o navegador em forma de imagem?
- Não a renderização é feita toda no navegador, computador do usuário. No servidor ficam armazenados os arquivos.
4. Qual a função das tags H (h1, h2, h3, etc) no HTML?
- Tem a função de níveis de títulos. Sendo h1 com altura da letra maior e até o h6 com a altura menor.
5. O que é SEO e como funciona?
- Search Engine Optimization - é usado para ganhar posicionamento nos buscadores na internet. 
6. O uso de media query é obrigatório em todas as páginas?
Se 
7. Qual a diferença entre CSS Inline e CSS em um arquivo?
- O CSS inline a estilização é atribuída na linha da tag que receber a formatação. Nesse caso somente essa tag é formatada.
CSS em um arquivo é separado somente com o css em um arquivo com extensão .css. Esse é usado para formatar as página lincadas a ele. Em um site todas as página são lincadas a um arquivo externo.
8. Como criar animações no CSS? Dê um exemplo.
- Primeiramente usamos o @keyframe procedido com o nome de identifição da animação. Ex.:

```css
@keyframe transparent {
    0% {opacity:1}
    50% {opacity:0}
    100% {opacity:1}
}
```

A animação foi montada acima, mas ainda não usada. Para usar devemos informar no seletor com o atributo animation. Ex.:

```css
selector {
    animation: transparent .3s ease infinite;
}
```

9. Qual a diferença entre class e ID no CSS?
- class: A classe pode repetir em vários momentos dentro da página e para elementos diferentes. Sendo o atributo class na tag que pode receber várias classes do css para o elemento.
Id: o ID pode ter uma única vez dentro página HTML. Para um único elemento.
10. Quais os diferentes tipos de seletores CSS?
- Tag, class, id

## Projeto prático

O candidato deve criar a página da imagem a seguir:
![Layout](https://i.ibb.co/Bydq2FZ/screencapture-spotify-br-2022-05-10-15-13-17.png)

Algumas observações importantes:
- Fazer a página responsiva não é obrigatório, mas a apresentação dos elementos deve ser o mais próximo possível da imagem.
- Todas as imagens necessárias estão neste repositório, na pasta "assets".
- Efeitos de hover não são obrigatórios, mas são um plus.

O candidato deve estar atento para obedecer principalmente as cores corretas e tamanhos aproximados.
