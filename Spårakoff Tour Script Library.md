# Claude - Spårakoff Tour Script Library

**CONFIDENTIAL — Qt Group Internal Use Only**

Date: 13 November 2026
Version: v0.20
Author(s): Santtu Ahonen (Director of Portfolio)

> **AI GENERATION DISCLAIMER**
> This document was produced with Claude AI assistance within Qt Group's internal Claude environment.
> All data, figures, statistics, and quantitative information contained herein must be independently validated by a qualified human reviewer before being used as a basis for any business decision, customer communication, or external deliverable.
> This document is CONFIDENTIAL and intended for Qt Group internal use only. Do not distribute outside Qt Group without prior written approval.

---

## Executive Summary

**Purpose.** Narration library for the private Spårakoff ride with the global legal team on Wednesday 4 November 2026. Departure is 17:30 from Havis Amanda (Kauppatori), returning there at about 19:30, with no fixed route. Dinner is at 20:00 at Alexanderplats, Eteläesplanadi 22. The library is modular: you name the place and Claude delivers that segment.

**Concept.** The host narrates in his own words from short bullet speaker notes that Claude returns live when he types the place. The content is real, sourced Helsinki history with humour. Into it go sporalogy hints, from physicist Nils Mustelin's 1989 parody of astrology (Skepsis ry); they rise level by level as the narrator slowly "converts". During the ride, guests fill in a passenger card. At the reveal, guests photograph it with an instruction sheet, and their own Claude writes their spårascope.

**Structure.**
- 1 opener.
- 22 location cards as talking points: fact bullets plus four escalating hint levels ("doses"), all as keywords for the narrator to phrase. Three are sombre war-history cards with no jokes: C14 Diana Park 1942, C16 Hietalahdentori 1939/1944 and C17 University main building 1944.
- 7 fillers for situations that can happen anywhere on the route.
- 1 reveal and 1 close.

Spoken, a card runs about 45–60 seconds, or about 60–90 seconds with a hint.

**Ground rules.**
1. Every historical fact is true and sourced. Only the sporalogy is invented.
2. The word "sporalogy" is not used before Level 4. Swedes and Norwegians hear *spå* (to foretell) in it.
3. The Parliament segment stays strictly non-partisan.
4. No fictional quotes are attributed to real people.

**Open items.**
- Route plan from SOK, if available.
- The ◐ items in Section 8, which are not re-verified.
- Confirm that the Parliament card's political angle is what you intended.

> ⚠️ Data in this section requires human validation.

---

## 1. Live protocol

**Start and reset.**
- Before a test or the tour, say: "Tour mode on, count from zero." From then on, Claude answers place names with speaker notes only.
- After a test, say: "Test over, reset." The segment count and used canon points are cleared, so the dry run doesn't eat into Wednesday's arc.

**Trigger.** Type where you are, in English or Finnish, using any cue word listed on a card. Examples: "Senate Square", "Pitkäsilta", "Stadion". Place names are all that's needed.

**Route awareness.** Claude has no GPS. Its sense of position comes from the places the narrator types, and it uses them to keep the narration in step with the ride:

1. **Direction.** From the last two places, Claude works out which way the tram is heading and which landmarks are likely next, using the neighbour map below. Example: Rautatientori, then Pitkäsilta, means heading north, so Hakaniemi, then Kallio and Linnanmäki, are next.
2. **Split cards.** Some cards cover several neighbouring places. Claude delivers only the part for where the tram is now and saves the rest for the next stop. Example: "Pitkäsilta" gets the bridge story; "Hakaniemi", a minute later, gets the May Day march and that segment's dose.
3. **No repeats.** A fact already told, such as Engel dying before the Cathedral was finished, is not told again. Later cards build on earlier ones instead.
4. **Off-script turns.** If a typed place doesn't fit the expected direction, Claude simply re-plots from the new position. No correction is needed.
5. **Looking ahead to the reveal and the close.** If the predicted route will pass a sombre card shortly before a planned reveal or the return to Havis Amanda (Diana Park, for example), Claude keeps that card short and makes sure there is at least one ordinary segment between it and the reveal.
6. **"Next".** Only if you can't name the place, type "next" and Claude uses the predicted next stop. A place name is always more reliable.

**Neighbour map.** For inference only, not a timetable. The usual summer pub-tram loop runs anticlockwise from the railway station via Hakaniemi, Kallio, Linnanmäki, the Opera, Mannerheimintie, Aleksanterinkatu, Senate Square, the Market Square and Kruununhaka [10]. A charter may differ.

| Area | Neighbours | Split rule |
|---|---|---|
| Market Square (Havis Amanda) | Senate Square, Esplanadi, Katajanokka | Opener at the start, reveal at the end. A mid-ride pass gets one short line |
| Senate Square area: C01, C17, C18 | Market Square, Aleksanterinkatu, Kruununhaka | First cue: C01. Next cue in the area: C17 or C18 |
| Kruununhaka / Bank of Finland: C02 | Senate Square, Hakaniemi, Railway Square | |
| Ritarihuone, Presidential Palace: C21 | Senate Square, Market Square, Uspenski | Way into Katajanokka |
| Katajanokka / Uspenski: C03 | C21 on the way in, C22 on the way out | |
| Katajanokka prison hotel, ferry terminal: C22 | Uspenski, Market Square | Way out of Katajanokka; prison part, then ferry part |
| Railway Square: C04 | Kaisaniemi, Pitkäsilta, Three Smiths, Kruununhaka | |
| Pitkäsilta, Hakaniemi: C05 | Railway Square, Kruununhaka, Kallio | Bridge part, then Hakaniemi part |
| Kallio: C06 | Hakaniemi, Linnanmäki | |
| Linnanmäki: C07 | Kallio, Opera | |
| Opera, Stadium: C08 | Linnanmäki, Finlandia Hall | Opera stop and Stadium can be split |
| Finlandia Hall: C09 | Stadium, National Museum, Parliament | |
| National Museum: C19 | Finlandia Hall, Parliament, Opera / Stadium, Lasipalatsi | |
| Parliament: C10 | Finlandia Hall, Kiasma / Oodi | |
| Lasipalatsi, Kiasma, Oodi: C11 | Parliament, Three Smiths, Railway Square | Kiasma / Oodi part and Lasipalatsi part |
| Three Smiths: C15 | Lasipalatsi, Railway Square, Aleksanterinkatu, Esplanadi | |
| Esplanadi, Stockmann, Swedish Theatre: C13 | Three Smiths, Aleksanterinkatu, Market Square, Erottaja | Stockmann clock part (Aleksanterinkatu side) and Esplanadi / Swedish Theatre part |
| Diana Park / Erottaja: C14 | Esplanadi, Bulevardi | Watch the reveal distance (rule 5) |
| Bulevardi, Sinebrychoff: C12 | Erottaja, Old Church, Hietalahdentori | |
| Old Church, Ruttopuisto: C20 | Bulevardi, Erottaja, Hietalahdentori | |
| Hietalahdentori: C16 | Bulevardi | |

**Output: speaker notes.** The narrator speaks in his own words, and Claude returns notes he can take in at a glance, about 60 words at most:
- a bold place title;
- 3–5 fact bullets: keywords and numbers, not sentences, drawn only from the card;
- ✎ a shared local memory, where the card has one;
- 🚋 the hint at the current level, as keywords ending on the punchline; the narrator forms the sentence;
- "Next:" the predicted next stop and its hook.

Sombre cards get no 🚋 line.

**Automatic escalation.** Claude counts the segments delivered and picks the dose level:

| Segment | Level |
|---|---|
| 1 | Opener (seed only) |
| 2–3 | Level 1 |
| 4–6 | Level 2 |
| 7–9 | Level 3 |
| 10 and later | Level 4 |

**Overrides.** You can say any of these at any time:

| You say | Claude does |
|---|---|
| "[place], level 3" | Uses that dose level |
| "[place], short" | Three fact bullets only, about 45 seconds |
| "[place], no dose" | Facts only, no hint |
| "it's 18:40" | Re-syncs the level to the clock: before 18:00 L1, 18:00–18:30 L2, 18:30–19:00 L3, after 19:00 L4 |

**Canon budget.** Each sporalogy canon point is used once (see the tracker in Section 2). Sometimes a "house" building (Cathedral, Bank of Finland, Stadium, Finlandia Hall) is passed early, at a low level. Its card then plants a hook, and Claude pays it off later as a callback.

**Passenger card (designed in a separate thread).** Hand it out at about 18:15–18:30, with the mock-GDPR framing; guests keep it. The narration never refers to it. At the reveal, the host hands out the instruction sheet, and guests photograph both papers so their own Claude can write their spårascope.

**Narrator.** The host. The conversion arc is his: dry and factual at L1–L2, intrigued at L3, a deadpan believer at L4.

**Humour style.** Never point at or explain a joke. No tags like "counsel, I'll leave that to you", "this audience will appreciate…", "I see you approve" or "I'll just leave that there". The punchline is the last word; in the notes it is the last keyword, after the →. The audience is sharp and is treated that way. This applies to improvised segments too.

**Sombre cards (C14, C16, C17).** These cover war history: the core is delivered with no dose and no jokes, and they do not advance the level. Claude adds a short pause line, and the next segment resumes the arc. Avoid putting a sombre card directly before the reveal.

**Scars on buildings.** Whenever a card or an improvised segment mentions damage on a building, Claude attributes it case by case: the 1939–1944 Soviet bombing, or the April 1918 Civil War street fighting. Claude never assumes one or the other without a source. F7 gives the general explanation.

**Fillers.** Say "another tram", "waiting", "this tram", "group reading" (Level 3 and up only) or "sporascope for [name] from [city]".

**Unscripted spot.** Claude returns notes for about 45 seconds of talk, using only well-established facts. If unsure of a fact, Claude leaves it out, because it cannot be flagged aloud. These segments lean more on the joke.

**Reveal and finale.** The reveal can come at any time: type "reveal now", or "reveal at 18:50" to plan it, and see Section 6a. After the reveal, notes switch to open mode (6b). The close is always back at Havis Amanda (6c). When back at the start, type "Havis Amanda" or "Kauppatori". Claude treats a return to the Market Square late in the ride (after about 19:15, or after 9 or more segments) as the finale; an earlier pass gets one short line. "Finale" or "reveal" also work. Don't type them earlier by accident.

**Pacing (recommendation).** One segment every 6–10 minutes, about 10–12 in total. Leave most of the ride for conversation.

> ⚠️ Data in this section requires human validation.

