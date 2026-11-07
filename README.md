# Vuorenvaltias

**Moottoripyörien mäkikiipeilypeli selaimeen – a motorcycle hill climb game for the browser.**

Aja moottoripyörällä suoraan ylös jyrkkää rinnettä niin pitkälle kuin pääset. Peli on tehty oikeiden mäkikiipeilykisojen mallin mukaan: tulos on rinnettä pitkin ajettu matka, jokaisessa kisassa on kolme yritystä ja paras ratkaisee.

Ride a motorcycle straight up a steep slope as far as you can. The game follows the format of real hill climb events: your result is the distance ridden along the slope, each race has three attempts and the best one counts.

▶ **Pelaa / Play:** `https://<käyttäjänimi>.github.io/<repo>/`

---

## Ominaisuudet

- **Isometrinen kuvakulma**, josta näet ajolinjan pitkälle eteen.
- **Fysiikka:** keulinta, takapyörän lipsuminen, jousitus, ilmalennot, kynnysiskut ja painonsiirto.
- **Kahdeksan rataa**, jotka perustuvat oikeiden kisojen mittoihin ja muotoihin. Nimet ovat keksittyjä.
- **Kolme luokkaa:** 125cc, 500cc ja Open, kullakin omat tehot, painot, akselivälit ja moottoriäänet.
- **Kisasarja:** nouse luokasta toiseen pääsemällä sarjan kolmen parhaan joukkoon. Ennen omaa vuoroasi näet siihen asti parhaan suorituksen.
- **Kaverikisa:** 2–6 pelaajaa ajaa vuorotellen samalla laitteella.
- **Vaihtuva sää:** aurinko, pöly, kostea maa, sade ja sumu vaikuttavat pitoon.
- **Kielet:** suomi, englanti ja saksa.
- **Yksi tiedosto:** ei kirjastoja, ei kuvia eikä äänitiedostoja. Grafiikka piirretään ja äänet tuotetaan selaimessa.

## Ohjaus

| | Kosketus | Näppäimistö |
|---|---|---|
| Kaasu | Vasen peukalo ylös | W tai välilyönti |
| Jarru | Vasen peukalo alas | S |
| Kuljettajan asento | Oikea peukalo alas siirtää painoa taakse (oletuksena täysi etukeno) | ↓ = taakse, N = neutraali |
| Ohjaus | Oikea peukalo sivuille | ← → |

Liian taakse nojatessa pyörä keulii ympäri, liian eteen nojatessa takapyörä lipsuu.

## Käyttö

Avaa `index.html` selaimessa. Muita tiedostoja tai asennuksia ei tarvita.

GitHub Pagesiin: lisää `index.html` repon juureen ja valitse **Settings → Pages → Deploy from a branch → main / (root)**.

---

## Features (English)

- Isometric view that shows the line far ahead.
- Physics with wheelies, rear wheel slip, suspension, jumps, ledge impacts and weight shifting.
- Eight tracks modelled on the dimensions and shapes of real hill climb venues (fictional names).
- Three classes: 125cc, 500cc and Open, each with its own power, weight, wheelbase and engine sound.
- Championship mode: finish in the top three to move up a class. Before your turn you watch the best run so far.
- Friends mode: 2–6 players take turns on one device.
- Changing weather: sun, dust, damp ground, rain and fog affect grip.
- Finnish, English and German.
- A single HTML file with no libraries, images or sound files.

**Controls:** left thumb up = throttle, down = brake. Right thumb drag down = shift weight back (the rider starts fully forward), sideways = steer. Keyboard: W/Space throttle, S brake, ↓ lean back, N neutral, ← → steer.

---

## Lisenssi / License

Vuorenvaltias on vapaata ohjelmistoa. Voit levittää ja muokata sitä **GNU General Public License -lisenssin version 3** (tai halutessasi minkä tahansa myöhemmän version) ehtojen mukaisesti. Ohjelmaa levitetään siinä toivossa, että se on hyödyllinen, mutta **ilman mitään takuuta**. Lisenssin koko teksti on tiedostossa [`LICENSE`](LICENSE).

Vuorenvaltias is free software: you can redistribute it and/or modify it under the terms of the **GNU General Public License version 3** as published by the Free Software Foundation, or (at your option) any later version. It is distributed in the hope that it will be useful, but **WITHOUT ANY WARRANTY**; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the [`LICENSE`](LICENSE) file or <https://www.gnu.org/licenses/gpl-3.0.html> for details.

Copyright © 2026 Heikki Heinonen

SPDX-License-Identifier: GPL-3.0-or-later
