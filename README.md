# Informações sobre o Projeto

### Tutorial de Acesso ao Google Earth Engine
Este tutorial foi desenvolvido para aqueles que nunca acessaram ou não possuem conta na plataforma do Google Earth Engine. Esta etapa é muito importante para dar continuidade ao processo de gerar o token de autorização da API. Vamos ao tutorial!

Para criar uma conta no GEE, basta acessar este [link](https://code.earthengine.google.com/register) e seguir as próximas etapas.

**Passo 1:**  

Ao acessar o site do google Earth Engine será necessário realizar o login em uma das suas contas do google, após o login você será direcionado para esta página e clicar em “Register a Noncommercial or Commercial Cloud Project” 
![Passo 1](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/1.png)

**Passo 2:**  

Nesta etapa você seleciona como gostaria de utilizar o Earth Engine. Ao selecionar “Unpaid usage”, em Project type será exibida uma lista de tipos de projetos e você seleciona a que lhe interessar, após a escolha clique em “Next”.
![Passo 2](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/2.png)

**Passo 3:**  

Como é o seu primeiro acesso, ao chegar nesta etapa será preciso criar um novo projeto. Então você seleciona “Create a new Google Cloud Project”
![Passo 3](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/3.png)

**Passo 4:**  

Para criar um novo projeto, você precisa definir ID para o projeto em Project-ID. Importante: Não utilize caixa alta para definir o Project- ID.  Feito isto, clique em “Continue do Summary”
![Passo 4](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/4.png)

**Passo 5:**  

Antes de continuar a criação do projeto, é necessário aceitar os termos de serviço. Então clique em “Cloud Terms of Service”
![Passo 5](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/5.png)

**Passo 6:**  

Ao abrir os termos de serviço você concorda com os termos e clique em “Concordar e continuar”
![Passo 6](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/6.png)

**Passo 7:**  

Novamente você será direcionado para a página de criação de projeto, após ter aceitado os termos você clica novamente “Continue to Summary” 
![Passo 7](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/7.png)

**Passo 8:**  

Nesta página aparece as informações do projeto que está sendo criado, basta clicar em “Confirm”
![Passo 8](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/8.png)


**Passo 9:**  

Quando confirmar, você será direcionado para o Code Editor do Google Earth Engine. Se isto acontecer, basta fechar o Code Editor e retornar para o Colab.
![Passo 9](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/9.png)

**Passo 10:**  

Ao retornar para o google colab e rodar a célula de autorização da API, você clica no link disponível para gerar o seu token.
![Passo 10](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/10.png)

**Passo 11:**  

Você será direcionado para o Notebook Authenticator, é esperado que em Cloud Project apareça o ID do projeto que foi Criado anteriormente, caso isso não aconteça você pode clicar em “Choose Project”
![Passo 11](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/11.png)

**Passo 12:**  

Com a janela de Choose Project aberta você pode criar um novo projeto ou selecionar o projeto já existente em Cloud Project. Caso opte por criar um novo projeto, basta escolher um novo ID e clicar em “Select”.
![Passo 12](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/12.png)

**Passo 13:**  

Caso queira selecionar o seu projeto criado anteriormente, basta clicar em “Select an existing Cloud Project”, selecionar o nome do projeto existente e clicar em “Select”.
![Passo 13](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/13.png)

**Passo 14:**  

Realizada as etapas de escolher o projeto, a API irá solicitar novamente que selecione a conta do google. (Utilize a mesma na qual você criou conta no Google Earth Engine)
![Passo 14](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/14.png)

**Passo 15:**  

Caso apareça esta janela, basta clicar em “Continuar”
![Passo 15](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/15.png)

**Passo 16:**  

Após continuar você clica em “Selecionar tudo” e depois “Continuar”
![Passo 16](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/16.png)

**Passo 17:**  

Copie o código de autorização gerado e retorne para o ambiente do Google Colab.
![Passo 17](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/17.png)

**Passo 18:**  

Agora cole o código no campo indicado e aperte enter. Feito isso, a API será autorizada.
![Passo 18](https://github.com/MottaD2/TCC-Daniella_Motta/blob/640b6df5f9138f653ecdde503c34f7884bcbc874/images/18.png)
