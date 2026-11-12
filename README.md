# Arcanum: Tarot, Numbers & Stars

A single-page mobile web app that brings together tarot, numerology, astrology, runes, the I Ching, angel numbers, crystals, chakras, and sound frequencies, with a narrator that reads everything aloud. It is inspired by the old "Tarot Magic" PC program: many kinds of readings with the same deck, several deck traditions, and a voice that tells you your reading.

It is one file (`index.html`). There is no server, no account, no tracking and no internet connection needed once the page has loaded. Everything the user saves stays on their own device.

## Guided Tarot Lessons

Open **Tarot → Learn Tarot → Open the lessons**. Ten interactive lessons cover observation, positions, reversals, court cards, connecting cards, comparing two options, comparing deck art, reading with a friend, and reviewing a reading later. Complete both questions in a lesson to save its completion on this device.

## Compare cards and favorite decks

Open **Tarot → Compare Cards** or tap **Compare this card** from a card detail. Choose a card and two decks to inspect their art side by side. Some cards also have short notes on the imagery. Favorite playable decks in **Deck Gallery** to move them to the front of the reading deck picker.

## Oracle guides and guided listening

Open **Oracles → Learn** for shortcuts to separate study guides for repeating numbers, crystals, and chakras. Each has a worked example and a self-check. Open **Oracles → Sound Lab → Guided Listening** for three six-second A/B comparisons with explanations for pitch, pulsing, and tone color.

## Zodiac boundaries and rune practice

Open **Cosmos → Zodiac Boundaries** for dated examples of a tropical Sun sign transition and a Lunar New Year boundary. The lesson links to its source calendars and to February 2024 in Arcanum. Open **Oracles → Runes** to cast the two-rune Support & Friction or four-rune Crossroads layout and study a worked Crossroads reading.

## Interactive learning labs

Open **Numbers → Life Path Methods** to compare two calculations and see what changes when 11, 22, and 33 are retained. Open **Cosmos → Chart Study** for an interactive wheel of all twelve houses and a diagram of seven example aspect angles. Both include practice questions.

## Seasonal practices

Open **Cosmos → Moon** and select a date in the Lunar Calendar. Below the calendar, choose a hemisphere and explore the seasonal and lunar journal prompts. Open the four-card Seasonal Turning Point spread with the selected date and seasonal prompt, then save your reading to add Journal notes.

## Folklore and Symbol Atlas

Open **Oracles → Symbol Atlas** to search six motifs, read their story context, and inspect ten examples from Arcanum’s Tarot art. Every entry links to a source and includes a reflection prompt.

## Bibliomancy

Open **Oracles → Bibliomancy** to draw a passage, browse six public-domain excerpts, or follow a worked reading. Each passage includes its author, original work and source. Save one editable reflection per passage under **Reflections**. Saved notes are included when you export an Arcanum backup.

## Geomancy

Open **Oracles → Geomancy** to cast a shield chart. Enter the parity of 16 rows from a paper cast or generate the rows automatically. Explore all 16 figures and follow a worked chart from the Mothers through the Judge and Reconciler.

## Playing-card cartomancy

Open **Oracles → Playing Cards** for a separate 52-card pack. Reveal a single card or a line of three or five. The Card Library has a reflection prompt for every card, and Learn shows how to read rank and suit together.

## Lenormand

Open **Oracles → Lenormand** for a separate 36-card oracle with its own illustrated faces and back. Draw one card, a pair, or a three- or five-card line. The Card Library explains each symbol, and Practice lets you swap the subject and modifier to see how order changes a reading.

## I Ching line study

Under **Oracles → I Ching**, expand **Study changing lines**. Select any of the 64 hexagrams and toggle its lines to see the original and resulting figures side by side. Random casts include the same six-line breakdown, numbered from the bottom. The reference links open James Legge’s translation of the classical text.

## Dream Journal and worked examples

In **Journal → Dream Journal**, record a dream with its feelings and symbols. Search saved dreams or filter by recurring symbols and date range. Entries stay on the device and are included in the app’s backup export.

In **Cosmos → Moon**, browse the lunar calendar and select any day for its estimated phase and illumination.

The learning sections for Tarot, Numerology, Cosmos, Oracles, and Frequencies include worked examples and exercises you can try or listen to.

## Revisiting readings

