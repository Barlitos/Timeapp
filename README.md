Timeapp
# timeapp

Do zbudowania obrazu z repo nalezy wydac polecenie : 
docker build -t timeapp https://github.com/Barlitos/timeapp.git#main

nastepnie : 
docker run -d --name timeapp -p 80:80 timeapp

w przegladarce przejsc na adres: localhost
