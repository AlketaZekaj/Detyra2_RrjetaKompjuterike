# Detyra2_RrjetaKompjuterike

#### Ky projekt ka per detyre Krjimi i serverit dhe klientit ku 4 pajisje te kycura ne nje rrjet me protokolin TCP mund komunikojne me ane te sockets ne gjuhen programuese C#

## SERVERI

### Ne pjesen e serverit duhet :
1. Të vendosen variabla te cilat përmbajnë numrin e portit (numri i portit të jetë i çfarëdoshëm) dhe IP adresën;
#### 2. Të jetë në gjendje të dëgjojë (listen) të paktën të gjithë anëtaret e grupit;
#### 3. Të pranojë kërkesat e pajisjeve që dërgojnë request (ku secili anëtarë i grupit duhet te e ekzekutoje të paktën një kërkesë në server);
#### 4. Të jetë në gjendje të lexoj mesazhet që dërgohen nga klientët;
#### 5. Të jetë në gjendje të jap qasje të plotë të paktën njërit klient për qasje ne folderat/përmbajtjen në file-t në server.


## KLIENTI 
### Ne pjesen e klientit: 
#### 1. Të krijohet socket lidhja me server;
#### 2. Njeri nga pajisjet (klientët) të ketë privilegjet write(), read(), execute();
#### 3. Klientët tjerë të kenë vetëm read() permission;
#### 4. Të behet lidhja me serverin duke përcaktuar sakt portin dhe IP Adresën e serverit;
#### 5. Të definohen sakte socket e serverit dhe lidhje të mos dështojë;
#### 6. Të jetë në gjendje të lexojë përgjigjet që i kthehen nga serveri;
#### 7. Të dërgojë mesazh serverit si në formë tekstit;
#### 8. Të ketë qasje të plotë në folderat/ përmbajtjen në server.
