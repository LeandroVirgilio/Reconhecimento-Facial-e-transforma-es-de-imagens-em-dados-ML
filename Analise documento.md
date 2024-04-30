# DETECÇÃO DE TEXTO 
![logo](https://cloud.google.com/static/vision/docs/images/sign_text.png?hl=pt-br)


## Vamos demosntrar de forma pratica tudo que aprendemos até o momento. 🤓

# Ler texto no Vision Studio

Neste exercício, você usará o serviço Azure AI para explorar os recursos de reconhecimento óptico de caracteres do Azure AI Vision. Você usará o Vision Studio para experimentar a extração de texto de imagens, sem precisar escrever nenhum código.

Um desafio comum da visão computacional é detectar e interpretar texto incorporado em uma imagem. Isso é conhecido como reconhecimento óptico de caracteres (OCR). Neste exercício você usará um recurso de serviços de IA do Azure, que inclui serviços do Azure AI Vision. Em seguida, você usará o Vision Studio para testar o OCR com diferentes tipos de imagens

## Crie um recurso de serviços de IA do Azure

Você pode usar os recursos de OCR do Azure AI Vision com um recurso multisserviço de serviços de IA do Azure . Se ainda não o fez, crie um recurso de serviços de IA do Azure na sua assinatura do Azure.

Em outra guia do navegador, abra o portal do Azure em https://portal.azure.com , entrando com a conta da Microsoft associada à sua assinatura do Azure.

Clique no botão ＋Criar um recurso e pesquise os serviços de IA do Azure . Selecione criar um plano de serviços de IA do Azure . Você será levado a uma página para criar um recurso de serviços de IA do Azure. Configure-o com as seguintes configurações:
Assinatura : sua assinatura do Azure .
Grupo de recursos : selecione ou crie um grupo de recursos com um nome exclusivo .
Região : Leste dos EUA.
Nome : Insira um nome exclusivo .
Nível de preços : Padrão S0.
Ao marcar esta caixa, confirmo que li e compreendi todos os termos abaixo : Selecionado .
Selecione Revisar + criar e depois Criar e aguarde a conclusão da implantação.

## Conecte seu recurso de serviço de IA do Azure ao Vision Studio

Em seguida, conecte o recurso de serviços de IA do Azure provisionado acima ao Vision Studio.

Em outra guia do navegador, navegue até Vision Studio em https://portal.vision.cognitive.azure.com .

Entre com sua conta e certifique-se de usar o mesmo diretório onde você criou seu recurso de serviços de IA do Azure.

Na página inicial do Vision Studio, selecione Visualizar todos os recursos no título Introdução ao Vision .

![logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/vision-resources.png)

 Na página Selecione um recurso para trabalhar , passe o cursor do mouse sobre o recurso que você criou acima na lista e marque a caixa à esquerda do nome do recurso e selecione Selecionar como recurso padrão .

 ###Nota : Se o seu recurso não estiver listado, pode ser necessário atualizar a página.

![logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/default-resource.png)
Feche a página de configurações selecionando o “x” no canto superior direito da tela.

## Extraia texto de imagens no Vision Studio

Num navegador web, navegue até Vision Studio em https://portal.vision.cognitive.azure.com .

Na página inicial Introdução ao Vision , selecione Reconhecimento óptico de caracteres e, em seguida, o bloco Extrair texto de imagens .

No subtítulo Experimente , reconheça a política de uso de recursos lendo e marcando a caixa.

Selecione https://aka.ms/mslearn-ocr-images para baixar ocr-images.zip . Em seguida, abra a pasta.

No portal, selecione Procurar um arquivo e navegue até a pasta em seu computador onde você baixou ocr-images.zip . Selecione advert.jpg e selecione Abrir .

Agora revise o que é retornado:
Nos atributos detectados , qualquer texto encontrado na imagem é organizado em uma estrutura hierárquica de regiões, linhas e palavras.
Na imagem, a localização do texto é indicada por uma caixa delimitadora, conforme mostrado aqui:

![logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/read-text-computer-vision/advert-bounding-boxes.jpg)

Agora você pode tentar outra imagem. Selecione Procurar um arquivo e navegue até a pasta onde você salvou os arquivos do GitHub. Selecione carta.jpg .

![logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/read-text-computer-vision/letter.jpg)

Revise os resultados da segunda imagem. Deve retornar o texto e as caixas delimitadoras do texto. Se você tiver tempo, tente note.jpg e recibo.jpg .

## Limpar

Se não pretende fazer mais exercícios, exclua todos os recursos que não precisa mais. Isso evita acumular custos desnecessários.

Abra o portal do Azure em https://portal.azure.com e selecione o grupo de recursos que contém o recurso que você criou.
Selecione o recurso e selecione Excluir e depois Sim para confirmar. O recurso é então excluído.

## Saber mais

Para saber mais sobre o que você pode fazer com este serviço, consulte a documentação do Azure AI Vision sobre reconhecimento óptico de caracteres .

## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leandro-virgilio-a1460a76/)

## Links Importantes

[Descrição de imagens](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html)



