# Bazowy obraz z Pythonem
FROM python:3.12-alpine

# Katalog roboczy w kontenerze
WORKDIR /app


COPY index.html /app/

# Port
EXPOSE 8000

# Polecenie startowe
CMD ["python", "-m", "http.server", "8000", "--bind", "0.0.0.0"]
