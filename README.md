# Código de ejemplo
### La idea es que conozcan el formato que les pedimos al usar github 
#
#### El programa consiste en un Front hecho en [React](URL "https://react.dev/") y un backend hecho en [Django Rest Framework](URL "https://www.django-rest-framework.org/").
#### La utilidad en concreta es crear una lista de comentarios, estos comentarios quedan almacenados en la base de datos, los cuales pueden ser creados, eliminados y vistos mediante la api.

![Texto alternativo](assets/ejemplo.gif)


---

## Instrucciones de ejecución

---
### Primero deben correr el backend. Para ello, en el directorio donde se encuentra el backend, ejecutan los siguientes comandos:  

&nbsp;

##### crear el entorno virtual de python.
```
python3 -m venv .venv
```

##### activar el entorno virtual de python.
```
source .venv/bin/activate
```

##### instala las dependencias
```
pip3 install -r requirements.txt
```

##### hace las migraciones
```
python3 manage.py migrate
```

##### correr la app
```
python3 manage.py runserver
```

### El backend ya estará corriendo en [http://localhost:8000]()

&nbsp;

### Luego deben correr el frontend. Para ello, en el directorio donde se encuentra el frontend, ejecutan los siguientes comandos:  

&nbsp;

##### Instalar las dependencias
```
yarn
```

##### Correr la app en modo desarrollo
```
yarn dev
```

### El frontend ya estará corriendo en [http://localhost:5173]()