Search the Journal by card, deck, question, note, or tag. Open a reading to mark it as a favorite or save comma-separated tags. Saved entries include expandable card interpretations. Completed and saved readings also include a journal prompt and a small practice tied to a card in the spread.

## Custom spreads and calculation details

The **Everyday** category contains spreads for friendship, creativity and transitions, plus a five-position Companion Reading for two people. In **Tarot → Reading**, open the **Custom** spread category and create a template with one to nine named positions. Edit or delete templates from that category. Saved readings retain the template they used, including its original positions, when you edit or delete the template later.

In **Numbers → Cycles**, open **See the calculation** for the steps behind your Personal Year, Month and Day.

## Drawing and sharing

After choosing a spread, use **Shuffle and Draw** for an automatic draw or **Draw by hand** to riffle, shuffle and cut. Fan out the deck and select one face-down card for each position shown. Swipe horizontally to browse each row.

Choose **Share reading** after revealing the spread or from a saved entry in Journal. Choose Feed (4:5), Story (9:16) or Square (1:1), then download the PNG or use the device share menu where supported. For spreads of four or more cards, choose **Carousel** to export numbered 4:5 slides with up to three cards each. Download slides individually or share them together on devices that support sharing multiple files. Under **What to include**, choose whether to show the spread title and position labels, the deck name, and brief card interpretations in the copyable caption. Reading questions and journal notes are excluded from the image and caption.

## Illustrated app sections

Home features an illustrated directory and a dawn scene behind the daily card. Tarot, Numerology, Cosmos, Oracles, Journal, Settings, Card Library, Learn Tarot and Sound Lab each have their own chapter artwork. The Western and Chinese zodiac portraits appear in the sign directories and personalized sign profiles. The chapter art and portraits are bundled for offline use.

## Illustrated tarot decks

Open **Tarot → Reading** and choose **Alice in Wonderland**, **Gilded Nocturne**, **Felix the Cat**, **Otherworld Ways**, **Circle of Seasons**, **Woodland Folklore**, **Tides & Legends**, **Once Upon a Time**, **City of Capes**, **Aether Circuit**, **Draconic Atlas**, **The Infernal Masquerade**, **Clockwork Observatory**, **Gothic Library**, **Midnight Diner**, **The Hourglass Desert**, **Wind and Water**, **The Unseen Geometry**, or **The Light Between** before selecting a spread. Each edition has 78 individual painted scenes. Choosing a deck also sets the daily card and card library artwork. Existing deck traditions are available under **Original decks**. Open **Tarot → Deck Gallery** to see playable decks and preview their faces and backs, or change the deck in **Card Library** to browse without changing your current reading.

The bundled illustrations are embedded in the built HTML for offline use. The source images are in `art/editions/` for rebuilding the app. Optional Art Studio overrides remain available separately.


---

## Spirit Animal Tarot

Choose **Spirit Animal Tarot** in the Deck Gallery or reading setup. It includes 78 individual wildlife illustrations and a matching back. The GitHub update contains the new page and the complete `art/editions/spirit-animal/` folder. Upload the files from inside the update archive, keeping the folder path and existing decks.

## Contents of this package

| Item | What it is |
|---|---|
| `index.html` | The app page, scripts, and styles. It loads artwork from the neighboring `art/` folder. |
| `README.md` | This guide. |
| `ART_GUIDE.txt` | Every image file name plus a ready-made ChatGPT prompt for each of the 104 pictures. |
| `art/` | Built-in illustrations under `art/editions/` and folders for optional custom artwork. |
| `.nojekyll` | An empty file that tells GitHub Pages to serve the files as they are. Keep it. |
| `source/` | The editable source code and the build script, in case you want to change the app. |

---

## 1. Putting it online (GitHub Pages)

You need a free GitHub account.

1. On github.com, click **New repository**. Name it, for example, `arcanum`. Set it to **Public** (free Pages hosting requires this on most plans). Click **Create repository**.
2. Click **Add file, then Upload files**. Drag in `index.html`, `.nojekyll`, the `art` folder and (optional) `ART_GUIDE.txt` and `README.md`. Click **Commit changes**.
   - Dot-files like `.nojekyll` can be hidden on some computers. If you can't see it, it is fine to skip it. The app works without it.
   - Empty folders do not upload through the web page. That is fine: the `art` folders are created when you upload your first picture into them (see below).
