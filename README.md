# DEMOS entrevista tecnica.


# 1) Descripcion del proyecto:

En los siguentes archivos se evidencia una prueba automatizada donde se realiza con 
selenium webDriver, Eclipse, y Java.


# 2) Instalacion de herramientas:

Para esta prueba vamos a necesitar las siguientes herramientas:

# - JDK de Java:
  - Para instalarlo ingresamos al siguiente enlace => https://www.oracle.com/
  - Para poder descargar un producto necesitamos primero crear una cuenta e iniciar sesión.
  - Despues de iniciar sesión, nos dirigimos a la pestaña de
 
    ![image](https://user-images.githubusercontent.com/95291737/201195783-fa474faf-b1df-4405-bf07-7a132bcb4aa4.png)
    
  - Luego a la pestaña de: 
  
    ![image](https://user-images.githubusercontent.com/95291737/201196308-fb737c12-d935-44c5-9fa3-55af23ab8707.png)
    
    y por ultimo seleccionamos la opcion de JAVA.
   
  - Al momento de ingresar a la opcion nombrada anteriormente, nos va a aparecer la siguiente venta, donde damos un click en la opcion de DOWNLOAD JAVA.
  
    ![image](https://user-images.githubusercontent.com/95291737/201207413-f9811768-a7f2-468c-a285-e2833c7272bf.png)
  
  - Nos ubicamos en la seccion de Java SE Development Kit 8u351, lo descargamos teniendo en cuenta nuestro sistema operativo, en este caso el mio es de 64bits, 
    asi que instalo el siguiente link:
  
   ![image](https://user-images.githubusercontent.com/95291737/201208069-c2f6d2a8-9ee1-414e-9b1e-09228286730b.png)
   
  - y se inicia la descarga automaticamente.
  
  # Ejecutar el SDK:
  
  - Simplemente ejecuta el archivo descargado en el paso anterior, la instalación es muy similar a la de cualquier programa, simplemente damos en «Next» hasta que ya       inicia la instalación, al final te dirá que Java SE Development Kit ha sido instalado correctamente.
 
    ![image](https://user-images.githubusercontent.com/95291737/201208904-18d80e51-e528-4ce7-bdc9-3b7ff3a564be.png)


  # Instalacion de Eclipse 
  
  - ingresa al siguiente enlace: https://www.eclipse.org/downloads/ se te abrirá la siguiente pantalla, donde aparecerá la versión más reciente de eclipse con el botón     «Download».
  
    ![image](https://user-images.githubusercontent.com/95291737/201215184-d38cb267-558d-4105-b436-c4ed57ea6ff4.png)
    
   - Se abrirá la siguiente pantalla y presionamos clic en el botón «Download» e inmediatamente se empezará a descargar el archivo .exe
   
     ![image](https://user-images.githubusercontent.com/95291737/201218837-33f1636c-67ee-4315-96c9-34a6cbcffa7f.png) 
     
  # Ejecutar Eclipse:
  
   - Ejecuta el archivo .exe que se descargó desde la página oficial de eclipse, se abrirá un menú de instalación con las opciones que tenemos para instalar como Java      EE, Java SE, eclipse para C++, entre otros, en este caso seleccionaremos la opción «Eclipse IDE for Java Developers»
   
     ![image](https://user-images.githubusercontent.com/95291737/201219687-9f55fbb1-6f5a-472c-bc69-1b7a4bc8cca0.png)

   - En el campo Installation Folder se establece la ruta de instalación de Eclipse IDE y le damos clic en el botón «Install»

     ![image](https://user-images.githubusercontent.com/95291737/201220013-d6f3dca3-2d2a-41d5-97ee-2d6fa8e02db3.png)

   - Al terminar la instalación de Eclipse para empezar a construir nuestras pruebas con Selenium Webdriver te debe de salir algo como lo que se muestra en la imagen y      significaría que estamos listos ! que eclipse se instaló correctamente. 
   
     Presionas clic en el botón «Launch».
     
     ![image](https://user-images.githubusercontent.com/95291737/201220174-b90061b1-833c-4110-b7b2-c4cadc969642.png)

   - Al ser primera vez que ejecutas Eclipse, te pedirá la ruta de tu workspace (carpeta donde quedaran los proyectos que crees) al tener la ruta seleccionada,         
     presionas clic en el botón «OK». 

# 3) Ejecucion del proyecto

   - Nos ubicamos en la carpeta que se crea por defecto de Eclipse: 

   ![image](https://user-images.githubusercontent.com/95291737/201361702-a0299fe8-73fa-4057-9052-32d8fac095a8.png) 
   
   ![image](https://user-images.githubusercontent.com/95291737/201361854-69c44a7a-71ea-4987-a8eb-523fa2bdd9f6.png)

   - Al abrir la carpeta mencionada anteriormente, creamos una nueva carpeta:
   
   ![image](https://user-images.githubusercontent.com/95291737/201363723-10a81255-4c35-44ac-88da-e8597abd161e.png)
  
   - Entramos a la carpeta que recien creada, y seleccionamos la opcion de GIT BASH
   
   ![image](https://user-images.githubusercontent.com/95291737/201365447-a2b0c190-9002-4512-ac99-b7ad737ad738.png)
   
   - Nos tiene que abrir la siguiente ventana:
   
   ![image](https://user-images.githubusercontent.com/95291737/201368084-0e9e8976-86ed-47cd-bca2-2a1a6e9b8169.png)
   
   - Nos dirijimos al link del repositorio y nos ubicamos en esta seccion, copiando el siguiente enlace:
   
   ![image](https://user-images.githubusercontent.com/95291737/201368836-164bd3ed-7586-46e2-96d7-df17ed59a5a0.png)
   
   - Volvemos a la ventana del GIT BASH copiando el siguiente comando
   
   ![image](https://user-images.githubusercontent.com/95291737/201369186-fc7e7d6d-cfe8-46ca-9263-8a9cdba33bbf.png)
   
   seguido del enlace que copiamos en el repositorio.
  
   ![image](https://user-images.githubusercontent.com/95291737/201371344-7ecd8299-7f10-4759-a7a2-75acf05ddced.png)
   
   - Nos ubicamos de nuevo en la ventana de la herramienta de eclipse y abrimos la carpeta donde clonamos nuestro archivo:
   
   ![image](https://user-images.githubusercontent.com/95291737/201384116-d90e7e9a-fa36-4303-9040-9ff187e928c6.png)
   
   ![image](https://user-images.githubusercontent.com/95291737/201384489-7b59d265-cd84-49eb-a122-2d5036b4c6a2.png)
   
   - Buscamos la carpeta que anteriormente explicamos en este caso llamada 
   
   ![image](https://user-images.githubusercontent.com/95291737/201384782-b571458d-e70f-4f7f-a91c-3982a9a12880.png)
   
   - Al ingresar seleccionamos la carpeta que habiamos creado 
   


   
   


   



   

   
   
   