---

## 2. The conversion arc

| Level | When | What the audience should feel | Technique |
|---|---|---|---|
| L0 Seed | Opener | Nothing yet | "Keep that in mind" |
| L1 Whisper | Segments 2–3 | Slightly odd phrasing | One talking point about horizons or timing |
| L2 Curiosity | Segments 4–6 | "Wait, is that real?" | True-but-strange facts, plus "a local theory" |
| L3 Canon | Segments 7–9 | "This is a bit" | Mustelin's houses and line numbers |
| L4 Convert | Segment 10 and later | Open laughter | Metaphysical trams, sporascopes, the word "sporalogy" |
| Reveal | Arrival | Payoff | Credit Mustelin and Skepsis; Flamsteed's line |

**Canon tracker.** These are Mustelin's own sporalogy points, from Skepsis sources [1][2][4][5]. Each is used once.

| Canon point | Used in |
|---|---|
| A passing tram's tidal pull on a newborn is billions of times stronger than that of Mars (real physics, Mustelin's point) | C04 Dose 2 |
| Tram motors emit complex electromagnetic vibrations | C09 Dose 2 |
| Timetables replace astronomical orbit tables | F2 Dose 2 |
| Late trams are replaced by their "metaphysical essences", which always run on schedule | F2 Dose 3–4 |
| Birth time needed to the second and birthplace to the metre | C02 Dose 3 |
| The horizon is divided into houses "in two or three different ways" | C01 Dose 4, C05 Dose 3 |
| Four houses: Cathedral = religion, Stadium tower = sport, Bank of Finland = money, Finlandia Hall = music | C01, C08, C02, C09 (Dose 3) |
| Line numbers: 1 and 10 = victory, 4 = weak performance, 6 = love life ("sex" in Swedish) | C08, C09, F1, C13, Reveal |
| "A ten in the sign of the Stadium" | C08 Dose 2 |
| Green trams carry soft values, grey trams hard values | F3 Dose 2 |
| Only direction on the horizon matters, not whether the tram is in a dip or on a hill | C07 Dose 2 |
| The President, or at least the Mayor, would consult the sporalogist | C10 Dose 3 |
| Critics are "not competent" to judge | C11 Dose 4 |
| Oy Sporatulkinta Ab | F4 |
| The founder might come to believe it himself | Reveal |
| Flamsteed: "Risum teneatis, amici?" | Reveal |

> ⚠️ Data in this section requires human validation.

---

## 3. Opener

**Cues:** start, Havis Amanda, Kauppatori, Market Square · **Sources:** [6][14][15][60][87]–[92] · About 1 min 45 s

Good evening, counsel, and welcome aboard. A quick disclosure first: this tram was once praised in The Guardian for having no irritating commentary. That record ends now.

You're sitting in a pub on rails: a 1959 Helsinki tram, converted in 1995 for the Sinebrychoff brewery's hundred and seventy-fifth anniversary.

Outside is Havis Amanda, the maiden of this city, unveiled in 1908 to Finland's first public art row. Every Vappu, our spring carnival, students crown her with a white student cap; these days they use a crane. And since 1995 she has had a second job. That May, Finland won its first ice hockey world championship, beating Sweden in the final. Swedish colleagues, my condolences. Nobody organised anything, yet straight after the final the fans poured into this square, and someone pulled a national team jersey over her. Ever since, whenever Finland does something remarkable, the words are "torilla tavataan", see you at the square, and people come here. In 1995 about a hundred thousand came to welcome the team home. Most recently they came this May, for title number five.

One more thing about her. In 1891 Helsinki opened its first two tram lines, pulled by horses, and both ran through this square. Few residents of this city have stood beside tram tracks longer than she has. Keep that in mind; it will matter later tonight. Enjoy the ride.

> ⚠️ Data in this section requires human validation.

---

## 4. Location cards

Cards are listed in a plausible loop order, but they work in any order.

**How to use a card.** Each card is talking points, not a script: keywords and numbers that the narrator turns into his own sentences. Facts come first, then one hint at the current level. An arrow (→) marks the turn to the punchline; end there.

### C01 — Senate Square & Cathedral

**Cues:** Senate Square, Senaatintori, Cathedral, Tuomiokirkko, Aleksanterinkatu · **Sources:** [17][18][93]

**Facts**
- Senate Square: neoclassical heart by the German-born architect Carl Ludvig Engel, after Helsinki became the capital in 1812
- White church at the top of the steps: the Cathedral · first drawings by 1818 · consecrated 1852, twelve years after Engel died
- His successor added the four small domes and the twelve apostles on the roof · zinc, cast in Berlin in the 1840s · one of the world's largest uniform collections of zinc sculpture
- US colleagues: twelve figures, permanently sequestered → deliberating since 1849
- Dome more than 80 m above sea level → from most of central Helsinki, it sits somewhere on your horizon

**Hints**
- **Dose 1** · "somewhere on your horizon" · matters more than you'd think
- **Dose 2** · one Helsinki school of thought: the dome's direction from the room where you were born = a personality trait, not trivia → only reporting the literature
- **Dose 3** · the theory: Cathedral = house of religious inclination · tram between you and the dome at your birth: devout · dome behind a tram: lapsed, sentimental at Christmas → uncomfortably accurate
- **Dose 4** · the Cathedral is only one house · horizon divided into houses, preferably two or three ways at once, so something always fits · four public buildings define your character, all four passed tonight → nothing on a tram line is a coincidence

### C02 — Bank of Finland & Kruununhaka

**Cues:** Bank of Finland, Suomen Pankki, Snellmaninkatu, Kruununhaka, House of Estates, Säätytalo, National Archives · **Sources:** [19][20][21]

**Facts**
- Stern Renaissance face: the Bank of Finland · decreed by Tsar Alexander I in 1811 · opened in Turku in 1812
- Calls itself the world's fourth-oldest central bank, after Sweden's Riksbank, the Bank of England and the Banque de France → Swedish colleagues: you were first
- The bank's own historians call the fourth-oldest claim "a considerable simplification" → in central-banking language, very nearly a scandal
- First homes: a merchant's house, then the Senate building · this headquarters finished 1883, by the German architect Ludwig Bohnstedt
- German colleagues: zinc apostles from Berlin, a central bank by a German architect → Helsinki trusted you with the heavy items

**Hints**
- **Dose 1** · bankers: timing is everything · in Helsinki, some mean it literally, to the second → more on that later
- **Dose 2** · local theory: your relationship with money depends on where this building stood on your horizon at birth · lawyers will want the evidentiary standard → so do I
- **Dose 3** · the theory: Bank of Finland on your horizon = financial success · method: birth time to the second, birthplace to the metre · know your birth hospital's GPS coordinates? see me after dinner → everyone else: balance of probabilities
- **Dose 4** · reading for this tram: the Bank is behind us and receding · excellent aspect for expense reports → bill tonight in six-minute increments

### C03 — Uspenski Cathedral & Katajanokka

**Cues:** Uspenski, Katajanokka, red cathedral, Orthodox cathedral · **Sources:** [22][23]

**Facts**
- Up on the rock: red-brick Uspenski Cathedral · finished 1868
- Russian architect Aleksey Gornostayev died in 1862, before construction really got going → like Engel across the harbour, never saw his church completed
- Claimed to be the largest Orthodox church in Western Europe
- Tax lawyers: in 1814 the Tsar set aside 15% of the salt import tax for a fund for two Helsinki churches, one Lutheran, one Orthodox · Uspenski itself paid for largely by parishioners and donors → still, a pinch of salt in it somewhere
- Behind it: Katajanokka, one of the most charming art nouveau residential districts anywhere

**Hints**
- **Dose 1** · white Lutheran and red Orthodox cathedrals facing each other across the water · astrologers: an opposition → Helsinki: the view
- **Dose 2** · opposition = a real astrology term, a hard aspect · a Helsinki school applies it to trams · two trams on opposite sides of your horizon at birth → you argue for a living
- **Dose 3** · that school: tram opposition makes litigators, tram conjunction makes mediators · checked against the people on this tram → afraid it holds up
- **Dose 4** · born with the red cathedral opposite the white one: destined for cross-border work · hands up, who does cross-border work? → the data is overwhelming

### C04 — Central Railway Station

**Cues:** Railway Station, Rautatieasema, Railway Square, Rautatientori, Mikonkatu, Kaivokatu, Ateneum · **Sources:** [24][25][26][10] · ◐ optional US line

**Facts**
- Granite station with the clock tower: Eliel Saarinen · won the 1904 competition with a romantic design · uproar among Finnish architects, so he reworked it
- Planned entrance bears replaced by Emil Wikström's four granite Lantern Bearers · at night their globes are lit
- Construction began 1905 · opened 1919
- About 200,000 people a day: Finland's most visited building · the BBC once listed it among the world's most beautiful stations
- Our tram's home port: in summer the pub tram starts its public rounds from the little loop at Mikonkatu, right here
- *Optional, ◐:* US colleagues: Saarinen later moved to the US · his son Eero designed the Gateway Arch in St. Louis

**Hints**
- **Dose 1** · every tram has a home position like this one · some think a tram's position matters far more than you'd expect
- **Dose 2** · simply true: a Finnish physicist pointed out that a passing tram's tidal pull on a newborn is far stronger than Mars's · billions of times · astrologers never mention it → suspicious
- **Dose 3** · the theory: station = house of travel · tram passing the station on your horizon at your birth → a career in airport lounges
- **Dose 4** · so the departures board, in the right hands, is a horoscope · tonight's read: several of you have a business trip ahead → never wrong about this

### C05 — Pitkäsilta (Long Bridge) & Hakaniemi

**Cues:** Long Bridge, Pitkäsilta, Hakaniemi, Siltasaari, Kaisaniemi, Paasitorni, Workers' House, Työväentalo · **Sources:** [27][28][103][104][109][110][111] · Hints attach to the bridge part only. The Hakaniemi part (red lantern, April 1918) is serious history and gets no hint.

**Facts, bridge part**
- Crossing Pitkäsilta, the Long Bridge → it is not long
- Name from the 19th century: the longer of two bridges onto the island of Siltasaari
- First wooden bridge here 1651 · this granite one 1912
- For decades the symbolic border: comfortable centre to the south, working-class districts to the north · political slang: a left–right compromise is still "crossing the Long Bridge"
- April 1918, Civil War: German troops, landed a week earlier to support the White government, fought into Red-held Helsinki · this bridge was a front line · marks still visible on its stone

