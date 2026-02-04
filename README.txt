Para ejecutar este proyecto debemos crear un entorno virtual con el comando:
    python -m venv .venv

Ya con el entorno creado, debemos activarlo:
    .\.venv\Scripts\activate

**EN CASO DE NO FUNCIONAR, EJECUTAR EN POWERSHELL COMO ADMINISTRADOR LOS SIGUIENTES COMANDOS:
    Get-ExecutionPolicy -List
    Set-ExecutionPolicy -ExecutionPolicy RemoteSigned

Con el entorno funcionando, corremos el programa con el comando:
    python flask_app.py
