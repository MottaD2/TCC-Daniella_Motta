# Informações sobre o Projeto
Para utilizar o projeto completamente funcional é necessário acessar este [link](https://drive.google.com/drive/folders/1k9EGD740iwaYUZlXihqT_NE9MO19i1P2?usp=sharing) que o direcionará para o google drive onde contém todos arquivos do projeto também disponibilizados no repositório.  

**Modo de funcionamento:**  

- Ao acessar o drive, você pode criar um atalho da pasta ou baixá-la e depois adicionar ao seu drive. *Recomendações: Caso você não queira fazer alterações no código e apenas rodá-lo, salve o atalho dentro da pasta do seu drive que se chama "Meu Drive"*
- Após adicionar a pasta ao Google Drive, basta abrir o [Projeto](https://colab.research.google.com/drive/1pEULrTHtwCxTVFyMLCdzV8f46pqELLlE?usp=sharing) e rodar o código seguindo as orientações.

# Recursos utilizados no projeto:
Recursos utilizados no projeto que não foram desenvolvidos pela autora.  

[Shapefile dos Limites da Amazônia Legal](https://geoftp.ibge.gov.br/organizacao_do_territorio/estrutura_territorial/amazonia_legal/2022/Limites_Amazonia_Legal_2022_shp.zip)  

[Shapefile da Amazonia Legal](http://terrabrasilis.dpi.inpe.br/download/dataset/legal-amz-aux/vector/brazilian_legal_amazon.zip)  

[Avisos na Amazônia Legal - DETER](http://terrabrasilis.dpi.inpe.br/geonetwork/srv/por/catalog.search#/metadata/f2153c4a-915b-48a6-8658-963bdce7366c)  

[Shapefile do Brasil](https://geoftp.ibge.gov.br/organizacao_do_territorio/malhas_territoriais/malhas_municipais/municipio_2022/Brasil/BR/BR_Pais_2022.zip)   

[Shapefile das Unidades Federativas](https://geoftp.ibge.gov.br/organizacao_do_territorio/malhas_territoriais/malhas_municipais/municipio_2022/Brasil/BR/BR_UF_2022.zip)  

[Mapa do PRODES](http://terrabrasilis.dpi.inpe.br/app/map/deforestation/)  


### Tutorial de Acesso ao Google Earth Engine
Este tutorial foi desenvolvido para aqueles que nunca acessaram ou não possuem conta na plataforma do Google Earth Engine. Esta etapa é muito importante para dar continuidade ao processo de gerar o token de autorização da API. Vamos ao tutorial!

Para criar uma conta no GEE, basta acessar este [link](https://code.earthengine.google.com/register) e seguir as próximas etapas.

**Passo 1:**  

Ao acessar o site do google Earth Engine será necessário realizar o login em uma das suas contas do google. Após o login você será direcionado para esta página, clique em “Register a Noncommercial or Commercial Cloud Project” 

![Passo 1](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/1.png)

**Passo 2:**  

Nesta etapa você selecionará como gostaria de utilizar o Earth Engine. Ao selecionar “Unpaid usage”, em Project type será exibida uma lista de tipos de projetos, você escolha a que lhe interessar, após a escolha clique em “Next”.

![Passo 2](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/2.png)

**Passo 3:**  

Como é o seu primeiro acesso, ao chegar nesta etapa será preciso criar um novo projeto. Marque “Create a new Google Cloud Project”

![Passo 3](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/3.png)

**Passo 4:**  

Para criar um novo projeto, você precisa definir uma ID para o projeto em Project-ID. Importante: Não utilize caixa alta para definir a Project- ID.  Feito isto, clique em “Continue do Summary”

![Passo 4](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/4.png)

**Passo 5:**  

Antes de continuar a criação do projeto, é necessário aceitar os termos de serviço. Então clique em “Cloud Terms of Service”

![Passo 5](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/5.png)

**Passo 6:**  

Ao abrir os termos de serviço, concorde com os termos e clique em “Concordar e continuar”

![Passo 6](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/6.png)

**Passo 7:**  

Novamente você será direcionado para a página de criação de projeto. Após ter aceitado os termos, novamente clique em “Continue to Summary” 

![Passo 7](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/7.png)

**Passo 8:**  

Nesta página aparecem as informações do projeto que está sendo criado, basta clicar em “Confirm” para prosseguir

![Passo 8](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/8.png)


**Passo 9:**  

Quando confirmar, você será direcionado para o Code Editor do Google Earth Engine. Se isto acontecer, basta fechar o Code Editor e retornar para o Colab

![Passo 9](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/9.png)

**Passo 10:**  

Ao retornar para o google colab e rodar a célula de autorização da API, clique no link disponível para gerar o seu token

![Passo 10](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/10.png)

**Passo 11:**  

Você será direcionado para o Notebook Authenticator, é esperado que em Cloud Project apareça o ID do projeto que foi Criado anteriormente, caso isso não aconteça você pode clicar em “Choose Project”

![Passo 11](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/11.png)

**Passo 12:**  

Com a janela de Choose Project aberta você pode criar um novo projeto ou selecionar o projeto já existente em Cloud Project. Caso opte por criar um novo projeto, basta escolher um novo ID e clicar em “Select”.

![Passo 12](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/12.png)

**Passo 13:**  

Caso queira selecionar o seu projeto criado anteriormente, basta clicar em “Select an existing Cloud Project”, selecionar o nome do projeto existente e clicar em “Select”.

![Passo 13](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/13.png)

**Passo 14:**  

Realizadas as etapas de escolher o projeto, a API solicitará novamente que logue a conta do google. (Utilize a mesma na qual você criou conta no Google Earth Engine)

![Passo 14](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/14.png)

**Passo 15:**  

Caso apareça esta janela, basta clicar em “Continuar”

![Passo 15](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/15.png)

**Passo 16:**  

Após continuar, clique em “Selecionar tudo” e depois “Continuar”

![Passo 16](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/16.png)

**Passo 17:**  

Copie o código de autorização gerado e retorne para o ambiente do Google Colab.

![Passo 17](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/17.png)

**Passo 18:**  

Agora cole o código no campo indicado e aperte enter. Feito isso, a API será autorizada.

![Passo 18](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/18.png)

# Dúvidas, sugestões e problemas:  
Basta me contatar via email: mottadaniella@id.uff.br
