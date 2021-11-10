# ARMTemplate
Below are the command for all the arm template using azure cli


1st Create Resource Group Arm parameters:-
az deployment create --location "West Europe" --template-file ResourceGrpArmTemp.json --parameters  ResourceGrpArmParams.json 

2nd Storage Accounts—>
az group deployment create -g RGArmTemplateTest --template-file StorageArmTemp.json --parameters storageArmParams.json

3rd AppServiceName—>
az group deployment create -g RGArmTemplateTest --template-file AppServiceArmTemp.json --parameters AppServiceArmParams.json

4th Function App->
az group deployment create -g RGArmTemplateTest --template-file FunctionAppArmTemp.json --parameters FunctionAppArmParams.json

5th PostgreSQL—>
az group deployment create -g RGArmTemplateTest --template-file PostGreSQLArmTemp.json --parameters PostGreSQLArmParams.json


