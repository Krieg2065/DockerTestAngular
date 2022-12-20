
Fai una build dell'immagine

docker build -t my-python-app .

Fai una run dell'immagine (mappando la porta del container con la porta del sistema operativo locale)

docker run -p 5000:5000 my-python-app