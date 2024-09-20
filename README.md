# Análise de notícias com Inteligência Artificial

Gostaria de compartilhar um pequeno projeto (alpha) desenvolvido em Python que tem como objetivo utilizar a inteligência artificial para facilitar análises críticas e semânticas de notícias da forma mais lógica e imparcial possível.

Essencialmente o que ele faz é receber uma url qualquer de um site de notícias que você mesmo entrega, ele realiza o webscraping e te devolve tanto o gráfico de palavras, quanto uma tabela que realiza a análise semântica. Enfim, bem simples.

O que eu acho importante nessa abordagem é que não é realizada nenhuma tentativa de identificar lado político ou fake news, mas independente de opinião ou fonte de notícias, aqui é lido o conteúdo do artigo e o ChatGPT se encarrega sozinho de realizar as análises semânticas.

A partir disso, fica a seu critério avaliar as respostas e chegar a uma conclusão crítica.

É importante destacar que eu não realizo nenhum aferimento de opinião, tudo é feito pelo ChatGPT e o código na íntegra está disponível aqui:
https://github.com/cerqueiralex/project-personal-chatgpt-analise-noticias/

Observação, este projeto ainda é um teste bem simplório, e qualquer um pode ficar à vontade para utilizar e modificar o código.

As bibliotecas utilizadas foram:

- Beautiful Soup (Para web scraping)
- Openai (O Chat GPT faz as análises semânticas)
- Wordcloud + Matplotlib (Para gerar o gráfico de nuvem de palavras)

<img src="https://i.imgur.com/oZDDKEO.jpeg">

## Analisando Notícias Tendenciosas: Ferramentas e Estruturas Lógicas
Identificar notícias tendenciosas exige um olhar crítico e a aplicação de algumas ferramentas analíticas. Ao analisar uma notícia, procure por estes elementos:

Estruturas Lógicas e Análises a Serem Aplicadas:

Fontes:
- Variedade: A notícia cita diversas fontes com diferentes perspectivas? Ou se concentra apenas em uma ou duas fontes que corroboram uma determinada narrativa?
- Credibilidade: As fontes citadas são confiáveis e independentes? Possuem expertise no assunto?
- Citação Direta: As citações são apresentadas de forma completa ou são cortadas para enfatizar um determinado ponto de vista?

Linguagem:

- Carregada de Emoção: A linguagem utilizada é objetiva ou carregada de emoções, adjetivos fortes e julgamentos de valor?
- Generalizações: A notícia utiliza generalizações excessivas ou estereótipos?
- Escolha de Palavras: As palavras escolhidas têm conotação positiva ou negativa?
- Tons Irônicos: A notícia utiliza ironia ou sarcasmo para ridicularizar determinada posição?

Ângulo da Notícia:

- Foco: Qual é o foco principal da notícia? Há outros ângulos possíveis que estão sendo ignorados?
- Contexto: A notícia apresenta o contexto completo do acontecimento ou seleciona apenas os fatos que corroboram uma determinada narrativa?
- Causalidade: A notícia estabelece relações de causa e efeito de forma clara e fundamentada?

Omissão de Fatos:

- Informações Relevantes: Há informações relevantes que foram omitidas da notícia?
- Contra-argumentos: A notícia apresenta os contra-argumentos de forma equilibrada ou os minimiza?

Intenção do Autor:

- Propósito: Qual é o objetivo da notícia? Informar, persuadir ou manipular?
- Viés: A notícia apresenta um viés ideológico claro?
- Interesses: A notícia serve aos interesses de algum grupo ou organização específica?
