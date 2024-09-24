## Pčelarski dnevnik

Aplikacija pomaže korisnicima da vode svoje pčelinjake. Podaci koji se prikupljaju su isključivo informacije o košnicama, pčelinjacima, selidbama košnica, zamenama matica i ostalim aktivnostima od važnosti za pčelarenje. Trenutna verzija ne prikuplja lične podatke korisnika kao što su ime, prezime i email adresa. Svi podaci su smešteni isključivo na mobilnom uređaju korisnika, ne koriste se spoljašni serveri za čuvanje. Samim tim što se podaci nalaze na mobilnom uređaju, korisnik je zadužen za njihovu bezbednost i ima mogućnost brisanja u svakom trenutku.

Moguće je da će našem timu programera biti dostavljene informacije o mobilnom uređaju ukoliko dođe do greške u radu aplikacije. Ti podaci su model uređaja, verzija operativnog sistema, količina slobodne memorije i vreme pojavljivanja greške. Ove informacije su bitne kako bi se Greška što pre otklonila. 

### Dozvole koje su potrebne aplikaciji za pravilan rad su 


| Dozvola | Žašto je potrebno |
| :---: | --- |
| `android.permission.INTERNET` | Pristup internetu se koristi isključvo za slanje grešaka ukoliko dođe do njih. Na ovaj način programeri lakše uočavaju gde je nastao problem i brže se otklanjaju nesavršenosti u radu aplikacije. |
| `android.permission.CAMERA` | Pristup kameri je potreban kako bi se omogućilo skeniranje barkoda na košnici, time postižemo bržu navigaciju unutar aplikacije i lakše upravljanje podacima. |
| `android.permission.FLASHLIGHT` | Kada se skenira barkod košnice, pri slabom osvetljenu korisnik ima mogućnost da uključi lampu telefona radi lakšeg očitavanja. |
| `android.permission.VIBRATE` | Kada se uspešnoo skenira barkod aplikacija daje signal korisniku putem kratke vibracije. |
| `android.permission.READ_EXTERNAL_STORAGE` | Čitanje memorije telefona je potrebno kako bi učitavanje rezervne kopije bilo moguće. |
| `android.permission.WRITE_EXTERNAL_STORAGE` | Za pravljenje rezervnih kopija potrebno nam je da imamo dozvolu upisivanja podataka u memoriju telefona. |
| `android.permission.READ_CALENDAR` | Čitanje događaja i podsetnika iz kalendara koji su napravljeni u aplikaciji. |
| `android.permission.WRITE_CALENDAR` | Za pravljenje novih podsetnika u kalendaru i izmenu starih. Aplikacija nudi mogućnost dodavanja napomena i podsetnika za svaku košnicu, koristi se kalendar telefona kako bi korisniku bilo prikazano obaveštenje o podestniku. |

Politika privatnosti se može ažurirati, a korisnik će biti obavešten o svakoj promeni.

Ukoliko imate bilo kakvih pitanja, budite slobodni da nas kontaktirate na pcelinjak.rs@gmail.com.

Nastavljanjem korišćenja aplikacije, korisnik prihvata navedenu politiku privatnosti.
