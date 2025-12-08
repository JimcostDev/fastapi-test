# Tutorial: Cómo crear tu primer API con FastAPI

En este tutorial, aprenderás a construir una API simple usando **FastAPI**, uno de los frameworks más rápidos y eficientes para Python.

## 📺 Recursos del Tutorial

Haz clic en la imagen para ver el video completo paso a paso:

[![Ver Tutorial en YouTube](https://img.youtube.com/vi/BZZOuM1UpyI/maxresdefault.jpg)](https://youtu.be/BZZOuM1UpyI)

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