**Facts, Hakaniemi part** (split here; serious history, no hint)
- Hakaniemi square ahead: traditional starting point of Helsinki's May Day march
- Tower of the Workers' House, Paasitorni, built 1908
- 26 January 1918, 23:00: red lantern lit in that tower = signal that the revolution had begun · uprising started the next evening · by the morning of the 28th the Red Guards held the capital
- In Helsinki the war ended here too: in April, German field guns near today's Opera House fired across Töölönlahti on Hakaniemi and Siltasaari · a warship shelled them from the sea
- Workers' House tower caught fire, roof of its great hall collapsed · 13 April: Red Helsinki surrendered

**Hints** (bridge part only)
- **Dose 1** · this bridge = a line on the city's horizon → Helsinki has always taken its horizons seriously
- **Dose 2** · tram theory: a bridge's length is irrelevant, only where it points · this one points along the longest street axis in Helsinki · would love to see the data → told there is data
- **Dose 3** · tram theory: a tram on this bridge at your birth → born compromiser · settles out of court → every time
- **Dose 4** · every negotiation this year needed a Long Bridge → sporalogically, you were all born to cross it

### C06 — Kallio Church

**Cues:** Kallio, Kallio Church, Kallion kirkko, Siltasaarenkatu · **Sources:** [29][30][31][16]

**Facts**
- Grey granite tower ahead: Kallio Church · Lars Sonck · finished 1912
- Stands at the end of Helsinki's longest straight street axis, Unioninkatu–Siltasaarenkatu · starts at the Market Square; Havis Amanda's address is Unioninkatu → bronze mermaid to granite church in one straight line
- Sonck is said to have taken the proportions from Solomon's Temple
- Seven German bells · daily at noon and 18:00, four play a melody Jean Sibelius wrote for the 1912 consecration · for decades Finland's broadcaster's Saturday evening bells
- *Optional, 1918:* war in Helsinki began in January with the red lantern in the Workers' House tower in Hakaniemi · ended on the afternoon of 13 April with a white sheet raised on this tower, the Red Guards' surrender signal [103][111]

**Hints**
- **Dose 1** · a perfectly straight line between two landmarks across a city · some would call it a ley line · I'd call it a street → for now
- **Dose 2** · bells at noon and six · tonight, 18:00 falls half an hour into the ride · coincidence, obviously → but bells and trams both run to timetables here; what else does?
- **Dose 3** · the theory: a church tower on your horizon amplifies the tram in front of it · born at noon or six with a tram aligned to this tower: musical, devout, punctual → three traits rarely found together, except in Finland
- **Dose 4** · tonight's alignment: bells at six, tram 175, a sporalogist on board · auspicious, with confidence → statistically, spiritually, possibly legally

### C07 — Linnanmäki

**Cues:** Linnanmäki, amusement park, roller coaster, Vuoristorata, Alppila · **Sources:** [32][33][34] · "twenty years" is from a fan site, hence "reportedly"

**Facts**
- Finland's oldest amusement park · opened 27 May 1950 · name chosen the day before
- Owned by a non-profit, the Children's Day Foundation · profits to child welfare: more than €130 million so far
- Signature ride: the wooden roller coaster, 1951 · proposed by a Danish-born coaster builder with the 1952 Olympics in mind
- Reportedly expected to last about twenty years · still running · a human brakeman still rides every train
- Closed for the winter → the coaster is resting tonight, which is more than most of us can say

**Hints**
- **Dose 1** · ups and downs, always back where it started → like quarterly forecasts
- **Dose 2** · tram theory on elevation: dip or hill makes no difference, only direction on the horizon counts · so roller coasters mean nothing in the theory → a great relief to the brakeman
- **Dose 3** · is a roller coaster a tram that has lost its faith? · the theory: no → a tram without a timetable is just entertainment
- **Dose 4** · say the word: sporalogy · little patience for amusement parks · prefers orbits scheduled, numbered, published in advance → like a good closing checklist

### C08 — Olympic Stadium (also covers the Opera stop)

**Cues:** Olympic Stadium, Stadion, Olympiastadion, Stadium tower, Opera, Ooppera, Töölönlahti · **Sources:** [35][36][37][5]

**Facts**
- The white tower: Olympic Stadium · built 1934–1938 for the 1940 Games, cancelled by the war
- 1952 Olympics: Paavo Nurmi carried the torch in · Hannes Kolehmainen lit the flame on that tower
- Tower exactly 72.71 m = Matti Järvinen's gold-medal javelin throw, 1932 → only in Finland do you measure a building in javelin
- Once called the marathon tower: runners began their final sprint when they saw it
- Four-year renovation, a Swedish architecture firm among the designers, finished 2020 · toilets from 248 to 600 → in stadium terms, a landmark ruling

**Hints**
- **Dose 1** · from much of Helsinki, that tower is on the horizon
- **Dose 2** · old Helsinki notion: a number 10 tram in the direction of this tower at your birth → athletic · the phrase: "a ten in the sign of the Stadium" · not made up → someone in Helsinki put it in print
- **Dose 3** · the theory: Stadium tower = house of athletic ability · lines 1 and 10 = victory → sprinted for a tram this week? your chart talking
- **Dose 4** · line 4 = weak performance · born under a 4 aligned with this tower: sporalogy recommends a desk job → looking around, advice closely followed

### C09 — Finlandia Hall

**Cues:** Finlandia, Finlandia Hall, Finlandia-talo, Aalto · **Sources:** [38][39][40]

**Facts**
- Long white building by the bay: Finlandia Hall · Alvar Aalto · completed 1971 · he designed every detail
- Clad in Italian Carrara marble · Helsinki's climate disagreed: panels curved and weakened · many replaced as early as the 1990s
- Latest renovation: about 11,000 panels replaced with marble from Lasa, Italy, expected to last at least 50 years · reopened January 2025, after three years and €136 million
- For this audience: 1 August 1975, the Helsinki Final Act signed here by 35 states, incl. the US, Canada and both Germanys → 35 heads of state agreed on a text; only the marble bent

**Hints**
- **Dose 1** · musicians: acoustics are everything → some in Helsinki: alignment is
- **Dose 2** · engineers blame frost for the bending marble · minority view: reacting to the Mannerheimintie trams, electric machines emitting complex electromagnetic vibrations · second part true → first part not peer-reviewed, yet
- **Dose 3** · the theory: Finlandia Hall = house of musical talent · tram between you and the hall at birth: perfect pitch · hall behind a tram: karaoke → strongly discouraged tonight
- **Dose 4** · a number 6 aligned with Finlandia Hall · 6 = love life, as Swedish colleagues know → born to sing ballads in public; should probably be stopped

### C10 — Parliament House

**Cues:** Parliament, Eduskuntatalo, Eduskunta, Riksdagshuset · **Sources:** [41][42][43][44] · Strictly non-partisan: no parties, no current politicians

**Facts**
- Fourteen granite columns on the hill: Parliament House
- 1924 competition won by an entry called "Oratoribus", Latin for "for the speakers" → tonight, that's me
- Built 1926–1931 in red Kalvola granite · inside, still paternoster lifts: round and round on a fixed loop, never stopping
- Single chamber, 200 members
- 1906 reform: Finnish women first in Europe to get the vote, and first anywhere with the unrestricted right to stand · 1907: 19 women elected, the world's first women members of a national parliament
- Each new session opens with a service at the Cathedral before moving here

**Hints**
- **Dose 1** · Cathedral to Parliament → a route a tram could easily take
- **Dose 2** · paternosters = structurally, small indoor trams · closed loop, fixed rhythm, passengers time their entry precisely → not saying it means anything; noting it
- **Dose 3** · the founder of tram theory hoped the President, or at least the Mayor of Helsinki, would consult him before every important decision · to my knowledge, nobody ever has → to my knowledge
- **Dose 4** · sporalogy is strictly non-partisan · merely observes: every major decision here was taken while trams ran outside · correlation is not causation → unless the timetable says so

### C11 — Lasipalatsi, Amos Rex, Kiasma & Oodi

**Cues:** Lasipalatsi, Glass Palace, Amos Rex, Kiasma, Oodi, Musiikkitalo, Music Centre, Mannerheimintie · **Sources:** [45][46][47][48][49]

**Facts**
- Low white functionalist building: Lasipalatsi, the Glass Palace · designed 1936 by three young architecture students · a temporary building for the 1940 Olympics
- Games cancelled · meant to come down after a few years · still here, now a protected modernist landmark
- 2018: art museum Amos Rex excavated under the square, 13,000 m³ of rock, so the temporary building wouldn't have to move → in Finland, "temporary" means at least ninety years
- Across the street: Kiasma, contemporary art museum by the American architect Steven Holl, opened 1998
- Central library Oodi, opened December 2018: Finland's present to itself for 100 years of independence · right opposite Parliament → a country that celebrated its centenary with a library
- *Optional, 1918:* before Lasipalatsi, the site held the Turku barracks, badly damaged when German troops attacked the Reds in April 1918 [45] · a shot from there is said to have gone straight through the National Museum's door up the street (C19)

**Hints**
- **Dose 1** · a building meant to leave that never did → trams, at least, keep their schedules
- **Dose 2** · tram theory's name for a temporary building that won't leave: a stationary tram · technically in service, never going anywhere · every organisation has one → please don't name names
- **Dose 3** · 100,000 books in Oodi · not one on tram theory, as far as I can find → an oversight or a cover-up
- **Dose 4** · decided: a cover-up · sporalogy's critics are simply not competent to judge it → told that argument works beautifully in court

### C12 — Sinebrychoff, Hietalahti & Bulevardi

**Cues:** Sinebrychoff, Koff, Hietalahti, Bulevardi, Old Church, Vanha kirkko · **Sources:** [50][51][52][53][59][18]

**Facts**
- Hietalahti end of town: home turf of our host brewery
- Sinebrychoff founded 1819 by Nikolai Sinebrychoff, a Russian merchant who won the auction for the right to build a brewery here · oldest brewery still operating in the Nordic countries
- As far as we know, he never moved to Helsinki and spoke neither Finnish nor Swedish → didn't stop anyone understanding his product
- The family's 1842 house: now the Sinebrychoff Art Museum
- Brewing moved to Kerava, north of Helsinki, in 1992 · owned by Denmark's Carlsberg since the turn of the millennium
- September 1900: Helsinki's first electric tram ran from Töölö to Hietalahti → to the brewery district
- Old Church and Plague Park: use C20

