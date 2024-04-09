# Laboratório-02-Projeto:
***
# Trabalhando com Visão Computacional
***
Este projeto é um dos laboratório do Bootcamp Microsoft Azure AI Fundamentals, promovido através da parceria entre a Microsoft e a DIO.

## Reconhecimento Facial e transformação de imagens em Dados no Azure ML
***

Análise de imagem 4.0 com o AI Vision Service.

## Lendo texto com reconhecimento óptico de caracteres (OCR)
***

Detectar a localização de texto:

* Impresso;

* Escrita à mão.

## Passo a Passo para Reconhecimento de Texto em Comprovantes Fiscais com Azure AI Vision Service
***

O Azure AI Vision Service oferece recursos poderosos para reconhecimento de texto em imagens, incluindo comprovantes fiscais. Vamos seguir um passo a passo para realizar o reconhecimento de texto em comprovantes fiscais usando esse serviço:

**1. Criação de um recurso Azure:**

* Acesse o [portal do Azure](https://portal.azure.com/).
* Crie recurso para começar a usar o serviço de reconhecimento de texto.
  
_*No portal Azure, botão +, criar recurso.*_

![Captura de Tela (130)](https://github.com/WaldeniseMoraes/Lab2-Transformando-imagens-em-objetos./assets/161647255/b7db6f22-e09a-4e03-b312-7dbd510417f8)

_*Ir para categorias, selecionar AI + Machine Learning.*_

![Captura de Tela (131)](https://github.com/WaldeniseMoraes/Lab2-Transformando-imagens-em-objetos./assets/161647255/8bdc6a44-a528-44e3-a187-9682300a4ee5)


_*Em AI + Machine Learning, procure Azure AI Services.*_

![Captura de Tela (132)](https://github.com/WaldeniseMoraes/Lab2-Transformando-imagens-em-objetos./assets/161647255/d02d0467-392b-4e32-9d99-b63fcb9e993b)


* Crie um novo recurso do tipo [Azure Cognitive Services](https://portal.vision.cognitive.azure.com/).

![Captura de Tela (120)](https://github.com/WaldeniseMoraes/Lab2-Transformando-imagens-em-objetos./assets/161647255/f7413702-76b6-4e26-af3c-1760ef9ea062)

**Selecione Standard SO e Marque checkbox**.

**2. Selecione o serviço Computer Vision.**

_*No Portal de Visão, [portal do Azure](https://portal.azure.com/), clicar ver todos recursos.*_

![Captura de Tela (133)](https://github.com/WaldeniseMoraes/Lab2-Transformando-imagens-em-objetos./assets/161647255/eecb2c84-e62b-4239-b6f4-28ed49129173)

_*Selecionar o recurso criado.*_

![Captura de Tela (134)](https://github.com/WaldeniseMoraes/Lab2-Transformando-imagens-em-objetos./assets/161647255/f020696c-0c16-4e6f-84f4-85e6aa875b52)

_*Selecionar extraindo texto de imagens*_

![Captura de Tela (137)](https://github.com/WaldeniseMoraes/Lab2-Transformando-imagens-em-objetos./assets/161647255/fb0f3c5a-6644-4648-94ee-170efaaf6d0c)

_*Marca checkbox*_

![Captura de Tela (138)](https://github.com/WaldeniseMoraes/Lab2-Transformando-imagens-em-objetos./assets/161647255/74793df6-f67c-4e5b-825a-00517c46879a)

_*Fazer upload da imagem desejada.*_

![Captura de Tela (139)](https://github.com/WaldeniseMoraes/Lab2-Transformando-imagens-em-objetos./assets/161647255/d0d69be3-9f78-4e6e-97de-766f7c6b21a3)

_*Resultado do experimento:*_

![Captura de Tela (140)](https://github.com/WaldeniseMoraes/Lab2-Transformando-imagens-em-objetos./assets/161647255/1fb42dc8-1e51-4e92-b23f-9920bcc5a7ef)

**3. Insights:**

*1. Analise e utilize o texto extraído:*

Analise o texto extraído do comprovante fiscal conforme necessário para suas aplicações ou processos específicos. Isso pode incluir a extração de informações relevantes, como valores, datas, nomes de produtos, etc.

*2. Implemente a integração em seu sistema:*

Se necessário, implemente a integração do serviço de reconhecimento de texto em seu sistema ou processo de negócios. Isso pode envolver o desenvolvimento de APIs ou integrações personalizadas, dependendo das suas necessidades.

_*Lembre-se de consultar a documentação específica do serviço de AI Vision que você está usando para obter informações detalhadas sobre como realizar o reconhecimento de texto em comprovantes fiscais. Além disso, verifique se você está em conformidade com todas as políticas de uso e regulamentações relacionadas ao processamento de documentos fiscais.*_
