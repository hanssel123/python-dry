# python-dry

## PASOS PARA INSTALAR PYTHON 3.12 EN UBUNTU 22.04

1. **Agrega el repositorio `deadsnakes`**:

   ```bash
   sudo add-apt-repository ppa:deadsnakes/ppa
   ```

2. **Actualiza los paquetes**:

   ```bash
   sudo apt update
   ```

3. **Instala Python 3.12 y su módulo venv**:

   ```bash
   sudo apt install python3.12 python3.12-venv
   ```

4. **Verifica la instalación**:

   ```bash
   python3.12 --version
   ```

5. **Crea el entorno virtual con Python 3.12**:

   ```bash
   python3.12 -m venv venv312
   source venv312/bin/activate
   ```

6. **Instala tu proyecto**:

   ```bash
   pip install --upgrade pip
   pip install .
   ```

---

¿Quieres que te dé un script para automatizar todo eso?