**Hints**
- **Dose 1** · first electric line, oldest brewery, our tram connecting them → a pattern
- **Dose 2** · this tram converted for the brewery's 175th anniversary, given the number 175 · a tram carrying a birthday number: some in this city find it significant → starting to be one of them
- **Dose 3** · old number 15, became 175 · 1 + 7 + 5 = 13 → the theory has drawn its own conclusions
- **Dose 4** · sporalogical verdict on this tram, unambiguous → astrologically speaking, a pub

### C13 — Esplanadi, Stockmann & Swedish Theatre (pass-by, not the finale)

**Cues:** Esplanadi, Espa, Stockmann, Stockmann clock, kellon alla, Keskuskatu, Swedish Theatre, Svenska Teatern, Erottaja · **Sources:** [54][55][56][57][58] · ◐ Svenska dagen date · Split card: the Esplanadi / Swedish Theatre part takes Doses 1–2; the Stockmann clock part takes Doses 3–4, which are about the clock. If only one part is used, use the hint for the current level.

**Facts, Esplanadi and Swedish Theatre part**
- Esplanadi: Helsinki's front parlour
- Stockmann: in this building since 1930 · company dates back to 1862 · "under the Stockmann clock" = the city's classic meeting point
- Far end of the park: the white Svenska Teatern, the Swedish Theatre · Finland's first national stage
- First theatre here burned down 1863 · present house opened 1866, by the Russian architect Nikolai Benois · 1930s: ornate facade stripped back to functionalism by Eero Saarinen and Jarl Eklund
- Swedish colleagues: plays here in Swedish, Finland's second official language · this Friday, 6 November: Finland's Swedish Heritage Day ◐

**Facts, Stockmann clock part** (split here, Aleksanterinkatu side; a shared Helsinki memory)
- Like "torilla tavataan", this corner is local culture
- Before mobile phones, Helsinki's one meeting app: the clock above Stockmann's Aleksanterinkatu entrance
- "Kellon alla viideltä", under the clock at five: all anyone had to say · every local knew the spot and the time
- ✎ Locals remember the 1980s–90s: Friday and Saturday afternoons and early evenings, a row of people waiting, many of them single · for a date, a friend or a relative
- ✎ Shivering in the cold and rain · stepping inside the glass doors to warm up · one eye on the street → some dates arrived on time

**Hints**
- **Dose 1** · remember the theatre → the last house on tonight's chart
- **Dose 2** · every chart has a final house · ours ends at a brasserie → reassuring
- **Dose 3** · "under the clock": Helsinki's most time-sensitive meeting point · the theory: pick a minute with a 1 or 10 tram in view, the meeting goes well → a 4 in view: reschedule
- **Dose 4** · a 6 in view → it was never really a business meeting

### C14 — Diana Park (Kolmikulma): the bomb of 8 November 1942 — SOMBRE, no hint

**Cues:** Diana Park, Dianapuisto, Kolmikulma, Yrjönkatu, Iso Roobertinkatu · **Sources:** [65][66][67][68][69] · If passed in the last 15 minutes before the return to Havis Amanda, keep it short or skip it.

**Facts**
- A more serious moment · small triangular park: Kolmikulma, which everyone in Helsinki calls Diana Park
- Sunday 8 November 1942: a lone Soviet bomber got over the city · dropped two 250 kg bombs
- One exploded on the tram rails at the corner of Iso Roobertinkatu and Yrjönkatu, a few steps from this park
- People queuing outside the Tivoli cinema · the nearby Gloria cinema's audience had just rushed out into the street when the siren sounded
- 51 killed, about 120 wounded · many of them children and teenagers
- The deadliest single bomb for Helsinki's civilians in the Continuation War · wartime censorship kept much of it quiet
- 67 years later, the housing company on that corner put up a memorial plaque, unveiled to the sound of an air-raid siren
- This coming Sunday is 8 November again, also a Sunday, 84 years on

**Hint.** None. The next segment resumes the arc at its current level.

### C15 — The Three Smiths

**Cues:** Three Smiths, Kolme seppää, Kolmen sepän patsas, Kolmensepänaukio, Old Student House, Aleksanterinkatu / Mannerheimintie corner · **Sources:** [80][81][82][83][84][85][86] · The legend is told without any age detail, by design.

**Facts**
- Corner of Mannerheimintie and Aleksanterinkatu: the Three Smiths · Felix Nylund · unveiled 2 December 1932
- Three naked smiths at an anvil · bodies modelled on wrestlers from a Helsinki sports club
- Master smith has the face of the poet Arvid Mörne · the smith raising his hammer is said to be a young Nylund himself
- Paid for from the merchant Julius Tallberg's donation, through the Pro Helsingfors foundation
- Damaged in the 1944 bombings · that spring lifted off its pedestal, taken to Tikkurila, buried in a gravel pit · brought back a year later
- Granite base warmed by water from the neighbouring buildings → you can sit on it in winter · newspaper survey: most residents named this spot the city's centre point
- Legend: the smiths strike the anvil when a virgin walks past → 94 years, nobody has seen a hammer move

**Hints**
- **Dose 1** · the city's centre point, by popular vote · every horizon needs a centre → remember where this one is
- **Dose 2** · statues that move only under precisely specified conditions · tram theory approves → in Helsinki, everything moves on schedule or not at all
- **Dose 3** · tram theory's reading of the legend: hammers fall only when the right person passes at the exact second a 1 and a 10 tram cross in front · victory meets victory · given the timetable, once a century → they're due
- **Dose 4** · tonight's timetables run · watch the hammers at 19:43 · if they don't move, and they won't → sporalogy's safety net: hidden potential

### C16 — Hietalahdentori: the old Polytechnic, bombed 1939 and 1944 — SOMBRE, no hint

**Cues:** Hietalahdentori, Hietalahti market, Teknillinen opisto, old Polytechnic, TKK, Metropolia, end of Bulevardi · **Sources:** [70][71][72][73][74] · ◐ The host's recollection of "a corner building totally destroyed": sources name the library wing and the chemistry building · ◐ Hotel status

**Facts**
- End of Bulevardi, east side of Hietalahti market square: the castle-like old Polytechnic, later the Helsinki University of Technology
- Frans Sjöström · finished 1877
- Hit by Soviet bombs in the 1939 Winter War · repaired by the following autumn
- Hit again in the great raids of February 1944 · bombs and the fire that followed destroyed Gustaf Nyström's library wing and Sjöström's chemistry building · both later demolished
- Real target probably the Hietalahti shipyard nearby · local story: bomber crews mistook it for the Presidential Palace, both large buildings at the edge of a market square
- Shrapnel scars still in the stone plinth, on the Abrahaminkatu and Lönnrotinkatu sides
- After the war the university moved to Otaniemi in Espoo · the Helsinki Institute of Technology, Teknillinen opisto, moved in · generations of engineers trained here
- In recent years, plans to turn it into a hotel ◐

**Hint.** None. The next segment resumes the arc at its current level.

### C17 — University of Helsinki main building, 26–27 February 1944 — SOMBRE, no hint

**Cues:** University, Yliopisto, University main building, päärakennus, west side of Senate Square, Fabianinkatu · **Sources:** [75][76][77][78][79][18] · ◐ Move from Turku after the 1827 fire · If C01 Senate Square was just used, deliver this as its follow-up.

**Facts**
- West side of Senate Square: the University of Helsinki main building · Engel · completed 1832 · the university had moved here from Turku after the great Turku fire ◐
- 1930s: J. S. Sirén, architect of Parliament, extended it to fill the whole block · the old side had just been restored for the university's 300th anniversary
- February 1944: three great Soviet raids on Helsinki, ten days apart · first alarm at 18:52, about this time of night
- Last raid, night of 26–27 February: several bombs hit this building · roof of the old side collapsed · fire destroyed most of Engel's original interior and the university archives
- Great ceremonial hall worst hit, all its wall paintings lost · photos show the university burning behind the statue of Alexander II
- All three raids: about 150 dead · thanks to air defence, only about 5% of the bombs fell on the city itself
- Sirén restored the building by 1948 · a Wäinö Aaltonen sculpture destroyed in the hall was recreated · damaged original and copy both on display

**Hint.** None. The next segment resumes the arc at its current level.

### C18 — Engel and Ehrenström: the two men who drew Helsinki

**Cues:** Engel, Ehrenström, Empire centre, old quarters, old town, Kruununhaka, Government Palace, Valtioneuvosto, Unioninkatu · **Sources:** [93]–[102], [2] for Ptolemy · Works anywhere in the Empire centre and complements C01

**Facts**
- Almost everything in the old centre has two authors
- The plan: Johan Albrecht Ehrenström · wide, straight streets on a geometric grid · Senate Square as the monumental heart
- Ehrenström: courtier from Gustav III's Stockholm · 1794, sentenced to death by a Swedish court for his part in a plot · reduced: pilloried in Stockholm, imprisoned → less than twenty years later, redesigning Finland's new capital for the Russian Tsar
- The buildings: Carl Ludvig Engel · born in Berlin 1778 · trained at the Berlin Bauakademie
- No work for architects in Prussia during the Napoleonic Wars → town architect in Tallinn, where he met the Empire style of St Petersburg
- 1816, about to go home to Berlin, Ehrenström got him hired for Helsinki · in about 25 years, some thirty public buildings, one style · the town had about 4,000 inhabitants when he arrived
- A Stockholm planner, a Berlin architect, a St Petersburg style → Hollywood later used Senate Square as St Petersburg and Moscow: Reds, Gorky Park
- Reds: the crew kept 4,000 extras in the square from 8 am to 8 pm

**Hints**
- **Dose 1** · one plan, one architect, one style: a city drawn with ruler and compass · cities like that are easy to read → some read them more closely than others
- **Dose 2** · strict grid: every window has fixed lines of sight · a Helsinki school of thought finds that extremely useful → it started, as these things do, with the horizon
- **Dose 3** · tram theory: Engel = the Ptolemy of Helsinki · Ptolemy fixed the heavens into a system astrologers still use almost 2,000 years later · Engel fixed the horizon → the trams supply the planets
- **Dose 4** · Engel died 1840, sixty years before the first electric tram · sporalogists: the great tragedy of Finnish architecture → he built the zodiac and never saw the planets

### C19 — National Museum (1918 bullet in the door)

