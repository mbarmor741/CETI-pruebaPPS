# FastApi Ejemplo

Ejemplo de aplicación FastApi con uso de ORM (SQLlchemy) que accede a BD sqlite.
La aplicación por defecto espera conexiones em el puerto 8000

## Test aplicación en local


```console
alu@xdebian11:~/pruebas$ python3 -m venv venv
alu@xdebian11:~/pruebas$ source venv/bin/activate
(venv) alu@xdebian11:~/pruebas$ pip install -r requirements.txt 
(venv) alu@xdebian11:~/pruebas$ uvicorn app:app --host 0.0.0.0
``` 

Y acceder a `http://localhost:8000/docs`


