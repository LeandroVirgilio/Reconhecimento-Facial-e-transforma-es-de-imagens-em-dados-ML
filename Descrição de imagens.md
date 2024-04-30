# DESCRIÇÃO DE IMAGENS 
![logo](https://cta.ifrs.edu.br/wp-content/uploads/sites/3/2018/12/18_BoasPrativasDescricaoImagens.jpg)


## Vamos demosntrar de forma pratica tudo que aprendemos até o momento. 🤓

# Analise imagens no Vision Studio
O Azure AI Vision inclui inúmeras capacidades para compreender o conteúdo e o contexto da imagem e extrair informações das imagens. O Azure AI Vision Studio permite-lhe experimentar muitas das capacidades de análise de imagens.

Neste exercício, você usará o Vision Studio para analisar imagens usando as experiências de teste integradas. Suponhamos que o retalhista fictício Northwind Traders tenha decidido implementar uma “loja inteligente”, na qual os serviços de IA monitorizam a loja para identificar os clientes que necessitam de assistência e direcionam os funcionários para os ajudar. Ao utilizar o Azure AI Vision, as imagens captadas por câmaras em toda a loja podem ser analisadas para fornecer descrições significativas do que representam.

## Crie um recurso de serviços de IA do Azure

Você pode usar os recursos de análise de imagem do Azure AI Vision com um recurso multisserviço de serviços de IA do Azure . Se ainda não o fez, crie um recurso de serviços de IA do Azure na sua assinatura do Azure.

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
Em seguida, conecte o recurso de serviço Azure AI provisionado acima ao Vision Studio.

Em outra guia do navegador, navegue até Vision Studio .

Entre com sua conta e certifique-se de usar o mesmo diretório onde você criou seu recurso de serviços de IA do Azure.

Na página inicial do Vision Studio, selecione Visualizar todos os recursos no título Introdução ao Vision .
![LOGO](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/vision-resources.png)

Na página Selecione um recurso para trabalhar , passe o cursor do mouse sobre o recurso que você criou acima na lista e marque a caixa à esquerda do nome do recurso e selecione Selecionar como recurso padrão .

### Nota : Se o seu recurso não estiver listado, pode ser necessário atualizar a página.

![logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/default-resource.png)
Feche a página de configurações selecionando o “x” no canto superior direito da tela.

## Gerar legendas para uma imagem

Agora você está pronto para usar o Vision Studio para analisar imagens tiradas por uma câmera na loja Northwind Traders .

Vejamos a funcionalidade de legenda de imagens do Azure AI Vision. As legendas das imagens estão disponíveis por meio dos recursos Legenda e Legendas densas .

Em um navegador da web, navegue até Vision Studio .

Na página inicial Introdução ao Vision , selecione a guia Análise de imagem e, em seguida, selecione o bloco Adicionar legendas às imagens .

![logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/add-captions.png)

No subtítulo Experimente , reconheça a política de uso de recursos lendo e marcando a caixa.

Selecione https://aka.ms/mslearn-images-for-análise para baixar image-análise.zip . Abra a pasta no seu computador e localize o arquivo chamado store-camera-1.jpg ; que contém a seguinte imagem:

![logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/store-camera-1.jpg)

Carregue a imagem store-camera-1.jpg arrastando-a para a caixa Arrastar e soltar arquivos aqui ou navegando até ela em seu sistema de arquivos.

Observe o texto da legenda gerado, visível no painel Atributos detectados à direita da imagem.

A funcionalidade Caption fornece uma única frase em inglês legível que descreve o conteúdo da imagem.

Em seguida, use a mesma imagem para realizar legendas densas . Retorne à página inicial do Vision Studio e, como fez antes, selecione a guia Análise de imagem e, em seguida, selecione o bloco Legenda densa .

O recurso Dense Captions difere do recurso Caption porque fornece diversas legendas legíveis para uma imagem, uma descrevendo o conteúdo da imagem e outras, cada uma cobrindo os objetos essenciais detectados na imagem. Cada objeto detectado inclui uma caixa delimitadora, que define as coordenadas dos pixels na imagem associada ao objeto.

Passe o mouse sobre uma das legendas na lista de atributos detectados e observe o que acontece na imagem.

![logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/dense-captioning.png)

Mova o cursor do mouse sobre as outras legendas da lista e observe como a caixa delimitadora muda na imagem para destacar a parte da imagem usada para gerar a legenda.

## Marcando imagens

O próximo recurso que você experimentará é a funcionalidade Extrair Tags . Extrair tags é baseado em milhares de objetos reconhecíveis, incluindo seres vivos, cenários e ações.

Retorne à página inicial do Vision Studio e selecione o bloco Extrair tags comuns de imagens na guia Análise de imagem .

Em Escolha o modelo que deseja experimentar , deixe selecionado Produto pré-construído vs. modelo de lacuna . Em Escolha seu idioma , selecione Inglês ou um idioma de sua preferência.

Abra a pasta que contém as imagens que você baixou e localize o arquivo chamado store-image-2.jpg , que se parece com isto:

![logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/store-camera-2.jpg)

Carregue o arquivo store-camera-2.jpg .

Revise a lista de tags extraídas da imagem e a pontuação de confiança de cada uma no painel de atributos detectados. Aqui, a pontuação de confiança é a probabilidade de o texto do atributo detectado descrever o que realmente está na imagem. Observe na lista de tags que ela inclui não apenas objetos, mas ações, como compras , vendas e permanência .

![logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/detect-attributes.png)

## Detecção de objetos

Nesta tarefa, você usa o recurso de detecção de objetos da Análise de imagem. A detecção de objetos detecta e extrai caixas delimitadoras com base em milhares de objetos e seres vivos reconhecíveis.

Retorne à página inicial do Vision Studio e selecione o bloco Detectar objetos comuns em imagens na guia Análise de imagem .

Em Escolha o modelo que deseja experimentar , deixe selecionado Produto pré-construído vs. modelo de lacuna .

Abra a pasta que contém as imagens que você baixou e localize o arquivo chamado store-camera-3.jpg , que se parece com isto:

![logo](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/media/analyze-images-vision/store-camera-3.jpg)

Carregue o arquivo store-camera-3.jpg .

Na caixa Atributos detectados , observe a lista de objetos detectados e suas pontuações de confiança.

Passe o cursor do mouse sobre os objetos na lista Atributos detectados para destacar a caixa delimitadora do objeto na imagem.

Mova o controle deslizante Valor limite até que um valor de 70 seja exibido à direita do controle deslizante. Observe o que acontece com os objetos da lista. O controle deslizante de limite especifica que somente objetos identificados com uma pontuação de confiança ou probabilidade maior que o limite devem ser exibidos.

## Limpar

Se não pretende fazer mais exercícios, exclua todos os recursos que não precisa mais. Isso evita acumular custos desnecessários.

Abra o portal do Azure e selecione o grupo de recursos que contém o recurso que você criou.
Selecione o recurso e selecione Excluir e depois Sim para confirmar. O recurso é então excluído.

## Saber mais
Para saber mais sobre o que você pode fazer com este serviço, consulte a página Azure AI Vision 











## 🔗 Links

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leandro-virgilio-a1460a76/)

## Links Importantes

[Descrição de imagens](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html)