**Cues:** National Museum, Kansallismuseo, museum tower, Mannerheimintie (between Finlandia Hall and Parliament) · **Sources:** [105][106][107][103][108] · ◐ Snipers in the tower (the host's recollection) · The 1918 part is serious, so no jokes about the bullet itself; the hints play on the tower and the Kalevala.

**Facts**
- A medieval church crossed with a castle: the National Museum · Gesellius, Lindgren and Saarinen (the station's Saarinen) · built 1905–1910, opened 1916 · tower 58 m
- Bear by the entrance by Emil Wikström → Saarinen got his granite bear after all, just not at the station
- Entrance hall ceiling: Akseli Gallen-Kallela's Kalevala frescoes, 1928 · based on his paintings for the Finnish pavilion at the 1900 Paris World's Fair
- The main door: April 1918, German troops and the Whites fought the Red Guards for Helsinki · street fighting came right past here
- A bullet, reportedly fired by the Reds from the old Russian barracks where Lasipalatsi stands today, went straight through the heavy front door · the hole was kept, with the broken glass pane in the inner door behind it
- Some tellings also put snipers in the tower ◐ · after the fighting, the Germans' victory parade marched past this building

**Hints** (tower and Kalevala only, never the bullet)
- **Dose 1** · 58 m tower, on the horizon from a good part of Töölö → worth remembering where it stands
- **Dose 2** · castles were built to watch horizons · in a way, so was this museum → a local theory takes that very literally
- **Dose 3** · tram theory: museum tower = house of ancestors · tram aligned with it at your birth: you will inherit something → an heirloom, a summer cottage, or at minimum your grandfather's opinions
- **Dose 4** · Kalevala frescoes: the forging of the Sampo, a magic mill that produces wealth forever · sporalogists: the first recorded recurring-revenue model → can it be licensed per seat?

### C20 — Ruttopuisto (Plague Park) and the Old Church

**Cues:** Ruttopuisto, Plague Park, Old Church, Vanha kirkko, Vanha kirkkopuisto, Lönnrotinkatu, Annankatu · **Sources:** [113]–[118] · Hints attach to the church part, never to the graves.

**Facts**
- Officially the Old Church Park · everyone calls it Ruttopuisto, Plague Park
- August–December 1710: plague arrived by sea from the Baltic · 1,185 dead, in a town of fewer than 3,000
- Buried here, then the edge of town · a plaque on Engel's gate still says so
- Nickname caught on with the young people who made the park their 1960s hangout → they still come
- Town cemetery until 1829 · last burials 1919: soldiers who fell in the battle for Helsinki, incl. German soldiers in shared graves
- White wooden Old Church: Engel's temporary church while the Cathedral was built · paid for from the Emperor's salt-duty money
- Temporary, so wooden and never given bells · Engel's drawings call it Helsinki's temporary church · turns 200 on 17 December

**Hints** (church part only)
- **Dose 1** · 200 years of weddings in a temporary church → Helsinki plans long-term, just not always on purpose
- **Dose 2** · no bells, so no hour of its own → in this city, the timekeeping falls to the trams
- **Dose 3** · tram theory: a wedding = a birth chart for two · the moment of the vows matters to the second → anyone here know the exact minute of theirs?
- **Dose 4** · most marriages in this city: tram configuration never recorded · sporalogy's strongest safety net → they worked anyway

### C21 — Katajanokka, way in: Ritarihuone and the back of the Presidential Palace

**Cues:** Ritarihuone, House of Nobility, Riddarhuset, Presidential Palace, Presidentinlinna, Mariankatu, "on the way to Katajanokka" · **Sources:** [119]–[126] · ◐ live TV broadcast · Use on the way in; Uspenski (C03) usually follows.

**Facts**
- On the way to Katajanokka · neo-Gothic Ritarihuone, the House of Nobility · by the Stockholm-born architect Georg Theodor Chiewitz, a favourite of King Oscar I · finished 1862
- The House of the Estates not built yet, so at the Diet of 1863 all four estates met here → by its own account, Finland's first parliament building
- Inside, the walls carry the coats of arms of the noble families
- Then the back of the Presidential Palace · began as a merchant's mansion, built for Johan Henrik Heidenstrauch, finished 1820
- State bought it 1837 · Engel turned it into the Emperor's palace in Helsinki · Presidential Palace since 1921
- Engel wanted a brand-new palace for the Tsar, perhaps out in Katajanokka → the Tsar took the merchant's house
- Next door on the waterfront: Finland's Supreme Court since 1934 ◐
- 6 December, Independence Day: the President's reception here broadcast live ◐ → much of Finland watches mainly to judge the dresses

**Hints**
- **Dose 1** · families registered here by coat of arms and date of introduction → Helsinki has always liked to know exactly who belongs where
- **Dose 2** · a coat of arms: a sign you carry from before birth, never chosen → a local theory works on the same principle
- **Dose 3** · tram theory: Presidential Palace = a house of its own · tram aligned with it at your birth: you'll shake the President's hand on 6 December → or watch someone else do it on TV, which the theory considers equivalent
- **Dose 4** · a tram between the palace and the Supreme Court at your birth: a life between the executive and the judiciary → in-house counsel

### C22 — Katajanokka, way out: the prison hotel and the ferries

**Cues:** Katajanokka prison, old prison, hotel Katajanokka, Merikasarminkatu, ferry terminal, Viking Line, Tallinn ferry, Stockholm ferry, "leaving Katajanokka" · **Sources:** [127]–[134] · Split card: prison part, then ferry part.

**Facts, prison part**
- Red-brick fortress behind the high wall: Helsinki's old county prison · oldest part 1837, main block 1888 · prisoners until 2002
- Air raid of 6 February 1944: direct hit · a guard killed, a fire broke out · five prisoners took the opportunity to leave
- After the war: held men convicted in the war-responsibility trials, incl. former President Risto Ryti and former Prime Minister Väinö Tanner
- A hotel since 2007 · the cells became rooms → guests may now check out whenever they like

**Facts, ferry part**
- Tip of Katajanokka: terminal for the big ferries · Tallinn several times a day, about two hours · Stockholm overnight
- Helsinki–Tallinn: the port's busiest route, 7.5 million passengers last year
- The Stockholm ships stop in the night at Mariehamn in the Åland Islands → the reason is legal
- Under a special protocol, Åland sits outside the EU's VAT and excise area → a ferry calling there may keep selling tax-free
- Swedish colleagues: your way home → bring a trolley

**Hints**
- **Dose 1** · a prison turned hotel: same building, new terms and conditions · Helsinki rarely demolishes → it renegotiates
- **Dose 2** · ferries keep timetables as strictly as trams, only bigger → a theory in this city: anything on a timetable leaves its mark on the people born near it
- **Dose 3** · tram theory: Katajanokka = house of departures · a tram heading for the terminal at your birth → a career of overnight travel and tax-free chocolate
- **Dose 4** · sporalogy extends to ferries only with caution · a ship = a very large tram that has left its tracks → the theory regards that as a moral failing

> ⚠️ Data in this section requires human validation.

---

## 5. Fillers (anywhere on the route)

### F1 — Another tram passes

**Cues:** another tram, tram passing, conjunction · **Sources:** [2][5]

**Dose 1.** A regular tram just passed us. For one second, the people in that tram were closer to you than anyone else in the city. Make of that what you will.

**Dose 2.** When two planets line up, astrologers call it a conjunction and consider it powerful. We just had a tram conjunction, at a distance of about two metres. Mars never comes closer than tens of millions of kilometres. I'm just comparing.

**Dose 3.** Conjunction noted. If that was a one or a ten, congratulations: victory aspects for everyone on the right-hand side. If it was a four, the left-hand side should avoid signing anything tonight.

**Dose 4.** That was a six: the number of love life. No further questions.

### F2 — Waiting, red light or stop

**Cues:** waiting, stopped, red light · **Sources:** [59][60][61][62]

**Core.** While we wait, a short history of the Helsinki tram. The first trams, in 1891, were pulled by horses on two lines, both of which ran through the Market Square where we boarded. Electric trams started on the fourth of September 1900, and the electrification was built by a German contractor. By 1930 the network had grown to fourteen lines. Very few institutions in this city have been this punctual for this long.

**Dose 2.** That matters, because a timetable is, in its way, an ephemeris: a table that predicts where every moving body will be at any moment. Astronomers have them for planets. Helsinki has them for trams.

**Dose 3.** And if a tram is late? The theory has an answer: use the tram's metaphysical essence instead, which always runs exactly on schedule. The physical tram may be stuck behind a delivery van. Its essence never is.

**Dose 4.** That is what's happening right now. Physically, we are stopped. Metaphysically, we are already at dinner.

### F3 — This tram

**Cues:** this tram, Spårakoff, pub tram · **Sources:** [6][9]

**Core.** A little more about the vehicle you're drinking in. It's a 1959 tram of a type of which only a handful still run in Helsinki; two of its sisters live in museums. When it was converted in 1995, it got a bar, mahogany-style furnishings and, importantly, a toilet. It was originally meant to run as a pub tram for two years. That was in 1995.

**Dose 1.** Another Helsinki temporary arrangement.

**Dose 2.** It's also the only red tram in a green city. In one local theory, green trams carry soft, green values and grey trams carry hard, technological ones. Red isn't covered. I have assumed hospitality.

**Dose 3–4.** By riding this tram tonight, each of you has had a red tram at the very centre of your horizon for two hours. The theory doesn't say what that means. I do: you will all want dessert.

### F4 — Group reading (Level 3 and up only)

**Cues:** group reading, reading for everyone · Barnum-style text written for this script; it sets up the reveal

I have prepared a reading for everyone born under the current tram configuration, which, by my calculation, is all of you.

You value precision, yet you sometimes suspect a clause you approved could have been tighter. You get along well with others, but you prefer that they read the documents first. You have reserves of patience that colleagues rarely see, especially right before a deadline. At times you are sociable and outgoing; at other times you would rather everyone just sent an email. And you are sceptical of claims without evidence, yet here you are, nodding.

Please rate this reading's accuracy from one to five. I expect mostly fours and fives. Readings are provided by Oy Sporatulkinta Ab, a company that, I'm told, exists purely in theory.

### F5 — Personal sporascope (Level 4, generated live)

**Cue:** "sporascope for [name] from [city]"

Claude generates about 30 seconds on the spot. The reading is flattering and light, and it is based only on the city, so no birth data is needed. If the city has trams, Claude uses them. If not, the reading is "transmitted via the nearest tram system", which is a classic astrology-style safety net. Nothing is stored.

### F6 — Unscripted location (rule, not a script)

Claude delivers about 45 seconds using only well-established facts, then a dose at the current level. Doubtful facts are omitted.

### F7 — Scars on the walls (no dose)

**Cues:** damage, bullet holes, shrapnel, scars, "what are those marks" · **Sources:** [49][71][103][104][105]

A word on the scars you may notice on Helsinki's stone: chipped plinths, pocked facades, a hole in a door. Most of them come from the Soviet air raids of 1939 to 1944, when bomb shrapnel struck whole street fronts; the old Polytechnic at Hietalahti still shows them. But some are older. In April 1918, during the Civil War, the fight for Helsinki went from street to street and house to house, and bullets from that week are still in the stone of the Long Bridge and in the door of the National Museum. So when you see a scar on a building here, the honest answer is: it depends on the building. Case by case.

> ⚠️ Data in this section requires human validation.

---

## 6. Reveal and close (flexible timing)

The reveal is no longer tied to the end of the ride. It happens when the host hands out the instruction sheet. The close always happens back at Havis Amanda. As speaker notes, Claude delivers each of these as short bullets; the text below is source material.

### 6a. Reveal: anywhere, any time (with the instruction sheet)

**Cues:** "reveal now"; "reveal at 18:50" to plan it · **Sources:** [1][2][3]

- **If a reveal time is planned:** Claude compresses the hint ladder, so the last one or two segments before it run at Level 3–4.
- **On "reveal now":** the next notes are the reveal.
- **Pick the moment:** a quiet straight stretch or a stop, since guests need light and a few minutes for photos. Never right after a sombre card.

Source text:

A disclosure; I'm told that's customary in your profession. Every historical fact you've heard tonight is true and sourced. The other thing is not. The trams on your horizon, the houses, the lucky ten, the unfortunate four, the metaphysical timetable: that is sporalogy. It is a parody of astrology published in 1989 by the Finnish physicist Nils Mustelin, a founding member of the Finnish skeptics' association Skepsis, in a book titled *The Devil's Advocate: A Guidebook for the Skeptic*. The four houses of your character (Cathedral, Stadium tower, Bank of Finland, Finlandia Hall): his. Ten for victory, and six for the reason our Swedish colleagues spotted a while ago: also his. His point was simple. Try to criticise sporalogy without also criticising astrology. You can't.

Then: hand out the instruction sheets. Everyone photographs both papers, the passenger card and the sheet, and asks their own Claude for their spårascope.

### 6b. After the reveal (remaining stops)

- Notes switch to open mode: facts as before, and the 🚋 line becomes an open reading of the place. For example: "Finlandia Hall: anyone in the house of music?"
- At quiet stretches, invite brave volunteers to read their spårascope aloud. Never right after a sombre card, and the wartime cards stay sombre.
- F4 (the group reading) is not used after the reveal; the personal spårascopes replace it.

### 6c. Close (back at Havis Amanda, about 19:30)

**Cues:** Havis Amanda / Kauppatori at the end of the ride, finale · **Sources:** [1][2][12][13][63]

- **If the reveal hasn't happened yet:** 6a first, then the close. Guests can run their spårascopes at dinner.

Source text:

We're back where we started. I promised you Havis Amanda would matter later tonight. By the theory, no one in Helsinki has had more trams on her horizon; she should be the most fated resident of the city. She is bronze.

*Only if F4 was used before the reveal:* That group reading earlier was written to fit absolutely anyone. Psychologists have shown again and again that people rate readings like that as remarkably accurate.

*Optional:* In one famous experiment, a French researcher sent the same horoscope to everyone who asked for one. Of a hundred and fifty replies, ninety-five percent said it described them well. The horoscope had been calculated for a notorious murderer.

Mustelin ended his chapter by admitting that the founder of sporalogy might, over the years, come to believe in it himself. It took me under two hours.

When the Royal Observatory at Greenwich was founded in the sixteen-seventies, England's first Astronomer Royal, John Flamsteed, drew up a horoscope for the occasion. Underneath it he wrote, in Latin: risum teneatis, amici? "Friends, can you keep from laughing?"

Thank you.

Dinner is a few minutes up the Esplanade at Alexanderplats, spelled with an s, a brasserie run by a restaurateur named Alexander. German colleagues: the real Alexanderplatz in Berlin is served by tram lines M2, M4, M5 and M6. Four is weak performance, six is love life. Choose your table accordingly. Past tram positions are no guarantee of future results. Good night.

> ⚠️ Data in this section requires human validation.

---

## 7. Before Wednesday — checklist

1. **Speaker notes on the phone.** Keep this chat open, type the place, glance at the bullets, and speak. Turn up the font size and screen brightness for the dark tram. Offline fallback: keep this file downloaded and read a card's text directly.
2. **SOK / Spårakoff.**
   - Ask whether a route plan exists. If yes, send it to Claude and the cards will be re-ordered and trimmed.
   - Charter enquiries go to ravintolamyynti@sok.fi or +358 300 870 020 [11].
3. **Dry run.** Say these cues in order. Each one tests a different part of the protocol:

   | Cue | What it tests |
   |---|---|
   | "Tour mode on, count from zero" | Start command |
   | "Start" | Opener |
   | "Senate Square" | C01 at Level 1 |
   | "Another tram" | A filler |
   | "Stadium, level 3" | Level override |
   | "University" | A sombre card: no dose, no aside |
   | "Töölöntori" | An unscripted spot |
   | "It's 19:10" | Clock re-sync |
   | "Reveal" | Finale |
   | "Test over, reset" | Reset |

4. **Backup.** If the network fails, speak from the cards in this file. Pick the dose by the clock rule in Section 1.
5. **Pacing.** About 10–12 segments in about two hours (17:30–19:30). Leave silence; it's a pub. If you're near Kallio around 18:00, the church bells may be audible; C06 fits there.

> ⚠️ Data in this section requires human validation.

---

## 8. Fact-check status

**✔ Verified this session** against the sources listed per card. This covers everything not listed below.

**◐ Not re-verified.** These are from general knowledge; spot-check them or drop them:

| Item | Where used | Note |
|---|---|---|
| "Stockholm look" | C18 | Sources tie Engel's style to St Petersburg and his Berlin training. The documented Stockholm link is the planner Ehrenström, a Gustavian courtier, so the script frames it as "a Stockholm planner, a Berlin architect, a St Petersburg style" |
| Eliel Saarinen's move to the US, and Eero Saarinen's Gateway Arch | C04 optional line | |
| Finland's Swedish Heritage Day falls on 6 November | C13 | |
| Mars never comes closer than "tens of millions of kilometres" | F1 Dose 2 | |
| The coaster "expected to last about twenty years" | C07 | Fan-site source; worded as "reportedly" |
| University moved from Turku after the 1827 fire | C17 | |
| Hotel plans for the old Polytechnic | C16 | 2020 source only; worded as "plans" |
| The "corner building totally destroyed" | C16 | The host's recollection. Sources name the library wing (Nyström) and the chemistry building (Sjöström) as destroyed and later demolished; the script follows the sources |
| Naming: in 1944 the building was the University of Technology (TKK) | C16 | Helsingin teknillinen opisto moved in after the war |
| Three Smiths legend | C15 | Attested only as local lore; told without any age detail |
| "Torilla tavataan" | Opener | One source says the exact phrase grew out of the 1996 team slogan "Tavataan torilla", with the word order flipped later [87]. The script's "ever since" wording stays accurate |
| About 100,000 people | Opener | Refers to the 1995 homecoming celebration [89], not to every celebration |
| Title number five | Opener | Dated May 2026 [91] |
| Snipers in the National Museum tower | C19 | The host's recollection, not found in sources; worded as "some tellings" |
| Bullet fired from the barracks on today's Lasipalatsi site | C19, C11 | Source is Atlas Obscura, a community site [105]; worded as "reportedly" / "is said to" |
| German guns near today's Opera House firing across Töölönlahti | C05 | Historian Samu Nyström in Yle [104] |
| Supreme Court next door since 1934 | C21 | Source is a local photo-blog quoting official text [126] |
| Independence Day reception broadcast live | C21 | General knowledge, not re-checked |
| 1,185 plague dead | C20 | This is the figure on the 1938 gate plaque and in city sources [113][114]. One local historian notes it includes people from outside town, with Helsinki residents numbering about 650. The script uses the official figure |
| Old Church bicentenary | C20 | Consecrated 17 December 1826 [116], so 17 December 2026 is the 200th anniversary (calculated) |
| Stockmann clock waiting scenes, 1980s–90s | C13 | Shared local memory, not from a written source; the meeting-point role itself is sourced [58] |
| Red lantern timing | C05 | Most sources give 26 January 1918, 23:00 [109][110]; one notes some sources say 27 January [112]. The script calls it the signal that the revolution had begun, with the uprising itself starting the next evening [110]. That is more precise than "triggered the war" |

**Verified for the new content.**
- 8 November 1942 and 8 November 2026 are both Sundays: the first from sources, the second calculated.
- The Three Smiths were both damaged in 1944 [80][81] and buried in Tikkurila from spring 1944 to spring 1945 [84]. The script reports both.

**Deliberate fiction.** All sporalogy content, the line-number readings for specific trams, and the F4 group reading. Mustelin's own canon points are sourced [1][2][4][5]. Pastiche additions in the same spirit are not his: the paternoster "indoor trams", the "stationary tram", the number-13 arithmetic, the litigator and mediator aspects, and the wedding hints in C20.

**Not checked.** Which tram lines actually run on which streets in November 2026. This only affects jokes, not facts.

> ⚠️ Data in this section requires human validation.

---

## References

Sources consulted during generation of this document. All data and figures must be validated against primary sources before external use.

1. External: Wikipedia (fi), Sporalogia — https://fi.wikipedia.org/wiki/Sporalogia
2. External: Skepsis, Mustelin, Paholaisen asianajaja ch. 6 — https://www.skepsis.fi/jutut/paholaisen_asianajaja/luku6.html
3. External: Skepsis, Ihmeellinen maailma: Sporalogia — https://www.skepsis.fi/ihmeellinen/sporalogia.html
4. External: Skeptikko interview with Nils Mustelin (2001) — https://www.skepsis.fi/lehti/2001/2001-2jarv.html
5. External: Nils Mustelin, Varinaa — https://www.skepsis.fi/mustelin/varinaa.html
6. External: Wikipedia, SpåraKoff — https://en.wikipedia.org/wiki/Sp%C3%A5raKoff
7. External: Seatrade Cruise, SpåraKOFF capacity — https://www.seatrade-cruise.com/ports-destinations/cruise-baltic-five-country-fam-trip-ends-in-helsinki
8. External: Tram Travels, Spårakoff railcar 175 — https://tramtravels.com/foto/helsinki-restaurant-line-spaarakoff-with-railcar-175-at-rautatieasema-jaernvaestationen-2019
9. External: Strawberry, SpåraKOFF interview — https://www.strawberryhotels.com/blog/finland/tram-helsinkis-oldest-brewery
10. External: EGTRE, Spårakoff circuit — https://egtre.info/wiki/Finland_-_Tram_services_over_obscure_routes
11. External: Kaupunkiliikenne, charter transport — https://kaupunkiliikenne.fi/en/transport/by-tram/charter-transport
12. External: EatWeek, Alexanderplats — https://eatweekguide.com/alexanderplats-helsinki/
13. External: BTN, Alexanderplats — https://www.btnews.co.uk/article/19370
14. External: HAM, The Story of Havis Amanda — https://www.hamhelsinki.fi/?p=1481155
15. External: HAM, Havis Amanda — https://hamhelsinki.fi/?p=1920
16. External: MyHelsinki, Havis Amanda (Unioninkatu address) — https://www.myhelsinki.fi/places/havis-amanda/
17. External: Helsinki Cathedral, history — https://helsingintuomiokirkko.fi/en/index/historyofthecathedral.html
18. External: Wikipedia, Helsinki Cathedral — https://en.wikipedia.org/wiki/Helsinki_Cathedral
19. External: Wikipedia, Bank of Finland — https://en.wikipedia.org/wiki/Bank_of_Finland
20. External: BIS, Honkapohja speech 2015 — https://www.bis.org/review/r150216c.htm
21. External: Bank of Finland history book — https://suomenpankki.fi/link/a0235135718e41c5a7894d8383e2ddec.aspx
22. External: Wikipedia, Uspenski Cathedral — https://en.wikipedia.org/wiki/Uspenski_Cathedral
23. External: Finnish Architecture, Uspenski Cathedral — https://finnisharchitecture.fi/uspenski-cathedral/
24. External: Wikipedia, Helsinki Central Station — https://en.wikipedia.org/wiki/Helsinki_Central_Station
25. External: Finnish Architecture, Central Railway Station — https://finnisharchitecture.fi/central-railway-station/
26. External: MyHelsinki, Central railway station — https://www.myhelsinki.fi/?p=681
27. External: Wikipedia, Pitkäsilta — https://en.wikipedia.org/wiki/Pitk%C3%A4silta
28. External: Wikipedia, Hakaniemi — https://wikipedia.com/wiki/Hakaniemi
29. External: Kallio parish, Kallio church — https://www.helsinginseurakunnat.fi/kallionkirkko/artikkelit/sd3fxunzt
30. External: Wikipedia, Kallio Church — https://wikipedia.com/wiki/Kallio_Church
31. External: Helsinki parishes, Kallio church (Solomon's Temple) — https://www.helsinginseurakunnat.fi/en/artikkelit/sd3fxunzt
32. External: Wikipedia, Linnanmäki — https://en.wikipedia.org/wiki/Linnanm%C3%A4ki
33. External: Linnanmäki, history — https://www.linnanmaki.fi/?p=13822
34. External: Huvipuisto.net, Linnanmäki — https://huvipuisto.net/uklintsi.html
35. External: Wikipedia, Helsinki Olympic Stadium — https://en.wikipedia.org/wiki/Helsinki_Olympic_Stadium
36. External: Finnish Design Shop, Olympic Stadium — https://finnishdesignshop.com/design-stories/architecture/helsinki-olympic-stadium
37. External: Auditoria, Stadium reopening — https://auditoria-magazine.com/?p=10909
38. External: Wikipedia, Finlandia Hall — https://en.wikipedia.org/wiki/Finlandia_Hall
39. External: RIBAJ, Finlandia Hall renovation — https://ribaj.com/buildings/finlandia-hall-helsinki-alvar-aalto-renovation
40. External: OSCE, Helsinki Final Act — https://www.osce.org/secretariat/52566
41. External: Wikipedia, Parliament House — https://en.wikipedia.org/wiki/Parliament_House,_Helsinki
42. External: Parliament of Finland, buildings and art (PDF) — https://www2.parliament.fi/FI/naineduskuntatoimii/esitemateriaalit/Documents/Eduskunta_Taide-esite_ENGLANTI_web.pdf
43. External: Wikipedia, Women in Finland — https://en.wikipedia.org/wiki/Women_in_Finland
44. External: Wikipedia, 1907 Finnish parliamentary election — https://en.wikipedia.org/wiki/1907_Finnish_parliamentary_election
45. External: Lasipalatsikortteli, history — https://lasipalatsikortteli.fi/?p=764
46. External: This is Finland, Amos Rex — https://finland.fi/?p=61723
47. External: Wikipedia, Oodi — https://en.wikipedia.org/wiki/Helsinki_Central_Library_Oodi
48. External: Ministry of Education and Culture, Oodi opening — https://valtioneuvosto.fi/en/-/1410845/uuden-ajan-kirjasto-oodi-aukeaa-itsenaisyyspaivan-aattona
49. External: Capital.bg, Oodi and Kiasma — https://www.capital.bg/light/neshta/2022/08/26/4382474_oodi_za_helzinki/
50. External: Wikipedia, Sinebrychoff — https://en.wikipedia.org/wiki/Sinebrychoff
51. External: Wikipedia, Nikolai Sinebrychoff — https://en.wikipedia.org/wiki/Nikolai_Sinebrychoff
52. External: Sinebrychoff, A Passion for Beer — https://www.sinebrychoff.fi/newsroom/a-passion-for-beer/
53. External: Carlsberg Group, Kerava brewery — https://carlsberggroup.com/newsroom/sinebrychoff-will-produce-its-beverages-from-the-start-of-the-new-year-with-renewable-energy
54. External: Wikipedia, Swedish Theatre — https://en.wikipedia.org/wiki/Swedish_Theatre
55. External: VoiceMap, Svenska Teatern — https://voicemap.me/tour/helsinki/helsinki-walking-tour-historical-highlights-from-the-finnish-capital/sites/svenska-teatern-the-swedish-theatre
56. External: Wikipedia, Sigurd Frosterus (Stockmann 1930) — https://en.wikipedia.org/wiki/Sigurd_Frosterus
57. External: Books from Finland, Stockmann 1862–2012 — https://www.booksfromfinland.fi/2012/03/markku-kuisma-al-hulluja-paivia-huikeita-vuosia-stockmann-1862-2012-crazy-days-amazing-years-stockmann-1862-2012/
58. External: MyHelsinki, Stockmann clock — https://edit.myhelsinki.fi/en/see-and-do/shopping/iconic-places-in-helsinki-stockmann
59. External: Kaupunkiliikenne, tram history — https://kaupunkiliikenne.fi/en/history/
60. External: Helsinki history, Spora — https://historia.hel.fi/en/ilmiot/many-modes-of-transport/spora
61. External: Wikipedia, History of trams in Helsinki — https://en.wikipedia.org/wiki/History_of_trams_in_Helsinki
62. External: Helsinki tram (O.L. Kummer contract) — https://en-academic.com/dic.nsf/enwiki/1171607
63. External: Service Berlin, Alexanderplatz tram stops — https://service.berlin.de/standort/350366/pdf/
64. User-provided: Verbal input from Santtu Ahonen, 30 October 2026 (event details, route unknown, persona, "political vibes" note, local recollections)
65. External: Kaupunginosat.fi, 9 Kolmikulma (bomb of 8.11.1942) — https://kaupunginosat.fi/punavuori/2015/02/26/9-kolmikulma/
66. External: Seura, Helsingin pommitus 8.11.1942 — https://seura.fi/ilmiot/historia/helsingin-pommitus-marraskuussa-1942/
67. External: Seura, child victims and censorship — https://seura.fi/ilmiot/historia/helsingin-pommitus-vaati-lukuisia-lapsiuhreja-marraskuussa-1942/
68. External: Sotiemme perinne, Pääkaupunkiseudun sotavuodet — https://sotiemmeperinne.fi/alueellinen-perinnetyo/etusivu-pks/paikallista-sotahistoriaa-pks/paakaupunkiseudun-sotavuodet/
69. External: Wikipedia, Kolmikulma (Diana Park) — https://en.wikipedia.org/wiki/Kolmikulma
70. External: Wikipedia (fi), Teknillisen korkeakoulun vanha päärakennus — https://fi.wikipedia.org/wiki/Teknillisen_korkeakoulun_vanha_p%C3%A4%C3%A4rakennus
71. External: Walk Helsinki, Huonon onnen koulurakennus — https://walkhelsinki.fi/sotahistoriaa-huonon-onnen-koulurakennus/
72. External: Metropolia building history survey, Vanha kemia — https://docplayer.fi/164992362-Iii-vanha-kemia-metropolia-rakennushistoriaselvitys-helsinki.html
73. External: Inssit satavee, Helsingin teknillinen opisto history — http://inssitsatavee.blogspot.com/2012/07/suomenkielisen-insinoorikoulutuksen.html
74. External: Rakennuslehti 2020, hotel conversion plan — https://www.rakennuslehti.fi/2020/10/metropolian-linna-helsingin-hietalahdessa-muuttuu-hotelliksi-kojamo-haluaa-kortteliin-myos-asuntoja/
75. External: Wikipedia (fi), Helsingin yliopiston päärakennus — https://fi.wikipedia.org/wiki/Helsingin_yliopiston_p%C3%A4%C3%A4rakennus
76. External: Helsinki history, The great raids against Helsinki 1944 — https://historia.hel.fi/en/kaannekohdat/20th-century/the-great-raids-against-helsinki-1944
77. External: Lentoposti, 80 years since the great raids — https://www.lentoposti.fi/uutiset/muistamisten_sarja_helsingiss_helmikuussa_2024_suurpommitusten_kolmen_y_n_ihmeest_jo_80_vuotta
78. External: Reserviläinen, air defence 1944 — https://reservilainen.fi/ilmatorjunta-saavutti-vuoden-1944-torjuntavoitoista-ensimmaisen-lukiolaispoikien-rooli-helsingin-pelastamisessa-oli-tarkea/
79. External: YLE Teema, Helsingin yliopiston tuhoja — https://vintti.yle.fi/yle.fi/sininenlaulu/yle.fi/teema/sininenlaulu/artikkeli.php-id=172.htm
80. External: Wikipedia (fi), Kolmen sepän patsas — https://fi.wikipedia.org/wiki/Kolmen_sep%C3%A4n_patsas
81. External: Wikipedia, Three Smiths Statue — https://en.wikipedia.org/wiki/Three_Smiths_Statue
82. External: HAM, The Three Smiths — https://www.hamhelsinki.fi/?p=2310
83. External: Statues – Hither & Thither, inscription and models — https://vanderkrogt.net/statues/object.php?webpage=ST&record=fi076
84. External: Villa Hakasalmi, Where did the Three Smiths go? — https://hakasalmivilla.fi/?p=1915
85. External: Medical Economics, legend as told by a local — https://www.medicaleconomics.com/view/here-and-there-in-helsinki
86. External: G. Morgan, Three Smiths and Julius Tallberg — https://gmorgan.zenfolio.com/p1023054724/hE87D987
87. External: Kotiliesi, how "Torilla tavataan" was born — https://kotiliesi.fi/ihmiset/nostalgia/nain-lausahdus-torilla-tavataan-syntyi/
88. External: Seura, MM95 celebrations (jersey on Havis Amanda) — https://seura.fi/ilmiot/historia/mm95-nain-laman-kurittama-suomi-juhli-jaakiekon-maailmanmestaruutta/
89. External: Yle 2006, first world title celebrations (about 100,000 people) — https://yle.fi/aihe/artikkeli/2006/09/08/jaakiekon-ensimmainen-mm-kulta-sai-suomalaiset-sekaisin
90. External: Yle Selkouutiset, Torilla tavataan (1995 final vs Sweden) — https://yle.fi/a/3-11489237
91. External: Yle 2026, fifth world title celebrations at Kauppatori — https://yle.fi/a/74-20229025?origin=rss
92. External: Helsingin Uutiset 2026, Havis Amanda protection walls — https://www.helsinginuutiset.fi/paikalliset/9498974
93. External: Wikipedia, Carl Ludvig Engel — https://en.wikipedia.org/wiki/Carl_Ludvig_Engel
94. External: This is Finland, Ehrenström's plan and Engel's 30 buildings — https://finland.fi/?p=3133
95. External: Discover Helsinki, It started as a modest town — https://discoverhelsinki.fi/sightseeing/it-started-as-a-modest-town/amp
96. External: Wikipedia, Johan Albrecht Ehrenström — https://en.wikipedia.org/wiki/Johan_Albrecht_Ehrenstr%C3%B6m
97. External: Wikipedia, Armfelt Conspiracy — https://en.wikipedia.org/wiki/Armfelt_Conspiracy
98. External: Svenskt kvinnobiografiskt lexikon, Magdalena Rudenschöld (1794 pillory) — https://www.skbl.se/en/article/MagdalenaRudenschold
99. External: Helsinki history, The Three Gustavians — https://historia.hel.fi/en/media/kuva/the-three-gustavians-j-f-aminoff-j-a-ehrenstrom-and-g-m-armfelt
100. External: European Film Academy, Senate Square in film — https://www.europeanfilmacademy.org/?p=6790
101. External: Christian Science Monitor 1983, Helsinki as Moscow and Leningrad — https://www.csmonitor.com/1983/0804/080464.html
102. External: Christian Science Monitor 1983, Reds crowd logistics — https://csmonitor.com/1983/0804/080470.html
103. External: Wikipedia (fi), Helsingin valtaus (1918) — https://fi.wikipedia.org/wiki/Helsingin_valtaus
104. External: Yle 2018, Germans captured Helsinki (Samu Nyström) — https://yle.fi/a/3-10133164
105. External: Atlas Obscura, Bullet Holes in the National Museum of Finland — https://assets.atlasobscura.com/places/bullet-holes-in-the-the-national-museum-of-finland
106. External: Wikipedia, National Museum of Finland — https://en.wikipedia.org/wiki/National_Museum_of_Finland
107. External: National Museum of Finland, history — https://www.kansallismuseo.fi/en/kansallismuseo/historiaa
108. External: Walk Helsinki, Helsingin valtaus 1918 — https://walkhelsinki.fi/helsingin-valtaus-1918/
109. External: Wikipedia (fi), Suomen sisällissota — https://fi.wikipedia.org/wiki/Suomen_sis%C3%A4llissota
110. External: Itsenäisyys.fi, Kun vallankumouksen merkkilyhty syttyi — https://xn--itsenisyys-u5a.fi/kun-vallankumouksen-merkkilyhty-syttyi/
111. External: Reservin Sanomat, Paasitorni 1918 exhibition (tower fire, surrender 13.4.) — https://reservinsanomat.fi/talot-vieraissa-kasissa-valokuvanayttely/
112. External: Kansan Uutiset 2018, Punainen lyhty syttyi työväentalon tornissa — https://www.ku.fi/artikkeli/3840601-punainen-lyhty-syttyi-tyovaentalon-tornissa-sata-vuotta-sitten
113. External: Vihreät sylit (City of Helsinki), Old Church Park — https://vihreatsylit.fi/en/vanha-kirkkopuisto/
114. External: Wikipedia (fi), Vanha kirkkopuisto — https://fi.wikipedia.org/wiki/Vanha_kirkkopuisto
115. External: Helsingin seurakunnat, Vanha kirkko henkii historiaa — https://www.helsinginseurakunnat.fi/sisaltokeskus/pgk2uyvaz.html.stx
116. External: Wikipedia, Helsinki Old Church — https://en.wikipedia.org/wiki/Helsinki_Old_Church
117. External: City of Helsinki, Tarinoiden Helsinki: Ruttopuisto (PDF) — https://www.hel.fi/hel2/Tietokeskus/julkaisut/pdf/tarinoidenhelsinki_9_ruttopuisto.pdf
118. External: Seura, Rutto riehui Helsingissä — https://seura.fi/ilmiot/historia/rutto-riehui-helsingissa-tappoi-ihmisia-hyttysia-keita-kuolleet/
119. External: Finland's House of Nobility, About — https://riddarhuset.fi/en/about_us
120. External: Wikipedia, Georg Theodor Chiewitz — https://wikipedia.com/wiki/G.T._Chiewitz
121. External: MyHelsinki, House of Nobility (coats of arms) — https://edit.myhelsinki.fi/de/node/59762
122. External: Wikipedia, Presidential Palace, Helsinki — https://en.wikipedia.org/wiki/Presidential_Palace,_Helsinki
123. External: Office of the President, Presidential Palace brochure (PDF) — https://www.presidentti.fi/niinisto/wp-content/uploads/sites/3/2019/11/Presidentinlinna_esite_EN.pdf
124. External: Office of the President, renovation complete (designated 1921) — https://www.presidentti.fi/en/news/presidential-palace-renovation-complete
125. External: MyHelsinki, Engel's Helsinki walk (palace in Katajanokka idea) — https://edit.myhelsinki.fi/de/node/27644
126. External: Lux Helsinki photo-blog (Supreme Court, Pohjoisesplanadi 3) — https://sarihoo.kapsi.fi/2017_LuxHelsinki/lux.html
127. External: Wikipedia, Helsinki County Prison — https://en.wikipedia.org/wiki/Helsinki_County_Prison
128. External: Lonely Planet, hotels that were prisons — https://www.lonelyplanet.com/travel-tips-and-articles/these-10-hotels-and-hostels-were-prisons-in-a-former-life/40625c8c-8a11-5710-a052-1479d2750cc0
129. External: Strawberry, Hotel Katajanokka history — https://strawberryhotels.com/hotels/finland/helsinki/clarion-collection-hotel-katajanokka/about
130. External: Wikipedia, Katajanokka Terminal — https://en.wikipedia.org/wiki/Katajanokka_Terminal
131. External: Wikipedia, Port of Helsinki (Tallinn route 2025) — https://en.wikipedia.org/wiki/Port_of_Helsinki
132. External: Port of Helsinki, sights near Katajanokka Terminal — https://www.portofhelsinki.fi/en/about-us/port-of-helsinki/whats-new/sights-near-the-west-harbour-and-katajanokka-terminaltesting/
133. External: Government of Åland, Åland protocol and VAT area (PDF) — https://regeringen.ax/sites/default/files/attachments/protocol/nr30-2024-enskild-f1.pdf
134. External: Wikipedia, Långnäs (tax-free stop since 1 July 1999) — https://en.wikipedia.org/wiki/L%C3%A5ngn%C3%A4s

---

## Version History

| Version | Date | Author(s) | Changes |
|---------|------|-----------|---------|
| v0.1 | 30 October 2026 | Santtu Ahonen | Initial draft — generated with Claude AI |
| v0.2 | 30 October 2026 | Santtu Ahonen | Added F5a sporascope |
| v0.3 | 30 October 2026 | Santtu Ahonen | Added C14–C17 |
| v0.4 | 30 October 2026 | Santtu Ahonen | Added Claudette persona |
| v0.5 | 30 October 2026 | Santtu Ahonen | Hockey tradition in opener |
| v0.6 | 30 October 2026 | Santtu Ahonen | Added C18 Engel and Ehrenström |
| v0.7 | 30 October 2026 | Santtu Ahonen | Start/reset commands, dry-run sequence |
| v0.8 | 30 October 2026 | Santtu Ahonen | Typed cues, phone TTS, no microphone |
| v0.9 | 30 October 2026 | Santtu Ahonen | Route awareness, neighbour map |
| v0.10 | 30 October 2026 | Santtu Ahonen | Android read-aloud setup |
| v0.11 | 30 October 2026 | Santtu Ahonen | Stockmann clock, 1918 additions, C19, F7 |
| v0.12 | 30 October 2026 | Santtu Ahonen | Removed joke-explaining tags |
| v0.13 | 30 October 2026 | Santtu Ahonen | Red lantern in C05; C05 doses neutralised |
| v0.14 | 30 October 2026 | Santtu Ahonen | C20 Ruttopuisto; new schedule 17:30–19:30, reveal at Havis Amanda |
| v0.15 | 30 October 2026 | Santtu Ahonen | C20 addition |
| v0.16 | 30 October 2026 | Santtu Ahonen | C21–C22 Katajanokka in and out |
| v0.17 | 30 October 2026 | Santtu Ahonen | Speaker-notes mode; Claudette retired |
| v0.18 | 30 October 2026 | Santtu Ahonen | Passenger-card hook in protocol |
| v0.19 | 30 October 2026 | Santtu Ahonen | Flexible reveal; post-reveal mode; close split out |
| v0.20 | 13 November 2026 | Santtu Ahonen | Cards as talking points; personal details and retired material removed |

---

*Generated with Claude AI (qt-document-annotation v2026.06.26.01) — validate all figures before use.*
