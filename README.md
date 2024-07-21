# greeting-az-func

I am creating an azure function using spring cloud function.  

Create an azure function and storage account.  

then add storage account connection string in azure function.  

Update the **pom.xml** and **local.settings.json** files with info accordingly.

Use these commands in project directory in cmd.  

```
mvn clean package
```

and then  

```
mvn azure-functions:run
```

now you can test your app in local.  

![image](https://github.com/user-attachments/assets/12ff5db3-2942-4b95-bdc4-e2453f613d1a)

and then  

```
mvn azure-functions:deploy
```

and then change the url for testing.  

![image](https://github.com/user-attachments/assets/01c0eddb-5c9b-4977-af5d-42c2563266a2)
  
