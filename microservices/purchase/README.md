# Purchase

Uporabnik lahko ob prijavi v sistem prične izpolnjevati oz. nakupovati svojo vinjeto. To stori z *Vnosom registrske tablice*, kjer jo mora vnesti dvakrat, saj lahko tako zmanjšamo ponovitev napak in zahtevamo dvojno preverjanje polja. Nato sledi *Izbira tipa vinjete*, kjer uporabnik izbere, katero vinjeto želi kupiti. Navsezadnje pa ima uporabnik možnost *Izvedba transakcije*, ki nakup zabeleži v bazo in uporabniku javi obvestilo o uspešnosti nakupa. 


| Funkcionalne zahteve | Nefunkcionalne zahteve |
| *** | *** |
| Vnos registrske tablice  | Za potrebe zmanjševanja napak je potrebno vnesti registrsko tablico dvakrat |
| Izbira tipa vinjete | Uporabnik ima na izbiro 4 tipe vinjet ( tedenska, mesečna, letna, polletna) |
| Izvedba transakcije  | Uspešnost nakupa se zabeleži v bazo |



![PurchaseDiagram](https://user-images.githubusercontent.com/1338126/157852323-527a4450-2c8b-46a7-9b10-46c22d3b10c2.png)