3. Go to **Settings, then Pages**. Under **Build and deployment**, set **Source** to *Deploy from a branch*, choose branch **main** and folder **/ (root)**, and click **Save**.
4. Wait a minute or two. GitHub shows the address, which looks like `https://YOURNAME.github.io/arcanum/`.
5. Open that address on a phone.

To update an existing site, upload the new `index.html` over the old one in the same folder. Keep the existing `art/editions/` folders and filenames. The page loads artwork using paths relative to itself, including when the site lives under a GitHub Pages project path. If the old version still shows, wait for the Pages deployment, then refresh.

### Putting it on a phone's home screen

- **iPhone:** open the page in **Safari**, tap the Share button, then **Add to Home Screen**.
- **Android:** open it in **Chrome**, tap the three-dot menu, then **Add to Home screen** (or **Install app**).

It then opens full screen like an app.

### Trying it without hosting

To preview the app locally with artwork and PNG exports, run `python -m http.server 8000` from the folder containing `index.html` and `art/`, then open `http://localhost:8000/`. Browsers can restrict exporting images from pages opened directly from disk.

---

## 2. What is in the app

The bottom bar has six areas: **Home, Tarot, Numbers, Cosmos, Oracles, Journal.** The top bar has three buttons: **Aa** (text size and display), **mute** (stops voice and sounds) and **gear** (Settings).

### Home
- **Your Card for Today.** One card a day, the same all day (chosen from the date). Tap to turn it over and hear it.
- Today's moon phase, the planetary ruler of the day, and a personal day number if a birth date is saved.
- A "fact of the day" and quick tiles into every part of the app.

### Tarot
- **29 built-in spreads** in 8 groups:
  - *Quick:* Single Card, Yes or No, Past/Present/Future, Mind/Body/Spirit, Situation/Action/Outcome, The Four Elements.
  - *Classic:* Horseshoe (7), Celtic Cross (10).
  - *Love:* Relationship Mirror (5), Seven Hearts (7).
  - *Work:* Career Path (5), Abundance (5), Two Paths decision (8).
  - *Spirit:* Shadow Work, Self-Love, Soul Journey, Seven Chakras, Tree of Life (10), Elemental Pentagram.
  - *Moon:* New Moon Intentions, Full Moon Release.
  - *Time:* Week Ahead (7), Year Ahead (13, one card per month starting with the current month), Astrological Houses (12).
- **5 deck traditions**, all using the same 78 cards:
  - *Waite-Smith:* the classic names and numbering (Strength VIII, Justice XI).
  - *Thoth:* Crowley-style names (Lust, Adjustment, Art, the Aeon, the Universe), Disks for Pentacles, titled pip cards (such as "Dominion"), and Knight/Queen/Prince/Princess courts.
  - *Marseille:* French names (Le Bateleur, La Papesse, and so on) and the older numbering with Justice at VIII.
  - *Obsidian Oracle* and *Celestial Moon:* two of the app's own visual themes on the same Waite-Smith meanings.
- **Reversed cards**, with a choice of how often they appear (10% to 90%) and how they are read (see "Reversals" below). Reversals can also be switched off completely.
- **Reading length:** Standard, In-depth or Full (see "How readings work").
- **Focus:** General, Love, or Work and money, which changes which part of each card is emphasized.
- A **question field**, a shuffle animation, tap-to-reveal cards, and **Read to me**, which narrates the whole reading and turns the cards over as it goes.
- **Reading as a whole:** patterns across the cards (see below), a story that weaves the cards together, and a summary of the reversed cards.
- **Chord:** plays a blended chord made from the planetary tones of the cards in the spread.
- **Card Library:** all 78 cards, searchable and filterable by suit, with a full detail sheet for each (upright and reversed meaning, love, career, advice, deep background, correspondences, yes/no lean, planetary tone).
- **Learn Tarot:** a Tree of Life diagram and articles (see "Learning library").

### Numbers (numerology)
- **My Numbers:** from a full birth name and birth date: Life Path, Expression, Soul Urge, Personality and Birthday numbers, master numbers (11, 22, 33), karmic debt numbers (13, 14, 16, 19), and a "Life Path in depth" section (money and work, health, spiritual path, growth).
- **Cycles:** personal year, month and day, the universal year, the nine-year cycle, pinnacles and challenges.
- **Name Lab:** try any name or word and see its value, with a choice of **Pythagorean** or **Chaldean** letter values.
- **Compatibility:** compare two people's numbers.
- Also a Lo Shu / birth-grid, missing numbers (karmic lessons), hidden passion, and tarot birth cards connected to the Life Path.
- **Learn:** numerology articles, including one on master numbers.

