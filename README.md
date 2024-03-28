# Azure-Cognitive-Search
Utilizando AI Search para indexação e consulta de Dados ![]()

DOCUMENTAÇÃO: https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/11-ai-search.html

1. Criar um Serviço de Pesquisa
Acesse o portal do Azure em portal.azure.com.
Crie um novo recurso e selecione "Pesquisa Cognitiva" ou "Azure Cognitive Search".
![criarsearch](https://github.com/IvoJucaBezerra/Azure-Cognitive-Search/blob/main/CRIANDORECURSOS/criar-azure-ai-search.png)
Escolha um nome único para o serviço e selecione a região mais adequada.
Escolha o plano de serviço conforme suas necessidades, considerando requisitos de escalabilidade e recursos disponíveis.
3. Recursos do Azure Necessários
Azure Cognitive Search (plano básico)
Serviços de IA do Azure (plano padrão S0)
Conta de Armazenamento do Azure (LRS)
4. Criar um Índice
Defina o esquema do seu índice, especificando os campos que deseja indexar e pesquisar.
Escolha os tipos de dados adequados para cada campo, como texto, números, datas, etc.
Considere a aplicação de técnicas de análise de texto, como tokenização e stemming, para melhorar a precisão da pesquisa.
Passo a Passo
Criar Recursos do Azure:

Criar um recurso do Azure Cognitive Search, Serviços de IA do Azure e uma conta de armazenamento do Azure.
Carregar Documentos:

Baixar e extrair as avaliações de café.
Carregar os arquivos de avaliações na conta de armazenamento do Azure.
Indexar Documentos:

Utilizar o assistente de importação de dados no portal do Azure para criar um índice e um indexador.
Configurar o indexador para extrair habilidades de IA, como extração de frases-chave, detecção de sentimento e OCR.
Consultar o Índice:

Utilizar o Search Explorer no portal do Azure para testar consultas ao índice.
Escrever consultas para recuperar documentos específicos ou filtrar por critérios, como localização ou sentimento.
Resultados
Com a configuração do índice do Azure Cognitive Search, a Fourth Coffee terá uma ferramenta poderosa para explorar e entender as experiências dos clientes através das avaliações. Além disso, o armazenamento de conhecimento permitirá uma análise mais aprofundada dos dados enriquecidos pela IA, fornecendo insights valiosos para aprimorar os serviços e produtos oferecidos pela empresa.

Este laboratório demonstra como a combinação de Azure Cognitive Search e Serviços de IA do Azure pode agregar valor significativo a empresas que desejam extrair insights de grandes volumes de dados não estruturados, como avaliações de clientes.
