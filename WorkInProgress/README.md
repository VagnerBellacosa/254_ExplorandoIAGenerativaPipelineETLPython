# 254_ExplorandoIAGenerativaPipelineETLPython
Explorando IA Generativa em um Pipeline de ETL com Python



###### DESCRIÇÃO

Prepare-se para uma jornada prática pelo mundo da Ciência de Dados neste vídeo! Vamos construir um pipeline ETL (Extração, Transformação e Carregamento), demonstrando a relação entre dados, Inteligência Artificial (IA) e APIs. Extração: A aventura começa com uma planilha simples, de onde extrairemos os IDs dos usuários. Depois, usaremos esses IDs para acessar a API da 'Santander Dev Week 2023' e obter dados mais detalhados, um processo que evidencia a versatilidade na coleta de informações em Ciência de Dados. Transformação: Adentraremos o universo da IA com o GPT-4 da OpenAI, transformando esses dados em mensagens personalizadas de marketing. Veremos como a IA pode ser empregada de maneira inovadora e prática! Carregamento: Finalizaremos o processo enviando essas mensagens de volta para a API da 'Santander Dev Week 2023'. Este passo ilustra como dados transformados são reintegrados em sistemas, completando o ciclo de um pipeline ETL.

**Python****REST****OpenAI API****ChatGPT****ETL**

------

###### Full-Stack

###### Avançado

------

###### ESPECIALISTA



https://web.dio.me/project/explorando-ia-generativa-em-um-pipeline-de-etl-com-python/learning/691df7f1-e1ad-4fc7-b643-0d800ea3fee2?back=/track/santander-bootcamp-2023-ciencia-de-dados-com-python&tab=undefined&moduleId=undefined



 - [**](https://web.dio.me/track/santander-bootcamp-2023-ciencia-de-dados-com-python)

##### Explorando IA Generativa em um Pipeline de ETL com Python

**

 - [**](https://web.dio.me/lab/explorando-ia-generativa-em-um-pipeline-de-etl-com-python/learning/691df7f1-e1ad-4fc7-b643-0d800ea3fee2) - [**](https://web.dio.me/lab/explorando-ia-generativa-em-um-pipeline-de-etl-com-python/learning/e28c7ef5-8262-4b51-b92b-e42bf5040dd1)

<iframe id="ytc56" frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" title="Apresentação e Background" width="100%" height="100%" src="https://www.youtube.com/embed/Yf7NqyDwQp0?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1" data-gtm-yt-inspected-12="true" style="box-sizing: inherit; max-width: none; float: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-optical-sizing: inherit; font-kerning: inherit; font-feature-settings: inherit; font-variation-settings: inherit; font-size: 14px; vertical-align: baseline;"></iframe>



00:14

 

05:42









normal

auto

- CONTEÚDOS
- INFORMAÇÕES

 - [O Que Vamos Desenvolver Neste Lab](https://web.dio.me/lab/explorando-ia-generativa-em-um-pipeline-de-etl-com-python/learning/691df7f1-e1ad-4fc7-b643-0d800ea3fee2)
 - [Apresentação e Background](https://web.dio.me/lab/explorando-ia-generativa-em-um-pipeline-de-etl-com-python/learning/9eb7a36a-c0ac-4e0b-a095-7ee63a907dfc)
 - [Contexto e Preparação](https://web.dio.me/lab/explorando-ia-generativa-em-um-pipeline-de-etl-com-python/learning/e28c7ef5-8262-4b51-b92b-e42bf5040dd1) 
 - [Extract (Extração)](https://web.dio.me/lab/explorando-ia-generativa-em-um-pipeline-de-etl-com-python/learning/6189e808-5bcf-47a7-8a81-bb10af82ff23)
 - [Transform (Transformação ou Enriquecimento)](https://web.dio.me/lab/explorando-ia-generativa-em-um-pipeline-de-etl-com-python/learning/c692dcb6-e617-42b9-ae7e-7e0d664cfb69) 
 - [Load (Carregamento)](https://web.dio.me/lab/explorando-ia-generativa-em-um-pipeline-de-etl-com-python/learning/00711247-1e2a-4816-93a7-d1b015a7d4b7)
 - [Desafio! Crie Seu Próprio Pipeline de ETL](https://web.dio.me/lab/explorando-ia-generativa-em-um-pipeline-de-etl-com-python/learning/4e4ca43e-e1f9-41c4-908f-0484e5072f52) 
 - [Entendendo o Desafio](https://web.dio.me/lab/explorando-ia-generativa-em-um-pipeline-de-etl-com-python/learning/63d1d743-0d7d-411b-82a6-625348c85054)



# Entendendo o Desafio

**Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos explorados até aqui e replique (ou melhore, porque não?) este projeto prático. Para isso, crie seu próprio repositório e aumente ainda mais seu portfólio de projetos no GitHub, o qual pode fazer toda diferença em suas entrevistas técnicas** 😎

Vocês já mergulharam a fundo no mundo da Ciência de Dados conosco! Juntos, construímos um pipeline ETL eficaz, começando com a simples extração de IDs de usuários de uma planilha, seguindo para uma transformação inovadora com a IA do GPT-4 da OpenAI, e culminando no carregamento desses dados transformados de volta ao 'Santander Dev Week 2023'. Agora, o desafio é reimaginar esse processo de ETL. Como vocês aplicariam o que aprenderam em um novo domínio de aplicação, sem depender diretamente de APIs externas (caso queiram simplificar)? Pensem nas infinitas possibilidades e domínios que podem ser explorados, e deixem a criatividade fluir!

### **Links Úteis**

1. ** - [colab.research.google.com](https://colab.research.google.com/drive/1SF_Q3AybFPozCcoFBptDSFbMk-6IVGF-?usp=sharing)**: Link do Notebook criado via Google Colab com todo o código-fonte desenvolvido neste Desafio de Projeto (Lab);
2. ** - [github.com/digitalinnovationone/santander-dev-week-2023-api](https://github.com/digitalinnovationone/santander-dev-week-2023-api)**: GitHub com a API desenvolvida para a Santander Dev Week 2023 com informações úteis (incluindo o link do Swagger e dados importantes sobre a disponibilidade da API). Relevante para quem quiser saber mais sobre o processo de criação da API RESTful consumi neste Lab.

Bons estudos 😉

 

