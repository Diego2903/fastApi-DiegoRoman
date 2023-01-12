[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=RomanFastApi&metric=alert_status)](https://sonarcloud.io/summary/new_code?id=RomanFastApi)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=RomanFastApi&metric=coverage)](https://sonarcloud.io/summary/new_code?id=RomanFastApi)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=RomanFastApi&metric=ncloc)](https://sonarcloud.io/summary/new_code?id=RomanFastApi)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=RomanFastApi&metric=security_rating)](https://sonarcloud.io/summary/new_code?id=RomanFastApi)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=RomanFastApi&metric=bugs)](https://sonarcloud.io/summary/new_code?id=RomanFastApi)

# Comandos
## Instalar dependencias
`pip install --no-cache-dir --upgrade -r requirements.txt`
## Ejecutar el servicio
`uvicorn app.main:app --host 0.0.0.0 --port 8000`
## Ejecutar pruebas unitarias
`python -m unittest discover tests`
## Compilar Docker
`docker build -t devco/fast-api-example:latest .`