### Cosmos (astrology)
- **Today:** moon phase and age, the planetary ruler of the day, and the day's astrological flavor.
- **My Sign:** Sun sign profile, element and modality, birthstone, the Chinese zodiac animal and element, the tarot cards for the sign and its three decans.
- **Zodiac:** a zodiac wheel diagram and a profile of each of the 12 signs.
- **Match:** pick any two signs for a compatibility reading built from the angle between them (conjunction, sextile, square, trine, quincunx, opposition) and their elements.
- **Chinese:** the 12 animals and 5 elements.
- **Planets, Moon:** what each planet and house represents; the eight moon phases and a guide to working with them.
- **Learn:** astrology articles, including one on aspects.

### Oracles
- **Runes:** the 24 Elder Futhark runes; cast one, three or five, with reversed meanings where a rune can reverse.
- **I Ching:** cast six lines with three simulated coins. You get the hexagram, its two trigrams, changing lines, the hexagram it becomes, the hidden *nuclear* hexagram and the *opposite* hexagram. All 64 hexagrams are browsable.
- **Angel Numbers:** type any repeating number (111, 444, 1212...) for its meaning, with digit-by-digit analysis for numbers that are not in the list.
- **Crystals:** 36 stones with properties, chakras, signs and uses, searchable.
- **Chakras:** the seven centers, a figure, their tones, and a link to the Seven Chakras spread.
- **Frequencies:** playable tones (see "Frequencies and sound").
- **Sound Lab:** binaural beats and resonance experiments.
- **Learn:** articles on the runes, the I Ching and the chakras.

### Journal
Any reading can be saved. A saved entry keeps the spread, deck, question, cards (with reversals) and a place for your own notes. Entries can be reopened, read aloud again, and deleted. The journal keeps the 200 most recent readings.

### Settings
- **Text & Display** (also available from the Aa button), **Art Studio**, **About You** (name and birth date, used for numerology and greetings), **Voice** (narrator choice, speed, pitch, and a test button), **Readings** (default deck, reversal options and length), **Your Data** (export, import, erase) and **Add to Home Screen** instructions.

---

## 3. How readings work

### Reading length
- **Standard:** a clear reading of each card (meaning, focus-specific note, advice).
- **In-depth:** adds a sentence tying the card to its position, the card's imagery and what it means, a question to sit with, and a closing story that weaves the cards together. A three-card reading is around 900 spoken words (roughly six minutes).
- **Full:** adds love and work readings, astrological, Hebrew-letter and Tree of Life correspondences, numerology, mind and body, background lore, more questions and a small practice for each card. A Celtic Cross at Full length is around 5,000 words (roughly half an hour spoken). The player has skip-forward and skip-back buttons to move between sections.

The setting is stored in Settings and can also be changed on the reading setup screen.

### Reversals
Reversed cards are treated as meaningful, not as bad cards. In Settings, "How reversed cards are read" has four options:
- **Mix of all:** each reversed card in turn is read through a different lens (blocked, shadow, inward).
- **Blocked:** the energy is blocked, delayed or weakened.
- **Shadow:** the same energy in excess, distorted or denied.
- **Inward:** the energy is private, unexpressed or still forming.

Each reversed card also gets its own deep text, and a summary section looks at all the reversed cards together. The Yes/No spread handles reversals as "not yet" or "no, softened". A Learn article, "Reading Reversed Cards: Four Ways In", explains the thinking.

### Patterns across the reading
The "Reading as a Whole" section looks for: Major Arcana weight (or none), a dominant or missing suit, many reversals or none, repeated ranks, Aces (new seeds), Tens (completions), many court cards, a dominant element, elemental dignities between neighboring cards (supportive pairs and pairs in tension), repeated astrological signs or planets, and the numerological number of the whole spread.

### Honesty
Tarot here is a tool for reflection and storytelling. The app says so on screen, and nothing in it is medical, legal, financial or predictive advice.

---

## 4. Frequencies and sound

New in the Oracles area. The app makes real sound in the browser (no audio files). It separates what is **physics** from what is **tradition**:

