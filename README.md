# Ivan Sourvillo

[sourvillo.ru](https://sourvillo.ru)

I choose the targets. A crew of Claude agents (Anthropic) does the digging, working as my agents. Every claim below was checked against the source before it went out.

✅ accepted or public · 📝 done, write-up not public yet

## Ciphers

- ✅ **1549 · Charles V papers, Biblioteca Estense, Modena, ff. 131–132.** Ambassador Simon Renard's ciphered dispatch from Paris, 12 July 1549. Henry II's council plans to buy the garrison of the castle of Nice (63 soldiers), while the Count of Tende brings 12 galleys and 300 men to Antibes under cover of building a fort. The plot was known from one line in the *Calendar of State Papers, Spain*; the dispatch itself had never been printed. The key was rebuilt from a decipherment of the time in the same file and S. Tomokiyo's 1548 table. 503 of 531 words read. Accepted into the Cyphersolver ledger: [dbourdeau/cyphersolver#373](https://github.com/dbourdeau/cyphersolver/issues/373).
- 📝 **1902 · *Iskra* correspondence, letter No. 449.** A paragraph of 40 cipher fractions, left unread in the 1969–70 edition of Lenin's correspondence with *Iskra*, gives Lenin's London cover address: "Jacob Richter, 30 Holford Square, Pentonville". The key was Martov's "Hymn of the Newest Russian Socialist", with the refrain counted as one line.
- 📝 **1901 · *Iskra* letter No. 25.** The key, listed as unknown in the literature, is Lermontov's "The Prophet" (1841) in pre-reform spelling: "suitcases to Lepeshinsky in Pskov…".

## Archives

- 📝 **185 Soviet punch cards bought on Avito.** All decoded: a Fortran IV program for the ES EVM, spline routines SPLINE/SEVAL (Forsythe–Malcolm–Moler, 1977) and a local KOEFSP dated 27.10.82, with a sign error in it.

## Devices set free

No earlier public work found:

- 📝 **Evoko Room Manager ERM1001,** Windows CE 5 meeting-room panels. 29 bought in one lot and turned into home wall panels: a music and light remote, a scale. Native USB drivers written for Windows CE: a Dymo S100 scale and a USB rocket launcher.
- 📝 **Freewrite Traveler.** Persistent root over SSH through UART and U-Boot. A layer of my own on top of its Debian: screensavers, overlays, a Russian interface, offline sync over Wi-Fi.

New things in known devices:

- ✅ **Bang & Olufsen Beo4 remote on Flipper Zero.** The protocol was known; sending its 455 kHz carrier straight from Flipper's own IR LED is new. [sourvillo/flipper-beo4-remote](https://github.com/sourvillo/flipper-beo4-remote)
- 📝 **Xiaomi AI Glasses (M2442G1).** The miwear encryption over BLE decoded, live control without the Xiaomi app. Earlier public work covered only file download over Wi-Fi.
- 📝 **Kobo Libra Colour, firmware 4.44.** A Nickel plugin that puts a row of covers from local books, with no account, into the stock library; a Russian language pack for 4.44.
- 📝 **Sen.se Mother and Motion Cookies.** A stand-in for the dead cloud already existed ([freemother](https://github.com/ccarlo64/freemother), 2018). New: the Cookie firmware taken apart, and firmware of my own flashed into a Cookie over the radio.

## Contributions

- ✅ [dbourdeau/cyphersolver#373](https://github.com/dbourdeau/cyphersolver/issues/373): Renard's 1549 dispatch, see above
- [Lucaslhm/Flipper-IRDB#1142](https://github.com/Lucaslhm/Flipper-IRDB/pull/1142): IR codes for the Kodak EasyShare EX811 picture frame
- [kidbomb/flipper-ccid-app#1](https://github.com/kidbomb/flipper-ccid-app/pull/1): answer every CCID command, accept T=1, fix message buffers
- [q1ngyang/open-mobifitness#1](https://github.com/q1ngyang/open-mobifitness/issues/1): AT-R sensor bike, revolution counter and writable resistance
- [sourvillo/flipper-beo4-remote](https://github.com/sourvillo/flipper-beo4-remote): Bang & Olufsen Beo4 remote for Flipper Zero, 455 kHz IR straight from the timer
