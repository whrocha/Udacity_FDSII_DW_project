# Visão Geral do Projeto
## Introdução
Dados do mundo real raramente vem limpos. Colete dados de uma série de fontes em uma variedade de formatos, avalie sua qualidade e arrumação e, então, limpe-os. Isso é chamado de data wrangling. Você irá documentar seus esforços de wrangling em um notebook Jupyter, além de exibi-los por meio de análises e visualizações usando Python e/ou SQL.

O conjunto de dados no qual você irá fazer o wrangling (e analisar e visualizar) é o arquivo de tweets do usuário do Twitter @dog_rates, também conhecido como WeRateDogs. WeRateDogs é uma conta no Twitter que classifica os cães das pessoas com um comentário bem humorado sobre o cão. Ele foi iniciado em 2015 pelo estudante universitário Matt Nelson e recebeu cobertura da mídia internacional. Em outubro de 2017 tinha mais 3,7 milhões de seguidores. Estas classificações têm quase sempre um denominador de 10. Mas e os numeradores? Quase sempre maior que 10. 11/10, 12/10, 13/10, etc. Por quê? Porque "são bons cães, Brent."

WeRateDogs deu à Udacity acesso exclusivo a seu arquivo tweets para este projeto. Este arquivo contém dados básicos de tweets para todos os seus mais de 5000 tweets como eles estavam em 1 de agosto de 2017. Voltaremos a esse assunto em breve.

# Motivação do projeto
## Meta
Sua meta: fazer wrangling dos dados de tweets de WeRateDoga para que você possa criar análises e visualizações interessantes e confiáveis. Sim, WeRateDogs deu à Udacity acesso exclusivo a seu arquivo de tweets, mas ele contém informações muito básicas. Coleta, avaliação e limpeza adicionais são necessárias para análises e visualizações que mereçam uma reação de "Uau!"

## Contexto
Este arquivo contém dados básicos de tweets para os mais de 5000 de seus tweets, mas não tudo. Uma coluna o arquivo contém com certeza: cada texto de tweet, o que eu usei para extrair classificação, nome e "estágio" do cachorro (ou seja, doggo, floofer, pupper e puppo).

## Pontos Principais
Pontos-chave para ter mente quando ao fazer data wrangling para esse projeto:
- Só queremos classificações originais (não retweets) que têm imagens.
- Avaliar e limpar totalmente todo o banco de dados requer um esforço excepcional para que apenas um subconjunto de seus problemas (oito problemas de qualidade e dois problemas de arrumação) precisem ser avaliados e limpos.
- A limpeza inclui a fusão de acordo com as regras de dados arrumados para facilitar a análise e visualização.
