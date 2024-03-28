# Azure-Cognitive-Search
Utilizando AI Search para indexação e consulta de Dados ![]()

DOCUMENTAÇÃO: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html

Criar um Serviço de Pesquisa
Acesse o portal do Azure em portal.azure.com.
Crie um novo recurso e selecione "Pesquisa Cognitiva" ou "Azure Cognitive Search".
![criarsearch](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/criar-azure-ai-search.png)
Escolha um nome único para o serviço e selecione a região mais adequada.
Escolha o plano de serviço conforme suas necessidades, considerando requisitos de escalabilidade e recursos disponíveis.
![preço](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/alterar-tipodepreco.png)

Recursos do Azure Necessários
Azure Cognitive Search (plano básico)
Serviços de IA do Azure (plano padrão S0)
![criarcognitivo](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/criarServicoCognitivo.png)

![planobasico](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/escolhaprecoBasico.png)


Criar Conta de Armazenamento do Azure (LRS)
Defina o esquema do seu índice, especificando os campos que deseja indexar e pesquisar.
Escolha os tipos de dados adequados para cada campo, como texto, números, datas, etc.
Considere a aplicação de técnicas de análise de texto, como tokenização e stemming, para melhorar a precisão da pesquisa.
![armazenamento](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/armazenamento.png)

Criar Contêiner:
![conteiner](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/criandonovoconteiner.png)

![habilidadescognitivas](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/addHabilidadesCognitivas.png)

Carregar Documentos: Baixar e extrair as avaliações de café. (Na documentação: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html)
![baixarreviews](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/baixarReviews.png)


Carregar os arquivos de avaliações na conta de armazenamento do Azure.
Indexar Documentos: continuando seguindo a documentação, chegaremos nas seguintes etapas:
![](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/selecConteiner.png)  

![](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/habilitarBlob.png)  

![](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/importardados.png)  

![](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/importardados1.png)  

![](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/importardados2.png) 

Criar indexador:

![](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/importardados3.png)

Imagens dos outpus em JSON: 

Continuando seguindo as orientações da documentação!!

![query](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/JSON%20query.png)  

LOCATION:

![location](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/JSONlocation.png)  

ANÁLISE DE SENTIMENTOS:

![negative](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/JSONnegative.png)  



