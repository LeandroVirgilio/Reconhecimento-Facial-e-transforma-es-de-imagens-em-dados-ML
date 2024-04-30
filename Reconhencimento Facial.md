# Reconhecimento Facial 
![logo](https://img.freepik.com/fotos-gratis/conceito-de-colagem-de-reconhecimento-facial_23-2150038886.jpg?w=1060&t=st=1714434993~exp=1714435593~hmac=b7f09d9515437a406afb9f9e767f519783ca4b3ded387c9d0aaa6c8d13ff3f79)

## Vamos demosntrar de forma pratica tudo que aprendemos até o momento. 🤓

# Detectar rostos no Vision Studio
As soluções de visão geralmente exigem que a IA seja capaz de detectar rostos humanos. Suponha que a empresa varejista fictícia Northwind Traders queira localizar onde os clientes estão em uma loja para melhor atendê-los. Uma maneira de fazer isso é determinar se há algum rosto nas imagens e, em caso afirmativo, retornar as coordenadas da caixa delimitadora que mostram sua localização.

Para testar as capacidades de deteção facial do serviço Azure AI Face, utilizará o Azure Vision Studio . Esta é uma plataforma baseada em UI que permite explorar os recursos do Azure AI Vision sem a necessidade de escrever nenhum código.

## Crie um recurso de serviços de IA do Azure

Você pode usar o serviço Azure AI Face com um recurso multisserviço de serviços de IA do Azure . Se ainda não o fez, crie um recurso de serviços de IA do Azure na sua assinatura do Azure.

Em outra guia do navegador, abra o portal do Azure em https://portal.azure.com , entrando com a conta da Microsoft associada à sua assinatura do Azure.

Clique no botão ＋Criar um recurso e pesquise os serviços de IA do Azure . Selecione criar um plano de serviços de IA do Azure . Você será levado a uma página para criar um recurso de serviços de IA do Azure. Configure-o com as seguintes configurações:
Assinatura : sua assinatura do Azure .
Grupo de recursos : selecione ou crie um grupo de recursos com um nome exclusivo .
Região : Leste dos EUA.
Nome : Insira um nome exclusivo .
Nível de preços : Padrão S0.
Ao marcar esta caixa, confirmo que li e compreendi todos os termos abaixo : Selecionado .
Selecione Revisar + criar e depois Criar e aguarde a conclusão da implantação.

##Conecte seu recurso de serviço de IA do Azure ao Vision Studio
Em seguida, conecte o recurso de serviços de IA do Azure provisionado acima ao Vision Studio.

Em outra guia do navegador, navegue até Vision Studio em https://portal.vision.cognitive.azure.com .

Entre com sua conta e certifique-se de usar o mesmo diretório onde você criou seu recurso de serviços de IA do Azure.

Na página inicial do Vision Studio, selecione Visualizar todos os recursos no título Introdução ao Vision .

O link Visualizar todos os recursos está destacado em Introdução ao Vision no Vision Studio.

![Logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/vision-resources.png)

Na página Selecione um recurso para trabalhar , passe o cursor do mouse sobre o recurso que você criou acima na lista e marque a caixa à esquerda do nome do recurso e selecione Selecionar como recurso padrão .

![Logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/default-resource.png)

Feche a página de configurações selecionando o “x” no canto superior direito da tela.

## Detecte rostos no Vision Studio
Num navegador web, navegue até Vision Studio em https://portal.vision.cognitive.azure.com .

Na página inicial Introdução ao Vision , selecione a guia Face e, em seguida, selecione o bloco Detectar rostos em uma imagem .

No subtítulo Experimente , reconheça a política de uso de recursos lendo e marcando a caixa.

Selecione cada uma das imagens de amostra e observe os dados de detecção facial retornados.

Agora vamos tentar com algumas de nossas próprias imagens. Selecione https://aka.ms/mslearn-detect-faces para baixar detect-faces.zip . Em seguida, abra a pasta no seu computador.

Localize o arquivo chamado store-camera-1.jpg ; que contém a seguinte imagem:

![logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/create-face-solutions/store-camera-1.jpg)

Faça upload de store-camera-1.jpg e revise os detalhes de detecção de rosto retornados.

Localize o arquivo chamado store-camera-2.jpg ; que contém a seguinte imagem:

![logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/create-face-solutions/store-camera-2.jpg)

aça upload de store-camera-2.jpg e revise os detalhes de detecção de rosto retornados.

Localize o arquivo chamado store-camera-3.jpg ; que contém a seguinte imagem:

![loog](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/create-face-solutions/store-camera-3.jpg)

Faça upload de store-camera-3.jpg e revise os detalhes de detecção de rosto retornados. Observe como o Azure AI Face não detectou o rosto que está obscurecido.

Neste exercício você explorou como os serviços de IA do Azure podem detectar rostos em imagens. Se você tiver tempo, sinta-se à vontade para experimentar as imagens de amostra ou algumas de suas próprias imagens.

##Limpar
Se não pretende fazer mais exercícios, exclua todos os recursos que não precisa mais. Isso evita acumular custos desnecessários.

Abra o portal do Azure em https://portal.azure.com e selecione o grupo de recursos que contém o recurso que você criou.
Selecione o recurso e selecione Excluir e depois Sim para confirmar. O recurso é então excluído.
## Saber mais
Para saber mais sobre o que você pode fazer com este serviço, consulte a página do serviço Azure AI Face .

## Para ver experimento completo verificar os arquivos de imagens.











## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leandro-virgilio-a1460a76/)

## Links Importantes

[Detectar Rostos](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)