- **Solfeggio tones** (174, 285, 396, 417, 528, 639, 741, 852, 963 Hz): a traditional set of nine tones with traditional meanings. *Tradition.* The app also says clearly that claims such as "528 Hz repairs DNA" are not supported by research.
- **Planetary tones:** the "cosmic octave." The cycle of each planet, the Sun, the Moon and the Earth raised by octaves into hearing range (for example the Earth year at 136.10 Hz, often linked to the sound Om). The mathematics is exact; the meanings are astrological tradition.
- **Chakra tones:** both the modern Solfeggio mapping and the older Western note mapping.
- **Number tones:** the app's *own* scheme, not an ancient one. Each number 1 to 9 plays a degree of the major scale in pure ratios from C at 264 Hz; master numbers sound an octave above their base.
- **432 Hz vs 440 Hz:** play both and compare, with an honest note on what is and is not known.
- **Personal tones:** with a birth date saved, the app offers the tone of the Life Path number, the Sun sign's ruling planet, and today's planetary ruler.
- **Tone buttons** also appear in each card's detail sheet, each sign profile, Today, the Life Path section and the chakras.
- **Sound Lab, Binaural beats:** six presets (2, 6, 7.83, 10, 18 and 40 Hz) with a 5, 10 or 20 minute timer. A different tone plays in each ear and the brain perceives the difference. **Headphones are required.** The research on their effects is mixed, and the app says so. The 7.83 Hz preset refers to the Schumann resonance, which is real measured physics of the Earth's electromagnetic cavity, though no solid evidence shows it affects people.
- **Sound Lab, Resonance:** hear the Pythagorean ratios (octave 2:1, fifth 3:2, and so on), and a genuine acoustic beat from two close notes.
- **Sound Lab, Harmonics:** builds a harmonic series one overtone at a time.
- A live **waveform** display, a **volume** control, and a floating player with a countdown and a Stop button.
- Safety notes are in the app: keep the volume low, use headphones for binaural beats, do not use while driving, and anyone with a seizure disorder should consult a doctor.

Seven Learn articles explain resonance, Solfeggio, the music of the spheres, the Schumann resonance, binaural beats, 432 Hz and harmonics.

---

## 5. The voice

Narration uses the **Web Speech API** built into the browser, which is free and works offline, so quality depends on the phone.

- Press **Read to me** in a reading, or **Listen** buttons throughout the app.
- A floating bar shows **Pause / Resume / Stop**, and skip buttons for readings with many sections.
- **Settings, Voice:** pick the narrator, the speed and the pitch, with a test button.
- Better voices:
  - **iPhone:** Settings, Accessibility, Spoken Content, Voices. Download an *Enhanced* or *Premium* English voice.
  - **Android:** Google voices usually sound best. Install more in the phone's text-to-speech settings.
- Text is spoken in short pieces to avoid a known problem where some browsers cut off long speech.
- On iPhone, speech may stay silent if the phone's silent switch is on. Turn the switch off.

---

## 6. Text size and accessibility

Reading text as well as hearing it is supported throughout.

- The **Aa** button in the header is always visible.
- **Text size:** 90% to 220% with a slider and A- / A+ buttons. Everything scales, including buttons and card text.
- **High contrast:** brighter text and a darker background.
- **Bold text**, **extra line and letter spacing**, and **bigger buttons**.
- All settings are saved. **Reset** restores the defaults.
- The layout was tested at 200% text size.

---

## 7. Art

### Built-in art
All card art is drawn in code (no image files), so the app loads fast. Each deck tradition has its own colors.
- The 22 **Major Arcana** each have a drawn scene inside a sunburst, with the Hebrew letter, astrological glyph and element.
- **Minor cards** use playing-card style pips; **Aces** show a hand from a cloud; **Courts** show a figure with a face, crown and suit item.
- Diagrams: the zodiac wheel (Cosmos, Zodiac), the Tree of Life (Tarot, Learn) and the chakra figure (Oracles, Chakras).

### Adding your own art
You can replace any of this with your own pictures, for example ones made with ChatGPT.

1. Open `ART_GUIDE.txt` (or the in-app **Settings, Art Studio**). It lists every file name with a ready-made prompt. In the app, tap **Copy prompt** next to any item.
2. Make the picture and save it with the exact name listed (for example `00.jpg` for The Fool).
3. Put it in the `art` folder next to `index.html` (cards go in `art/cards/`). On GitHub, use **Add file, Upload files** inside the right folder. If the folder does not yet exist, choose **Create new file** and type `art/cards/placeholder.txt` to create it, or drag the whole `art` folder in.
4. In the app: **Settings, Art Studio**, turn on **Use my art**.
5. Tap **Check which files were found** to confirm.

