# Tutorial: Cómo crear tu primera API con FastAPI

En este tutorial, aprenderás a construir una API simple usando FastAPI, uno de los frameworks más rápidos y eficientes para desarrollar APIs en Python. Te guiaremos paso a paso desde la instalación de dependencias hasta la implementación de rutas y la configuración de la documentación automática.

## Recursos

![Imagen del tutorial](https://firebasestorage.googleapis.com/v0/b/jimcostdev-firebase.appspot.com/o/FASTAPI-MINIATURA.jpg?alt=media&token=1a9de89a-9842-4c6a-ba25-7c65f43e0f1e)

- [Video Tutorial en YouTube](https://youtu.be/BZZOuM1UpyI?si=7E2yZG-BtAja4Q5q)

## Cómo probarlo

1. **Clona este repositorio** ejecutando el siguiente comando:

    ```bash
    git clone https://github.com/JimcostDev/fastapi-test.git
    ```

2. **Crea y activa tu entorno virtual**:

    - Crea un entorno virtual:

        ```bash
        python -m venv venv
        ```

    - Activa el entorno virtual:

        - En **Windows**:

            ```bash
            venv\Scripts\activate
            ```

        - En **macOS y Linux**:

            ```bash
            source venv/bin/activate
            ```

3. **Instala las dependencias requeridas**:

    ```bash
    pip install -r requirements.txt
    ```

4. **Ejecute el servidor con:**
    ```bash
    fastapi dev main.py # mode dev
    fastapi run # mode prod
    ```
5. **Actualizar versión de FastAPI**:
 ```bash
    pip install --upgrade fastapi
 ```
 ### Puedes  instalar las dependecias individualmente con:
```bash
    pip install "fastapi[standard]"
    pip install pymongo
```