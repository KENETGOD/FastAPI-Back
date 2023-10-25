python -m venv venv

Set-ExecutionPolicy Unrestricted -Scope Process

venv\Scripts\activate

pip install fastapi

pip install "uvicorn[standard]"

uvicorn main:app --reload