### Estas instrucciones para un sistema operativo windows
### Instrucciones:
1. Descargar en el local la herramienta Zincsearch (zincsearch.exe).
2. Abrir la ventana de comandos y situarse en la ruta local donde se encuentre el zincsearch.exe, luego copiar estas 
instrucciones en la ventana de comandos
set ZINC_FIRST_ADMIN_USER=admin
set ZINC_FIRST_ADMIN_PASSWORD=Complexpass#123
mkdir data
zincsearch.exe
3. Si las instrucciones del paso anterior se han ejecutado correctamente, se podrá ingresar al zincsearch con 
http://localhost:4080 
Lo cuál indica que el servicio de ZincSearch está arriba y se puede ingresar a la base de datos para realizar las cargas.
4. Descargar la base de datos de correos enron: http://www.cs.cmu.edu/~enron/enron_mail_20110402.tgz
5. Descomprimir la carpeta y ubicarla en la ruta: *".../Indexer_Mail/Backend/indexer/"* junto con el archivo *Indexer.go*
6. Ejecutar el comanto en terminal ./indexer (Indexara y cargar la base de datos a Zincsearch)
7. Una vez terminada la ejecución ejecutar en el terminal el archivo llamado *router(./router)* ubicado en la ruta *".../Indexer_Mail/Backend/router/"*
8. Una vez el script se esta ejecutando se puede realizar el despliegue del **Frontend**

## Frontend
1. Ingresar por terminal a la ruta *".../Indexer_Mail/Frontend/email-front/"*
2. Una vez dentro instalar todas la dependecias necesarias para la ejecución del codigo con el comando: *npm i*
3. Cuando finalice la instalación el proyecto de Vue podra ejecutarse
4. Ejecutar el proyecto usando el comando: *npm run dev*
5. Termina de compilarse el proyecto podra ingresar a el a partir de la ruta indicada en consola
