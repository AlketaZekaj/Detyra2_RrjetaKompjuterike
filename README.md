# Detyra2_RrjetaKompjuterike

 Ky projek eshte punuar si detyre e dhene nga asistenti i lendes Mergim Hoti,ky projekt eshte i ndare ne dy pjese,pjesa e serverit dhe e klientit ku 4 pajisje te kycura ne nje rrjet me protokolin TCP mund komunikojne me ane te sockets ne gjuhen programuese C#

 # Antaret e grupit 
 Ky projekt u punua nga :
 Albin Murtezaj,
 Albina Kuleta,
 Alketa Zekaj,
 Alnita Kabashi, 

## SERVERI

### Ne pjesen e serverit duhet te permbushen kerkesat :
1. Të vendosen variabla te cilat përmbajnë numrin e portit (numri i portit të jetë i çfarëdoshëm) dhe IP adresën;
2. Të jetë në gjendje të dëgjojë (listen) të paktën të gjithë anëtaret e grupit;
3. Të pranojë kërkesat e pajisjeve që dërgojnë request (ku secili anëtarë i grupit duhet te e ekzekutoje të paktën një kërkesë në server);
4. Të jetë në gjendje të lexoj mesazhet që dërgohen nga klientët;
5. Të jetë në gjendje të jap qasje të plotë të paktën njërit klient për qasje ne folderat/përmbajtjen në file-t në server.

Ne ne pjesen e serverit per te permbushur keto kerkesa kemi perdorur librarit: System.IO,System.Collections.Generic,System.Net,System.Net.Sockets,System.Text,System.Diagnostics.Kemi deklaruar një objekt Socket për serverin dhe një listë për klientët,Serveri inicializohet në një adresë IP dhe portë të caktuar (127.1.0.1:100), kemi perdorur metoda BeginAccept për të pritur për lidhje të reja nga klientët,funksionet për pranimin e lidhjeve dhe përpunimin e tyre:AcceptCallback dhe ReceiveCallback ,f unksionet për manipulimin e klientëve: HandleAdminCommands dhe HandleClientCommands,dhe ne fund kemi bere mbylljen e lidhjeve dhe serverit: CloseAllSockets


## KLIENTI 
### Ne pjesen e klientit: 
1. Të krijohet socket lidhja me server;
2. Njeri nga pajisjet (klientët) të ketë privilegjet write(), read(), execute();
3. Klientët tjerë të kenë vetëm read() permission;
4. Të behet lidhja me serverin duke përcaktuar sakt portin dhe IP Adresën e serverit;
5. Të definohen sakte socket e serverit dhe lidhje të mos dështojë;
6. Të jetë në gjendje të lexojë përgjigjet që i kthehen nga serveri;
7. Të dërgojë mesazh serverit si në formë tekstit;
8. Të ketë qasje të plotë në folderat/ përmbajtjen në server.

Per te permbushur keto kerkesa ne pjese e klientit kemi perdorur librarite :System,System.Net.Sockets,System.Net,System.Text
keto librari te C# qe pedoren veqanerisht per te zhvilluar aplikacione te lidhura me  komunikimin ne rrjeta kompjuterike,kemi perdorur nje Socket per lidhje e klientit me serverin,kemi klasen Encoding për të konvertuar tekstin në bajtë dhe anasjelltas për të pranuar dhe dërguar të dhënat në rrjet,Metoda për lidhjen me serverin :ConnectToServerfunksionin ,kemi perdorur nje Loop për kërkesat dhe përgjigjet,Metoda për dërgimin e kërkesave:
SendRequest dhe ne fund metoda exit.


