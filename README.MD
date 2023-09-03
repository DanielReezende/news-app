## Aplicativo (NEWS APP)

Descrição: Um aplicativo que exibe as últimas notícias de diferentes categorias e permite aos usuários ler artigos completos.

## Layout de Referência

Link do figma: [News App UI Kit](https://www.figma.com/file/txHiutpNG7rPI2fm43HJby/News-App-UI-Kit-(Community)?type=design&node-id=89-1&mode=design&t=jbpvDMex3ZbZ9h70-0)

*OSB: O layout apresentado é apenas uma sugestão não precisa ser seguido fielmente.*

## Requisitos Mínimos

- Tela inicial com categorias de notícias (por exemplo, Tecnologia, Esportes, Entretenimento).
- Ao selecionar uma categoria, o aplicativo deve exibir uma lista de artigos relacionados a essa categoria.
- Tela de detalhes do artigo que exibe o título, resumo e imagem da notícia, bem como o texto completo quando o usuário seleciona um artigo.
- Capacidade de salvar artigos favoritos no async storage.
- Navegação entre as telas usando um navegador de pilha (Stack Navigator).

## API de Notícias

Para obter dados reais de notícias, você pode usar a API gratuita do News API (https://newsapi.org/). Você precisará se inscrever para obter uma chave de API gratuita. A API oferece uma ampla variedade de fontes de notícias e categorias que você pode utilizar para o seu aplicativo.

Aqui está um exemplo de como você pode usar a API do News API para obter notícias de tecnologia:

- Endpoint da API: https://newsapi.org/v2/top-headlines
- Parâmetros de consulta:
- country: Especifique o país das notícias (por exemplo, US para os Estados Unidos).
- category: Especifique a categoria de notícias (por exemplo, technology para tecnologia).
- apiKey: Sua chave de API obtida após o registro.

## Pontos que seram avaliados

1. Conceitos primários do react native (Componente, estado e propriedade)
2. Boa escrita do código
3. Cumprimento dos requisitos básico
4. Integração com a api
5. Interface de usuário agradavél e concisa

## Método de avaliação

1. Os pontos 1 e 2 citados acima serão pontuados juntos com um valor máximo de 20 pontos
2. O ponto 3 citado acima será pontuado de maneira que cada requisito mínimos atendido pelo aplicativo somará 4 pontos totalizando assim 20 pontos, caso o aplicativo atenda todos os requisitos citados.
3. O ponto 4 citado acima será pontuado com um valor máximo de 10 pontos
4. O ponto 5 citado acima será pontuado com um valor máximo de 10 pontos