Notes:
- **Card pictures** should be portrait, 2:3 (for example 1024 by 1536) and under about 500 KB each. The app adds the card name itself on top of your picture, so ask for **no text** in the image.
- File extensions `.jpg`, `.png`, `.webp` and `.jpeg` all work.
- Missing pictures simply keep the built-in drawing. You can add them over days.
- The same card pictures are used for all five decks.
- The full file list is also in `art/README.txt`: `art/back.jpg` (card back), `art/hero.jpg` (home banner), `art/cards/00.jpg` to `77.jpg` (00 to 21 Major Arcana, 22 to 35 Wands, 36 to 49 Cups, 50 to 63 Swords, 64 to 77 Pentacles), `art/signs/aries.jpg` and the other 11 signs, and `art/animals/rat.jpg` and the other 11 animals.
- Copyright: the prompts ask for original compositions and do not copy any existing deck. You are responsible for any art you add.

---

## 8. Learning library

36 articles in five groups, each with a **Listen** button, plus a 24-term glossary.

- **Tarot (16):** what tarot is and is not, a short history, how the deck is built, the Fool's Journey, the suits and elements, court cards, reversed cards (two articles), elemental dignities, tarot and astrology, tarot and the Kabbalah, asking better questions, the suits in depth, a method for reading a spread, and a daily practice and journal. (A few topics are covered twice, once briefly and once in depth.)
- **Numerology (7):** what it is and where it comes from, the core numbers, master numbers and karmic debt, pinnacles and cycles, Pythagorean vs. Chaldean, your tarot birth cards, and master numbers as gift and burden.
- **Astrology (3):** Western astrology basics, the Chinese zodiac, and aspects.
- **Oracles (3):** the runes, the I Ching and the seven chakras.
- **Frequencies (7):** resonance, Solfeggio, planetary tones, the Schumann resonance, binaural beats, 432 vs 440 Hz, and harmonics.

---

## 9. Privacy and your data

- Nothing leaves the device. There is no account, no analytics and no server.
- Settings and the journal are stored in the browser's local storage (keys `arcanum.v1` and `arcanum.journal.v1`).
- **Settings, Your Data:** **Export** copies everything to the clipboard as text; **Import** pastes it back (use this to move to another phone); **Erase all** wipes everything.
- If the browser is set to clear site data, or the app is opened in a private window, saved readings may not persist. Use Export for a backup.
- Each device and browser has its own copy. Opening the page on a new phone starts fresh unless you import.

---

## 10. Troubleshooting

| Problem | Fix |
|---|---|
| The page is blank or old after an update | Close and reopen it, or refresh the page. On GitHub Pages, wait a minute after uploading. |
| No voice | Check the phone is not on silent (iPhone switch), the volume is up, and tap Read to me again. Try another voice in Settings, Voice. Some browsers (notably Firefox on some phones) have no voices installed. |
| Voice stops partway through a long reading | Tap the skip-forward button, or press Stop and start again. Chrome sometimes pauses very long speech. |
| No sound from tones | Raise the volume slider. Phones need a tap before they allow sound, which Play does. For binaural beats use headphones. Very low tones (under about 100 Hz) are not audible on phone speakers, which is why the beats use a 200 Hz carrier. |
| My art does not appear | Turn on **Use my art** in the Art Studio. Check the folder is called `art` and is next to `index.html`. File names are case-sensitive on GitHub (`00.jpg`, not `00.JPG`). Use **Check which files were found**. |
| Text too small or too large | Tap **Aa** in the header. |
| Journal entries disappeared | Browser data was cleared or a different browser was used. Use Export regularly. |
| Chinese zodiac animal looks wrong for a January or February birthday | The app estimates the date of Lunar New Year. Near that date it shows a warning. Check an official calendar. |
| Sun sign looks wrong on a boundary day | Sign changes happen at different hours each year. The app warns near a boundary; a birth chart with time and place is exact. |

---

## 11. Accuracy notes and limits

