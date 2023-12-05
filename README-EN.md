# Information about the Project
To run the completely functional project access the following [link](https://drive.google.com/drive/folders/1k9EGD740iwaYUZlXihqT_NE9MO19i1P2?usp=sharing) that will redirect to a google drive folder that has all the files also present in the repository.  

**Running the project:**  

- Access the drive folder and you may create a shortcut or add it to your own drive. *Recomendations: If you do not wish to make any changes in the cod and simply run it, save the shortcut inside the "My Drive" folder in your google drive.*
- Open the [Project](https://colab.research.google.com/drive/1pEULrTHtwCxTVFyMLCdzV8f46pqELLlE?usp=sharing) and run the code following the guidelines.

# Resources used on the project:
Resources used on the project that were not developed by the author.  

[Legal Amazon limits Shapefile](https://geoftp.ibge.gov.br/organizacao_do_territorio/estrutura_territorial/amazonia_legal/2022/Limites_Amazonia_Legal_2022_shp.zip)  

[Legal Amazon Shapefile](http://terrabrasilis.dpi.inpe.br/download/dataset/legal-amz-aux/vector/brazilian_legal_amazon.zip)  

[Legal Amazon warnings - DETER](http://terrabrasilis.dpi.inpe.br/geonetwork/srv/por/catalog.search#/metadata/f2153c4a-915b-48a6-8658-963bdce7366c)  

[Brazil Shapefile](https://geoftp.ibge.gov.br/organizacao_do_territorio/malhas_territoriais/malhas_municipais/municipio_2022/Brasil/BR/BR_Pais_2022.zip)   

[Brazilian States Shapefile](https://geoftp.ibge.gov.br/organizacao_do_territorio/malhas_territoriais/malhas_municipais/municipio_2022/Brasil/BR/BR_UF_2022.zip)  

[PRODES map](http://terrabrasilis.dpi.inpe.br/app/map/deforestation/)  


### Google Earth Engine access tutorial
This tutorial was written for those who never accessed nor have an account in the GEE platform. This step is extremely important to generate a valid API authorization token;

To create a GEE account, open this [link](https://code.earthengine.google.com/register) e seguir as próximas etapas.

**Step 1:**  

Access the site and login to a google account, after logging in you will be redirected to a new page, click on “Register a Noncommercial or Commercial Cloud Project”;

![Step 1](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/1.png)

**Step 2:**  

Select how you would like to use GEE, it is recommended to select unpaid usage. Upon selecting “Unpaid usage”, in Project type there should be a list with project types, select the one that you prefer and then click on “Next”;

![Step 2](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/2.png)

**Step 3:**  

Since it should be your first access, upon reaching this step you will need to create a new project. Select “Create a new Google Cloud Project”;

![Step 3](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/3.png)

**Step 4:**  

To create a new project, define an ID to the project in Project-ID. *Important: Do not use uppercase letters in the Project-ID*. After that click on “Continue do Summary”;

![Step 4](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/4.png)

**Step 5:**  

Before continuing the project creation, accept the terms of service (ToS). To do so click on “Cloud Terms of Service”;

![Step 5](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/5.png)

**Step 6:**  

Upon loading the ToS, agree with it and click on “Agree and continue”;

![Step 6](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/6.png)

**Step 7:**  

You will be redirected to the project creation page after agreeing to the ToS, then click on "Continue to Summary”;

![Step 7](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/7.png)

**Step 8:**  

This page shows the project's Summary including all information, you simply need to click on “Confirm”;

![Step 8](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/8.png)


**Step 9:**  

You will be redirected to GGE's Code Editor. If this happens, just close the editor and return to google collab;

![Step 9](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/9.png)

**Step 10:**  

Upon returning to google colab and running the API authorization cell, click on the available link to generate your token;

![Step 10](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/10.png)

**Step 11:**  

You will be redirected to the Notebook Authenticator, it's expected that in Cloud Project the project ID from the recently made project to be autofilled, if that doesn't happen, click on “Choose Project”;

![Step 11](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/11.png)

**Step 11.1:**  

On the Choose Project window you can create a new project or select an existing one. If you choose to create a new project, you just need to define a new ID and click on “Select”;

![Step 11.1](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/12.png)

**Step 11.2:**  

If you wish to select the previously created project, click on “Select an existing Cloud Project”, select the name of the existing project and then click on “Select”;

![Step 11.2](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/13.png)

**Step 12:**  

After selecting the project, the API will ask for a login to a google account. Use the same account used for the GEE account;

![Step 12](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/14.png)

**Step 13:**  

If that window appear, you need to click on “Next”;

![Step 13](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/15.png)

**Step 14:**  

Upon continuing, click on "Select all" and then "Next";

![Step 14](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/16.png)

**Step 15:**  

Copy the generated token and return to Gogle Collab;

![Step 15](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/17.png)

**Step 16:**  

Paste the token on the appointed field and press enter. With that done the API will be authorized.

![Step 16](https://github.com/MottaD2/TCC-Daniella_Motta/blob/e9c0025aff82e5bdc16f21034ffee3a2c37a0c56/_images_/18.png)

# Questions, suggestions and troublesearching:
Contact me via e-mail: mottadaniella@id.uff.br
