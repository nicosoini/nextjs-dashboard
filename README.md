# Next.js Financial Dashboard
Tämä on Laurea-ammattikorkeakoulun Fullstack-kurssilla toteutettu hallintapaneelisovellus. Projekti on rakennettu hyödyntäen nykyaikaisia web-kehityksen työkaluja ja Next.js:n uusimpia ominaisuuksia.

## Ominaisuudet
**Dashboard-näkymä:** Yhteenveto tuloista, laskuista ja asiakkaista.

**Laskujen hallinta (CRUD):** Täydellinen tuki laskujen luomiselle, muokkaamiselle ja poistamiselle.

**Autentikaatio:** Turvallinen kirjautuminen NextAuth.js-kirjastolla.

**Palvelinpuolen logiikka:** Hyödyntää Next.js App Routeria, Server Components -arkkitehtuuria ja Server Actions -toimintoja.

**Tietokanta:** Reaaliaikainen yhteys Neon PostgreSQL -tietokantaan.

**Responsiivisuus:** Tyylitelty Tailwind CSS:llä toimimaan kaikilla laitteilla.

## Tekniset valinnat
Framework: Next.js 14/15 (App Router)

**Kieli:** TypeScript

**Tyylittely:** Tailwind CSS

**Tietokanta:** PostgreSQL (Neon)

**Tunnistautuminen:** NextAuth.js

## Kuvakaappaus
<img width="1899" height="908" alt="image" src="https://github.com/user-attachments/assets/08a1fff8-4b02-44ba-abc2-97a9449f7660" />


## Aloitus (Local Development)
**Kloonaa repo:**

Bash
```
git clone https://github.com/sinun-kayttajanimi/projekti-nimi.git
```

**Asenna riippuvuudet:** 

Bash

```
npm install
```

**Ympäristömuuttujat:**
Luo .env-tiedosto juureen ja lisää tarvittavat tiedot (tietokantayhteys, NextAuth secret jne.).

**Käynnistä sovellus:**

Bash
```
npm run dev
```
Sovellus aukeaa osoitteeseen http://localhost:3000.

## Testitunnukset
Voit testata sovellusta seuraavilla tunnuksilla:


Sähköposti: user@nextmail

Salasana: 123456


## Kurssiprojekti
Tämä työ on tehty osana tietojenkäsittelyn opintoja Laureassa. Projektissa on käytetty pohjana [Learn Next.js](https://nextjs.org/learn). -kurssia, jota on muokattu ja laajennettu kurssivaatimusten mukaisesti.