- **Symbolic, not scientific.** Tarot, numerology, astrology, runes, the I Ching and chakras are symbolic traditions for reflection. The app says this in several places.
- **Astrology** uses Sun signs only. It does not compute a full birth chart (no rising sign or planet positions). The moon phase is estimated from the average lunar month, accurate to within about a day.
- **Chinese zodiac:** the Lunar New Year date is estimated, not looked up.
- **Planetary tones:** the cycle values come from the "cosmic octave" tradition and were entered by hand. Check them against a reference such as Hans Cousto's published tables if exact figures matter to you.
- **Numerology** follows the common Pythagorean method plus Chaldean as an option. Practitioners differ in details (for example whether master numbers are kept at every step); the app keeps master numbers and says when a reduction applies.
- **Frequency claims:** the app labels tradition and physics separately; healing claims for specific frequencies are not scientifically established.
- **Voice quality** depends entirely on the phone and its installed voices.
- The Waite-Smith card descriptions in the "imagery" text follow the classic imagery; other decks use their own images but the same underlying card meanings.
- Tested in desktop Chrome (headless) with automated checks, with the voice replaced by a test stand-in. The real phone voice quality and the sound of the tones on real phone speakers and headphones have **not** been checked by the author.

---

## 12. For developers: source and rebuilding

`source/` contains the code. It is plain JavaScript and CSS with no frameworks and no dependencies. A Python 3 script combines the scripts and styles into one page and validates the separate artwork files.

```
cd source
python3 build.py        # writes source/dist/index.html
```

Copy the generated `index.html` beside the existing `art/` folder before serving or uploading it.

Files in `source/src/`, in the order the build joins them:

| File | Purpose |
|---|---|
| `data-majors.js`, `data-minors1.js`, `data-minors2.js` | Card text: keywords, upright, reversed, love, career, advice, lore |
| `data-tarot.js` | Builds the 78 cards, the suits, rank info, decans, deck traditions and the built-in spreads |
| `data-deep1.js`, `data-deep2.js`, `data-deep3.js` | The extended text: Major Arcana deep readings, Minor Arcana imagery text, reversal lenses and the combining functions |
| `data-numbers.js`, `engine-num.js` | Numerology texts and the calculation engine |
| `data-cosmos.js` | Signs, Chinese zodiac, moon, planets, houses, birthstones |
| `data-oracles.js` | Runes, the 64 hexagrams and trigram lookup, crystals, chakras, angel numbers |
| `data-learn.js`, `data-extra.js` | Learn articles, glossary, extra numerology depth, sign aspects |
| `data-freq.js` | Frequency data and the frequency Learn articles |
| `art-scenes.js` | The 22 hand-drawn Major Arcana scenes (SVG) |
| `ui-core.js` | State, saving, speech engine, router, text-size system |
| `art-diagrams.js` | Zodiac wheel, Tree of Life and chakra figure |
| `ui-cards.js` | Card drawing and the card detail sheet |
| `ui-tarot.js`, `ui-numbers.js`, `ui-cosmos.js`, `ui-oracles.js`, `ui-misc.js` | The screens |
| `art-studio.js` | The custom-art loader and the Art Studio |
| `snd.js` | The sound engine, Frequencies and Sound Lab |
| `main.js` | Starts the app |
| `style.css` | All styling |

**Adding a source file:** add its name (without `.js`) to the `order` list at the top of `build.py`, in the position where it should load. Files share two global objects: `TM` (data) and `A` (the interface).

**Where to change common things**
- Card meanings: `data-majors.js`, `data-minors1.js`, `data-minors2.js`.
- Longer readings: `data-deep1.js` (Major Arcana) and `data-deep2.js` (Minor Arcana); how readings are assembled is `A.cardReading` in `ui-tarot.js`.
- Spreads: the `S("id", name, ...)` calls in `data-tarot.js`.
- Colors and deck looks: the CSS variables at the top of `style.css` and the `.d-classic`, `.d-thoth` and similar rules.

---

## 13. Version summary

- 78 cards, multiple deck traditions, 29 built-in spreads, reversal support with 3 reading lenses, 3 reading lengths.
- 22 hand-drawn Major Arcana scenes, a custom-art system for 104 image slots, and the Art Studio.
- Numerology (Pythagorean and Chaldean), astrology and sign matching, Chinese zodiac, moon, runes (24), I Ching (64 hexagrams with nuclear and opposite hexagrams), angel numbers, crystals (36), chakras (7).
- Frequencies, Sound Lab, binaural beats and resonance experiments.
- 36 Learn articles, a 24-term glossary, a journal with export and import.
- Text size to 220%, high contrast, bold, spacing and bigger buttons.
- One file, about 485 KB, no external dependencies.

*For reflection and entertainment. Not a substitute for professional advice.*
