# 🎬 Aplikacija za praćenje filmova i serija

Jednostavna i funkcionalna veb aplikacija za pretragu, pregled i praćenje omiljenih filmova i serija. Projekat je izrađen u okviru predmeta **Klijentske veb tehnologije** na Fakultetu organizacionih nauka (FON).

---

## 🚀 Funkcionalnosti

- 🔍 **Pretraga sadržaja:** Pretraga filmova i TV serija u realnom vremenu po naslovu.
- 📋 **Detaljan pregled:** Prikaz informacija o izabranom naslovu (opis/sinopsis, žanr, ocena, datum izlaska, glumci i slika/poster).
- ⭐ **Omiljeni naslovi (Watchlist/Favorites):** Dodavanje i uklanjanje filmova i serija iz privatne liste omiljenih sadržaja.
- 📱 **Responzivan dizajn:** Prilagođen prikaz za sve veličine ekrana (mobilni telefoni, tableti, desktop).

---

## 🛠️ Tehnologije i Biblioteke

### Frontend / Klijentski sloj
- **HTML5 & CSS3** – Struktura i stilizovanje korisničkog interfejsa.
- **JavaScript (ES6+)** – Dinamičko manipulisanje DOM-om, asinhroni HTTP zahtevi (`fetch` API / `axios`) i klijentska logika.
- **External API:** Integracija sa javnim filmskim API-jem (npr. *The Movie Database (TMDb) API* ili *OMDb API*) za dohvatanje podataka i slika o filmovima i serijama.
- **LocalStorage:** Čuvanje preferencija i korisničkih lista direktno u veb pregledaču.

---

## ⚙️ Pokretanje Projekta Lokalno

Projekat je klijentska veb aplikacija, tako da je pokretanje brzo i ne zahteva složena okruženja:

### 1. Kloniranje repozitorijuma
```bash
git clone [https://github.com/ogi87/klijentske-veb-tehnologije-filmovi-i-serije.git](https://github.com/ogi87/klijentske-veb-tehnologije-filmovi-i-serije.git)
cd klijentske-veb-tehnologije-filmovi-i-serije
