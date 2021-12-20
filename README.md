# Azure-Databricks Connect Databricks to Power BI
 Connecting Databricks to Power BI using Azure Active Directory, which adds a much tighter security model and of best experience.


# Creating Azure Databricks workspace


* In the Azure home look for Databricks

![image](https://user-images.githubusercontent.com/92280659/146822105-21505ed9-75f5-43a1-8773-d26948c12ee7.png)


* Select create

![image](https://user-images.githubusercontent.com/92280659/146822260-18f4fad9-2420-4f61-b95a-e9f869850be8.png)


* Create an Azure Databricks workspace

![image](https://user-images.githubusercontent.com/92280659/146822408-7aacde3a-0152-4fbf-ab07-b526dbfe53b0.png)


* Inicie o Workspace 

![image](https://user-images.githubusercontent.com/92280659/146823030-a56346f9-d662-4612-ba67-667aa3d9a185.png)


# Creating the Cluster

* Select create Cluster

![image](https://user-images.githubusercontent.com/92280659/146823621-c0d572d3-f033-43bc-b8f3-fb3682107356.png)

![image](https://user-images.githubusercontent.com/92280659/146823912-2819b7d0-ecb7-4517-866e-c7ba647cbdea.png)


# Carregando Dados

* Go on create, Notebook
* Insert name and Cluster

![image](https://user-images.githubusercontent.com/92280659/146824220-5020d976-baa9-4309-b63a-5fe32495572e.png)

* Upload data

![image](https://user-images.githubusercontent.com/92280659/146824475-b0be64ef-eae0-4c0d-8c53-8c6a556a3883.png)

![image](https://user-images.githubusercontent.com/92280659/146824575-83381428-4240-42b7-b665-f663b4b64632.png)

* Load the data

![image](https://user-images.githubusercontent.com/92280659/146824678-86285306-997b-4f98-a904-92dbd3f6f5aa.png)


# Connecting Power BI to Azure Databricks

* Click get data
* Azure Databricks

![image](https://user-images.githubusercontent.com/92280659/146825313-0d43687f-cae5-4476-8807-eb65e23458be.png)

* Connect 
* Select ServerHostname and HTTP Path on Cluster created
* On the tab JDBC\OBDC

![image](https://user-images.githubusercontent.com/92280659/146826381-ab9da7c0-f91a-4933-9864-a61d3acdcfc4.png)

* Finally select the desired tables
