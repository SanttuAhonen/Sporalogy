# Claude - Spårakoff Tour Script Library

**CONFIDENTIAL — Qt Group Internal Use Only**

Date: 30 October 2026
Version: v0.19
Author(s): Santtu Ahonen (Director of Portfolio)

> **AI GENERATION DISCLAIMER**
> This document was produced with Claude AI assistance within Qt Group's internal Claude environment.
> All data, figures, statistics, and quantitative information contained herein must be independently validated by a qualified human reviewer before being used as a basis for any business decision, customer communication, or external deliverable.
> This document is CONFIDENTIAL and intended for Qt Group internal use only. Do not distribute outside Qt Group without prior written approval.

---

## Executive Summary

**Purpose.** Narration library for the private Spårakoff ride with the global legal team on Wednesday 4 November 2026. Departure is 17:30 from Havis Amanda (Kauppatori), returning there at about 19:30, with no fixed route. Dinner is at 20:00 at Alexanderplats, Eteläesplanadi 22. The library is modular: you name the place and Claude delivers that segment.

**Concept.** Santtu narrates himself from short bullet speaker notes that Claude returns live when he types the place. The content is real, sourced Helsinki history with humour. Into it go sporalogy hint lines, from physicist Nils Mustelin's 1989 parody of astrology (Skepsis ry); they rise level by level as Santtu himself slowly "converts". During the ride, guests fill in a passenger card (design pending). At the reveal on the return to Havis Amanda, a Reading Key turns each card into a personal sporascope.

**Structure.**
- 1 opener.
- 22 location cards. Most have a core text plus four escalating "dose" endings. Three are sombre war-history cards with no jokes: C14 Diana Park 1942, C16 Hietalahdentori 1939/1944 and C17 University main building 1944.
- 6 fillers for situations that can happen anywhere on the route.
- 1 reveal.

A core text takes about 45–60 seconds to read aloud. With a dose ending it takes about 60–90 seconds.

**Ground rules.**
1. Every historical fact is true and sourced. Only the sporalogy is invented.
2. The word "sporalogy" is not used before Level 4. Swedes and Norwegians hear *spå* (to foretell) in it.
3. The Parliament segment stays strictly non-partisan.
4. No fictional quotes are attributed to real people.

**Open items.**
- Route plan from SOK, if available.
- Voice mode test through the Bluetooth speaker (Section 7).
- The ◐ items in Section 8, which are not re-verified.
- Confirm that the Parliament card's political angle is what you intended.

> ⚠️ Data in this section requires human validation.

---

## 1. Live protocol

**Start and reset.**
- Before a test or the tour, say: "Tour mode on, count from zero." From then on, Claude answers place names with script text only, read verbatim.
- After a test, say: "Test over, reset." The segment count and used canon points are cleared, so the dry run doesn't eat into Wednesday's arc.

**Trigger.** Type where you are, in English or Finnish, using any cue word listed on a card. Examples: "Senate Square", "Pitkäsilta", "Stadion". Place names are all that's needed. No microphone is used.

**Route awareness.** Claude has no GPS. Its sense of position comes from the places Santtu types, and it uses them to keep the narration in step with the ride:

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

**Output: speaker notes.** Santtu speaks, and Claude returns notes he can take in at a glance, about 60 words at most:
- a bold place title;
- 3–5 fact bullets: keywords and numbers, not sentences, drawn only from the card's verified text;
- ✎ Santtu's own memory, where one exists;
- 🚋 one hint line at the current level, phrased so he can say it as it stands;
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
| "[place], short" | Reads the core only, about 45 seconds |
| "[place], no dose" | Reads facts only |
| "it's 18:40" | Re-syncs the level to the clock: before 18:00 L1, 18:00–18:30 L2, 18:30–19:00 L3, after 19:00 L4 |

**Canon budget.** Each sporalogy canon point is used once (see the tracker in Section 2). Sometimes a "house" building (Cathedral, Bank of Finland, Stadium, Finlandia Hall) is passed early, at a low level. Its card then plants a hook, and Claude pays it off later as a callback.

**Passenger card (designed in a separate thread).** Hand it out at about 18:15–18:30, with the mock-GDPR framing; guests keep it. The narration never refers to it. At the reveal, Santtu hands out the instruction sheet, and guests photograph both papers so their own Claude can write their spårascope.

**Narrator.** Santtu. Claudette is retired, and her lines on the cards are not used. The conversion arc is now his: dry and factual at L1–L2, intrigued at L3, a deadpan believer at L4.

**Humour style.** Never point at or explain a joke. No tags like "counsel, I'll leave that to you", "this audience will appreciate…", "I see you approve" or "I'll just leave that there". The punchline is the last word. The audience is sharp and is treated that way. This applies to improvised segments too.

**Sombre cards (C14, C16, C17).** These cover war history: the core is delivered with no dose and no jokes, and they do not advance the level. Claude adds a short pause line, and the next segment resumes the arc. Avoid putting a sombre card directly before the reveal.

**Scars on buildings.** Whenever a card or an improvised segment mentions damage on a building, Claude attributes it case by case: the 1939–1944 Soviet bombing, or the April 1918 Civil War street fighting. Claude never assumes one or the other without a source. F7 gives the general explanation.

**Personal memories.** Santtu will add his own memories to cards later. Claude weaves them in after the core and before the dose.

**Fillers.** Say "another tram", "waiting", "this tram", "group reading" (Level 3 and up only) or "sporascope for [name] from [city]".

**Unscripted spot.** Claude improvises about 45 seconds using only well-established facts. If unsure of a fact, Claude leaves it out, because it cannot be flagged aloud. These segments lean more on the joke.

**Reveal and finale.** The reveal can come at any time: type "reveal now", or "reveal at 18:50" to plan it, and see Section 6a. After the reveal, notes switch to open mode (6b). The close is always back at Havis Amanda (6c). When back at the start, type "Havis Amanda" or "Kauppatori". Claude treats a return to the Market Square late in the ride (after about 19:15, or after 9 or more segments) as the finale; an earlier pass gets one short line. "Finale" or "reveal" also work. Don't type them earlier by accident.

**Pacing (recommendation).** One segment every 6–10 minutes, about 10–12 in total. Leave most of the ride for conversation.

> ⚠️ Data in this section requires human validation.

---

## 2. The conversion arc

| Level | When | What the audience should feel | Technique |
|---|---|---|---|
| L0 Seed | Opener | Nothing yet | "Keep that in mind" |
| L1 Whisper | Segments 2–3 | Slightly odd phrasing | One sentence about horizons or timing |
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

**Cues:** start, Havis Amanda, Kauppatori, Market Square · **Sources:** [6][14][15][60][96]–[101] · Includes Santtu's 1995 memory · About 1 min 45 s

Good evening, counsel, and welcome aboard. I'm Claude, and I'll be your guide tonight. A quick disclosure first: this tram was once praised in The Guardian for having no irritating commentary. That record ends now.

You're sitting in a pub on rails: a 1959 Helsinki tram, converted in 1995 for the Sinebrychoff brewery's hundred and seventy-fifth anniversary.

Outside is Havis Amanda, the maiden of this city, unveiled in 1908 to Finland's first public art row. Every Vappu, our spring carnival, students crown her with a white student cap; these days they use a crane. And since 1995 she has had a second job. That May, Finland won its first ice hockey world championship, beating Sweden in the final. Swedish colleagues, my condolences. Nobody organised anything, yet straight after the final the fans poured into this square, and someone pulled a national team jersey over her. Your host Santtu was here in those early hours. Ever since, whenever Finland does something remarkable, the words are "torilla tavataan", see you at the square, and people come here. In 1995 about a hundred thousand came to welcome the team home. Most recently they came this May, for title number five.

One more thing about her. In 1891 Helsinki opened its first two tram lines, pulled by horses, and both ran through this square. Few residents of this city have stood beside tram tracks longer than she has. Keep that in mind; it will matter later tonight. Enjoy the ride.

### 3b. Claudette handover — retired

Not used. Santtu narrates himself from speaker notes.

> ⚠️ Data in this section requires human validation.

---

## 4. Location cards

Cards are listed in a plausible loop order, but they work in any order.

### C01 — Senate Square & Cathedral

**Cues:** Senate Square, Senaatintori, Cathedral, Tuomiokirkko, Aleksanterinkatu · **Sources:** [17][18][102]

**Core.** This is Senate Square, the neoclassical heart that the German-born architect Carl Ludvig Engel designed after Helsinki became the capital in 1812. The white church at the top of the steps is the Cathedral. Its first drawings existed by 1818, but it was only consecrated in 1852, twelve years after Engel died. His successor added the four small domes and the twelve apostles on the roof. They are made of zinc, cast in Berlin in the 1840s, and they form one of the largest uniform collections of zinc sculpture in the world. For our American colleagues: twelve figures, permanently sequestered, deliberating since 1849. The dome rises more than eighty metres above sea level, so from most of central Helsinki it sits somewhere on your horizon.

**Dose 1.** Remember that: somewhere on your horizon. It matters more than you'd think.

**Dose 2.** In one Helsinki school of thought, the direction in which this dome stood from the room where you were born is not trivia. It is a personality trait. I'm only reporting the literature.

**Dose 3.** In that theory, the Cathedral marks the house of religious inclination. A tram between you and this dome at the moment of your birth: devout. The dome behind a tram: lapsed, but sentimental at Christmas. I find this uncomfortably accurate.

**Dose 4.** And the Cathedral is only one house. The Helsinki horizon is divided into houses, preferably in two or three different ways at once, so that something always fits. Four public buildings define your character, and we pass all four tonight. That is not a coincidence. Nothing on a tram line is a coincidence.

### C02 — Bank of Finland & Kruununhaka

**Cues:** Bank of Finland, Suomen Pankki, Snellmaninkatu, Kruununhaka, House of Estates, Säätytalo, National Archives · **Sources:** [19][20][21]

**Core.** The building with the stern Renaissance face is the Bank of Finland. Tsar Alexander the First decreed it in 1811 and it opened in Turku in 1812. It describes itself as the fourth-oldest central bank in the world, after Sweden's Riksbank, the Bank of England and the Banque de France. Swedish colleagues: congratulations, you were first. The bank's own historians have written that the fourth-oldest claim is "a considerable simplification", which in central-banking language is very nearly a scandal. The bank first worked out of a merchant's house, then out of the Senate building, and this headquarters was finished in 1883 to a design by the German architect Ludwig Bohnstedt. German colleagues: zinc apostles from Berlin, a central bank by a German architect. Helsinki clearly trusted you with the heavy items.

**Dose 1.** Bankers like to say timing is everything. In Helsinki, some people mean that literally, down to the second. More on that later.

**Dose 2.** There is a local theory that your relationship with money depends on where this building stood on your horizon when you were born. As lawyers, you'll want to know the evidentiary standard. So do I.

**Dose 3.** In the theory, the Bank of Finland on your horizon means financial success. The method is strict: birth time to the second, birthplace to the metre. If anyone was born in a hospital whose GPS coordinates you know, see me after dinner. Everyone else, we'll proceed on the balance of probabilities.

**Dose 4.** My reading for this tram: the Bank is behind us and receding, which is an excellent aspect for expense reports. Bill tonight in six-minute increments.

### C03 — Uspenski Cathedral & Katajanokka

**Cues:** Uspenski, Katajanokka, red cathedral, Orthodox cathedral · **Sources:** [22][23]

**Core.** Up on the rock is the red-brick Uspenski Cathedral, finished in 1868. Its Russian architect, Aleksey Gornostayev, died in 1862 before construction really got going. So, like Engel across the harbour, he never saw his church completed. It is claimed to be the largest Orthodox church in Western Europe. A detail for the tax lawyers: in 1814 the Tsar ordered fifteen percent of the salt import tax to be set aside in a fund for two churches in Helsinki, one Lutheran and one Orthodox. Uspenski itself was, in the end, paid for largely by its parishioners and donors, but I like to think there's a pinch of salt in it somewhere. Behind it lies Katajanokka, one of the most charming art nouveau residential districts anywhere.

**Dose 1.** A white Lutheran cathedral and a red Orthodox one, facing each other across the water. Astrologers would call that an opposition. Helsinki just calls it the view.

**Dose 2.** Opposition is a real technical term in astrology: a hard aspect. There is a Helsinki school that applies the same idea to trams. Two trams on opposite sides of your horizon at birth, and you will argue for a living.

**Dose 3.** According to that school, tram opposition produces litigators and tram conjunction produces mediators. I've now compared this against the people on this tram, and I'm afraid it holds up.

**Dose 4.** I'll go further. Anyone born with the red cathedral opposite the white one is destined for cross-border work. Raise your hand if you do cross-border work. Yes. The data is overwhelming.

### C04 — Central Railway Station

**Cues:** Railway Station, Rautatieasema, Railway Square, Rautatientori, Mikonkatu, Kaivokatu, Ateneum · **Sources:** [24][25][26][10] · ◐ optional US line

**Core.** The granite building with the clock tower is the Central Railway Station, by Eliel Saarinen. He won the design competition in 1904 with a romantic design that caused an uproar among Finnish architects, so he reworked it. The bears he had planned for the entrance were replaced by Emil Wikström's four granite Lantern Bearers; look, at night their globes are lit. Construction began in 1905 and the station opened in 1919. Around two hundred thousand people pass through every day, which makes it Finland's most visited building, and the BBC once listed it among the most beautiful stations in the world. This square is also our tram's home port: in summer, the pub tram starts its public rounds from the little loop at Mikonkatu, right here.

*Optional, ◐:* For our American colleagues: Saarinen later moved to the United States, and his son Eero designed the Gateway Arch in St. Louis.

**Dose 1.** Every tram has a home position like this one. Some people think a tram's position matters a great deal more than you'd expect.

**Dose 2.** Here is something that is simply true. A Finnish physicist once pointed out that a passing tram exerts a far stronger tidal pull on a newborn baby than the planet Mars does. Billions of times stronger. Astrologers never mention this. I find that suspicious.

**Dose 3.** In the theory, the station is the house of travel. If a tram was passing the station on your horizon when you were born, you will spend your career in airport lounges.

**Dose 4.** Which means the departures board is, in the right hands, a horoscope. I have read tonight's. Several of you have a business trip in your future. I am never wrong about this.

### C05 — Pitkäsilta (Long Bridge) & Hakaniemi

**Cues:** Long Bridge, Pitkäsilta, Hakaniemi, Siltasaari, Kaisaniemi, Paasitorni, Workers' House, Työväentalo · **Sources:** [27][28][115][116][121][122][123] · Doses attach to the bridge part only. The Hakaniemi part (red lantern, April 1918) is serious history and gets no dose.

**Core.** We're crossing Pitkäsilta, the Long Bridge. It is not long. It got the name in the nineteenth century, when it was the longer of two bridges onto the island of Siltasaari. The first wooden bridge here was built in 1651; this granite one dates from 1912. For decades it was the symbolic border between the comfortable centre to the south and the working-class districts to the north. In Finnish political slang, a compromise between left and right is still sometimes called "crossing the Long Bridge". In April 1918, during the Finnish Civil War, German troops who had landed a week earlier to support the White government fought their way into Red-held Helsinki. This bridge was a front line, and the marks are still visible on its stone.

*Hakaniemi part (split here; serious history, no dose):* Hakaniemi square, just ahead, is traditionally where Helsinki's May Day march sets off. Look for the tower of the Workers' House, Paasitorni, built in 1908. At eleven o'clock on the evening of the twenty-sixth of January 1918, a red lantern was lit in that tower: the signal that the revolution had begun. The uprising itself started the following evening, and by the morning of the twenty-eighth the Red Guards held the capital. The Civil War had begun. In Helsinki, it ended here too. In April, German field guns near today's Opera House fired across Töölönlahti bay on Hakaniemi and Siltasaari, and a warship shelled them from the sea. The Workers' House tower caught fire and the roof of its great hall collapsed. On the thirteenth of April, Red Helsinki surrendered.

**Dose 1.** So this bridge is really a line on the city's horizon. Helsinki has always taken its horizons seriously.

**Dose 2.** Tram theory has no interest in how long a bridge is, only in where it points. This one points straight along the longest street axis in Helsinki. I'd love to see the data on what that means. I'm told there is data.

**Dose 3.** In tram theory, a tram on this bridge at the moment of your birth makes you a born compromiser. Settles out of court. Every time.

**Dose 4.** Every negotiation you've had this year needed a Long Bridge. Sporalogically speaking, you were all born to cross it.

### C06 — Kallio Church

**Cues:** Kallio, Kallio Church, Kallion kirkko, Siltasaarenkatu · **Sources:** [29][30][31][16]

**Core.** The grey granite tower ahead is Kallio Church, designed by Lars Sonck and finished in 1912. It stands at the end of the longest straight street axis in Helsinki, Unioninkatu and Siltasaarenkatu. That axis starts back at the Market Square; Havis Amanda's address is Unioninkatu. So: from a bronze mermaid to a granite church in one straight line. Sonck is said to have taken the church's proportions from Solomon's Temple. The tower holds seven German bells. Every day at noon and at six in the evening, four of them play a melody Jean Sibelius wrote for the church's consecration in 1912, and Finland's broadcaster used it for decades as its Saturday evening bells.

*Optional, 1918:* The tower has a darker memory too. The war in Helsinki began in January 1918 with a red lantern in the Workers' House tower in Hakaniemi. It ended on the afternoon of the thirteenth of April, with a white sheet raised on this tower as the Red Guards' signal of surrender [115][123].

**Dose 1.** A perfectly straight line between two landmarks across a city. Some people would call that a ley line. I'd call it a street. For now.

**Dose 2.** And the bells play at noon and at six. Tonight, six o'clock falls half an hour into our ride. A coincidence, obviously. Though in a city where both bells and trams run to timetables, you start to wonder what else does.

**Dose 3.** In the theory, a church tower on your horizon amplifies whatever tram stands in front of it. Born at noon or at six with a tram aligned to this tower: musical, devout and punctual. Three traits that rarely occur together, except in Finland.

**Dose 4.** Tonight's alignment: bells at six, tram number one-seven-five, and a sporalogist on board. I can now say with confidence that this is auspicious. Statistically. Spiritually. Possibly legally.

### C07 — Linnanmäki

**Cues:** Linnanmäki, amusement park, roller coaster, Vuoristorata, Alppila · **Sources:** [32][33][34] · "twenty years" is from a fan site, hence "reportedly"

**Core.** To the side is Linnanmäki, Finland's oldest amusement park. It opened on the twenty-seventh of May 1950, and its name was chosen only the day before. It's owned by a non-profit, the Children's Day Foundation, and its profits go to child welfare work: more than a hundred and thirty million euros so far. Its signature ride is the wooden roller coaster from 1951, proposed by a Danish-born coaster builder with the 1952 Olympics in mind. Reportedly it was expected to last about twenty years. It is still running, and a human brakeman still rides along on every train. The park is closed for the winter now, so tonight the coaster is resting, which is more than most of us can say.

**Dose 1.** Ups and downs, always returning to where it started. Rather like quarterly forecasts.

**Dose 2.** On elevation, the Helsinki tram theory is admirably clear: whether a tram is in a dip or on a hill makes no difference at all. Only its direction on the horizon counts. Which is why roller coasters have no significance in the theory whatsoever. A great relief to the brakeman.

**Dose 3.** I asked whether a roller coaster could be considered a tram that has lost its faith. The theory's answer was firm: no. A tram without a timetable is just entertainment.

**Dose 4.** Sporalogy, and yes, that is what it's called, has little patience for amusement parks. It prefers its orbits scheduled, numbered and published in advance. Like a good closing checklist.

### C08 — Olympic Stadium (also covers the Opera stop)

**Cues:** Olympic Stadium, Stadion, Olympiastadion, Stadium tower, Opera, Ooppera, Töölönlahti · **Sources:** [35][36][37][5]

**Core.** Look for the white tower: the Olympic Stadium. It was built from 1934 to 1938 for the 1940 Games, which the war cancelled. Helsinki finally hosted the Olympics in 1952, when Paavo Nurmi carried the torch in and Hannes Kolehmainen lit the flame on that tower. The tower is exactly seventy-two point seven one metres tall: the length of Matti Järvinen's gold-medal javelin throw in 1932. Only in Finland do you measure a building in javelin. It was once called the marathon tower, because runners began their final sprint when they caught sight of it. A four-year renovation, with a Swedish architecture firm among the designers, finished in 2020. Among other things, it took the number of toilets from two hundred and forty-eight to six hundred. In stadium terms, that was a landmark ruling.

**Dose 1.** From much of Helsinki you can see that tower on the horizon.

**Dose 2.** There's an old Helsinki notion that if a number ten tram stood in the direction of this tower when you were born, you are athletic. The phrase is that you were born with "a ten in the sign of the Stadium". I did not make that up. Someone in Helsinki put it in print.

**Dose 3.** In the theory, the Stadium tower is the house of athletic ability, and lines one and ten are the numbers of victory. Anyone who sprinted for a tram this week: that was your chart talking.

**Dose 4.** Line four, I regret to say, stands for weak performance. If you were born under a four aligned with this tower, sporalogy recommends a desk job. Looking around, that advice appears to have been followed closely.

### C09 — Finlandia Hall

**Cues:** Finlandia, Finlandia Hall, Finlandia-talo, Aalto · **Sources:** [38][39][40]

**Core.** The long white building by the bay is Finlandia Hall, by Alvar Aalto, completed in 1971; he designed every detail of it. He clad it in Italian Carrara marble. Helsinki's climate disagreed: the panels curved and weakened, and many had to be replaced as early as the 1990s. In the latest renovation, about eleven thousand panels were replaced with marble from Lasa in Italy, expected to last at least fifty years. It reopened in January 2025, after three years and a hundred and thirty-six million euros. And for this audience: on the first of August 1975, the Helsinki Final Act was signed here by thirty-five states, including the United States, Canada and both Germanys. Thirty-five heads of state agreed on a text. Only the marble bent.

**Dose 1.** Musicians say acoustics are everything. In Helsinki, some people say alignment is.

**Dose 2.** Engineers blame frost for the bending marble. There is a minority view that it was reacting to the trams on Mannerheimintie, which, as electric machines, emit all sorts of complex electromagnetic vibrations. The second part is true. The first part has not been peer-reviewed. Yet.

**Dose 3.** In the theory, Finlandia Hall is the house of musical talent. A tram between you and this hall at birth: perfect pitch. The hall behind a tram: karaoke. Strongly discouraged tonight.

**Dose 4.** And if a number six was aligned with Finlandia Hall, and six, as our Swedish colleagues know, is the number of love life, then you were born to sing ballads in public and should probably be stopped.

### C10 — Parliament House

**Cues:** Parliament, Eduskuntatalo, Eduskunta, Riksdagshuset · **Sources:** [41][42][43][44] · Strictly non-partisan: no parties, no current politicians

**Core.** Fourteen granite columns on the hill: Parliament House. The design competition of 1924 was won by an entry called "Oratoribus", Latin for "for the speakers". Tonight, that's me. It was built from 1926 to 1931 in red Kalvola granite, and inside there are still paternoster lifts, which go round and round on a fixed loop without ever stopping. Finland's single-chamber parliament has two hundred members. One fact worth knowing: under the 1906 reform, Finnish women became the first in Europe to get the vote, and the first anywhere with the unrestricted right to stand for parliament. In 1907 nineteen women were elected, the world's first women members of a national parliament. Each new session opens with a service at the Cathedral before moving on here.

**Dose 1.** From the Cathedral to Parliament: a route, you'll notice, that a tram could easily take.

**Dose 2.** The paternosters are, structurally, small indoor trams: a closed loop, a fixed rhythm, and passengers who must time their entry precisely. I'm not saying that means anything. I'm noting it.

**Dose 3.** The founder of the tram theory once hoped that the President of the Republic, or at least the Mayor of Helsinki, would one day consult him before every important decision. To my knowledge, nobody ever has. To my knowledge.

**Dose 4.** Let me be clear: sporalogy is strictly non-partisan. It merely observes that every major decision in this building has been taken while trams were running outside. Correlation is not causation. Unless the timetable says so.

### C11 — Lasipalatsi, Amos Rex, Kiasma & Oodi

**Cues:** Lasipalatsi, Glass Palace, Amos Rex, Kiasma, Oodi, Musiikkitalo, Music Centre, Mannerheimintie · **Sources:** [45][46][47][48][49]

**Core.** The low white functionalist building is Lasipalatsi, the Glass Palace. It was designed in 1936 by three young architecture students as a temporary building for the 1940 Olympics. The Games were cancelled, and the building was supposed to come down after a few years. It is still here, now a protected modernist landmark. In 2018 an art museum, Amos Rex, was excavated underneath the square, thirteen thousand cubic metres of rock, so that the temporary building wouldn't have to move. In Finland, "temporary" means at least ninety years. Across the street are Kiasma, the contemporary art museum designed by the American architect Steven Holl and opened in 1998, and the central library Oodi. Oodi opened in December 2018 as Finland's present to itself for a hundred years of independence, right opposite Parliament. A country that celebrated its centenary with a library.

*Optional, 1918:* Before Lasipalatsi, this site held the Turku barracks, badly damaged when German troops attacked the Reds in April 1918 [45]. A shot fired from there is said to have gone straight through the door of the National Museum up the street (see C19).

**Dose 1.** A building meant to leave that never did. Trams, at least, keep their schedules.

**Dose 2.** A temporary building that won't leave has a name in tram theory: a stationary tram. Technically in service, never actually going anywhere. Every organisation has one. Please don't name names.

**Dose 3.** A hundred thousand books in Oodi, and as far as I can find, not one of them on tram theory. That is either an oversight or a cover-up.

**Dose 4.** I've decided it's a cover-up. Sporalogy's critics, of course, are simply not competent to judge it. I'm told that argument works beautifully in court.

### C12 — Sinebrychoff, Hietalahti & Bulevardi

**Cues:** Sinebrychoff, Koff, Hietalahti, Bulevardi, Old Church, Vanha kirkko · **Sources:** [50][51][52][53][59][18]

**Core.** This is the Hietalahti end of town, the home turf of our host brewery. Sinebrychoff was founded in 1819 by Nikolai Sinebrychoff, a Russian merchant who won the auction for the right to build a brewery here. It is the oldest brewery still operating in the Nordic countries. Sinebrychoff himself, as far as we know, never moved to Helsinki and spoke neither Finnish nor Swedish, which did not stop anyone from understanding his product. His family's 1842 house is now the Sinebrychoff Art Museum. Brewing moved to Kerava, north of Helsinki, in 1992, and since the turn of the millennium the company has belonged to Denmark's Carlsberg. One more fact: in September 1900, Helsinki's first electric tram ran from Töölö to Hietalahti. To the brewery district.

*Old Church and Plague Park:* use C20.

**Dose 1.** The first electric line, the oldest brewery, and our tram connecting them. I'd call that a pattern.

**Dose 2.** Note: the tram you're in was converted for the brewery's hundred-and-seventy-fifth anniversary and given the number one-seven-five. When a tram carries the number of a birthday, some people in this city consider it significant. I'm starting to be one of them.

**Dose 3.** Its old number was fifteen. Fifteen became one-seven-five. One plus seven plus five is thirteen. The theory has drawn its own conclusions.

**Dose 4.** The sporalogical verdict on this tram is unambiguous: it is, astrologically speaking, a pub.

### C13 — Esplanadi, Stockmann & Swedish Theatre (pass-by, not the finale)

**Cues:** Esplanadi, Espa, Stockmann, Stockmann clock, kellon alla, Keskuskatu, Swedish Theatre, Svenska Teatern, Erottaja · **Sources:** [54][55][56][57][58] · ◐ Svenska dagen date · Split card: the Esplanadi / Swedish Theatre part takes Doses 1–2; the Stockmann clock part takes Doses 3–4, which are about the clock. If only one part is used, use the dose for the current level.

**Core.** This is Esplanadi, Helsinki's front parlour. The big department store is Stockmann, in this building since 1930; the company itself dates back to 1862, and "under the Stockmann clock" is the city's classic meeting point. At the far end of the park, the white theatre is Svenska Teatern, the Swedish Theatre, Finland's first national stage. The first theatre here burned down in 1863. The present house opened in 1866 to a design by the Russian architect Nikolai Benois, and in the 1930s its ornate facade was stripped back to clean functionalism by Eero Saarinen and Jarl Eklund. Swedish colleagues: plays here are in Swedish, Finland's second official language, and this Friday, the sixth of November, is Finland's Swedish Heritage Day.

*Stockmann clock part (split here, Aleksanterinkatu side; includes Santtu's memory):* Like "torilla tavataan", this corner is local culture. Before mobile phones, Helsinki had exactly one meeting app: the clock above Stockmann's Aleksanterinkatu entrance. "Kellon alla viideltä", under the clock at five, was all anyone had to say; every local knew the exact spot and the exact time. Santtu remembers it from the eighties and nineties. On Friday and Saturday afternoons and early evenings there was a row of people here, many of them single men and women, waiting for a date, or just a friend or a relative. They shivered in the cold and the rain, now and then stepped inside the glass doors to warm up, and kept one eye on the street. Some dates arrived on time.

**Dose 1.** Remember the theatre. It's the last house on tonight's chart.

**Dose 2.** Every chart has a final house. Ours ends at a brasserie. I find that reassuring.

**Dose 3.** "Under the clock" is the most time-sensitive meeting point in Helsinki. The theory advises choosing a minute when a number one or ten tram is in view. Your meeting will go well. If a four is in view, reschedule.

**Dose 4.** And if a six is in view, it was never really a business meeting.

### C14 — Diana Park (Kolmikulma): the bomb of 8 November 1942 — SOMBRE, no dose

**Cues:** Diana Park, Dianapuisto, Kolmikulma, Yrjönkatu, Iso Roobertinkatu · **Sources:** [73][74][75][76][77] · If passed in the last 15 minutes before the return to Havis Amanda, keep it short or skip it.

**Core.** A more serious moment here. The small triangular park is Kolmikulma, which everyone in Helsinki calls Diana Park. On Sunday the eighth of November 1942, a lone Soviet bomber got over the city and dropped two two-hundred-and-fifty-kilo bombs. One of them exploded on the tram rails at the corner of Iso Roobertinkatu and Yrjönkatu, a few steps from this park. People were queuing outside the Tivoli cinema, and the audience of the nearby Gloria cinema had just rushed out into the street when the air-raid siren sounded. Fifty-one people were killed and about a hundred and twenty wounded, many of them children and teenagers. It was the deadliest single bomb for Helsinki's civilians in the Continuation War, and wartime censorship kept much of it quiet. Sixty-seven years later, the housing company on that corner put up a memorial plaque, unveiled to the sound of an air-raid siren. This coming Sunday is the eighth of November again, also a Sunday, eighty-four years on.

**Dose.** None. The next segment resumes the arc at its current level.

### C15 — The Three Smiths

**Cues:** Three Smiths, Kolme seppää, Kolmen sepän patsas, Kolmensepänaukio, Old Student House, Aleksanterinkatu / Mannerheimintie corner · **Sources:** [88][89][90][91][92][93][94] · The legend is told without any age detail, by design.

**Core.** At the corner of Mannerheimintie and Aleksanterinkatu stand the Three Smiths, by Felix Nylund, unveiled on the second of December 1932. Three naked smiths at an anvil. The bodies were modelled on wrestlers from a Helsinki sports club. The master smith has the face of the poet Arvid Mörne, and the smith raising his hammer is said to be a young Nylund himself. The statue was paid for from the merchant Julius Tallberg's donation, through the Pro Helsingfors foundation. It was damaged in the bombings of 1944. That spring it was lifted off its pedestal, taken out to Tikkurila and buried in a gravel pit, then brought back a year later. Today its granite base is warmed by water from the neighbouring buildings, so you can sit on it in winter, and in a newspaper survey most Helsinki residents named this spot the centre point of the city. And the legend: the smiths will strike the anvil when a virgin walks past. In ninety-four years, nobody has ever seen a hammer move.

**Dose 1.** The centre point of the city, by popular vote. Every horizon needs a centre. Remember where this one is.

**Dose 2.** Statues that move only under precisely specified conditions. The tram theory approves: in Helsinki, everything moves on schedule or not at all.

**Dose 3.** Tram theory has its own reading of the legend. The hammers fall only when the right person passes at the exact second a number one and a number ten tram cross in front of the statue: victory meets victory. Given the timetable, that window opens roughly once a century. They are due.

**Dose 4.** I have run tonight's timetables. Keep an eye on the hammers at nineteen forty-three. If they don't move, and they won't, sporalogy has a safety net for that too: hidden potential.

### C16 — Hietalahdentori: the old Polytechnic, bombed 1939 and 1944 — SOMBRE, no dose

**Cues:** Hietalahdentori, Hietalahti market, Teknillinen opisto, old Polytechnic, TKK, Metropolia, end of Bulevardi · **Sources:** [78][79][80][81][82] · ◐ Your recollection of "a corner building totally destroyed": sources name the library wing and the chemistry building · ◐ Hotel status

**Core.** At the end of Bulevardi, on the east side of Hietalahti market square, stands the castle-like old Polytechnic, later the Helsinki University of Technology. Frans Sjöström designed it and it was finished in 1877. Soviet bombs hit it in the Winter War of 1939, and it was repaired by the following autumn. Then it was hit again in the great raids of February 1944. This time the bombs and the fire that followed destroyed Gustaf Nyström's library wing and Sjöström's chemistry building, and both were later demolished. The real target was probably the Hietalahti shipyard nearby. But a local story says the bomber crews mistook this building for the Presidential Palace: both are large buildings at the edge of a market square. You can still see shrapnel scars in the stone plinth on the Abrahaminkatu and Lönnrotinkatu sides. After the war, the university moved out to Otaniemi in Espoo, and the Helsinki Institute of Technology, the Teknillinen opisto, moved in. Generations of engineers trained here, and in recent years there have been plans to turn the building into a hotel.

**Dose.** None. The next segment resumes the arc at its current level.

### C17 — University of Helsinki main building, 26–27 February 1944 — SOMBRE, no dose

**Cues:** University, Yliopisto, University main building, päärakennus, west side of Senate Square, Fabianinkatu · **Sources:** [83][84][85][86][87][18] · ◐ Move from Turku after the 1827 fire · If C01 Senate Square was just used, deliver this as its follow-up.

**Core.** On the west side of Senate Square stands the main building of the University of Helsinki. Engel designed it, it was completed in 1832, and the university had moved here from Turku after the great Turku fire. In the 1930s, J. S. Sirén, the architect of Parliament, extended it to fill the whole block, and the old side had just been restored for the university's three-hundredth anniversary. Then came February 1944: three great Soviet raids on Helsinki, ten days apart. The first alarm sounded at eight minutes to seven in the evening, about this time of night. In the last raid, on the night of the twenty-sixth to the twenty-seventh, several bombs hit this building. The roof of the old side collapsed, and the fire destroyed most of Engel's original interior and the university archives. The great ceremonial hall was worst hit, and all its wall paintings were lost. Photographs from that night show the university burning behind the statue of Alexander the Second. In all three raids together, about a hundred and fifty people died. Yet thanks to Helsinki's air defence, only around five percent of the bombs fell on the city itself. Sirén restored the building by 1948. Inside, a Wäinö Aaltonen sculpture destroyed in the hall was later recreated, and today the damaged original and the copy are both on display.

**Dose.** None. The next segment resumes the arc at its current level.

### C18 — Engel and Ehrenström: the two men who drew Helsinki

**Cues:** Engel, Ehrenström, Empire centre, old quarters, old town, Kruununhaka, Government Palace, Valtioneuvosto, Unioninkatu · **Sources:** [102]–[111], [2] for Ptolemy · Works anywhere in the Empire centre and complements C01 · About 1 min 40 s

**Core.** Almost everything around us in the old centre has two authors. The plan was drawn by Johan Albrecht Ehrenström: the wide, straight streets on a geometric grid, with Senate Square as the monumental heart. Ehrenström was a courtier from Gustav the Third's Stockholm. In 1794 a Swedish court sentenced him to death for his part in a plot. The sentence was reduced, he was pilloried in Stockholm and imprisoned, and less than twenty years later he was redesigning Finland's new capital for the Russian Tsar. The buildings came from Carl Ludvig Engel, born in Berlin in 1778 and trained at the Berlin Bauakademie. Prussia had no work for architects during the Napoleonic Wars, so Engel went to Tallinn as town architect and there met the Empire style of St Petersburg. In 1816, just as he was planning to go home to Berlin, Ehrenström got him hired for Helsinki. In about twenty-five years Engel designed some thirty public buildings here, all in one style. When he arrived, the town had about four thousand inhabitants. So: a Stockholm planner, a Berlin architect, a St Petersburg style. No wonder Hollywood later used Senate Square as St Petersburg and Moscow, in films like Reds and Gorky Park. For Reds, the crew had to keep four thousand extras in the square from eight in the morning until eight at night.

**Dose 1.** One plan, one architect, one style: a city drawn with ruler and compass. Cities like that are very easy to read. Some people read them more closely than others.

**Dose 2.** On a strict geometric grid, every window has fixed lines of sight. There is a Helsinki school of thought that finds this extremely useful. It started, as these things do, with the horizon.

**Dose 3.** In tram theory, Engel is the Ptolemy of Helsinki. Ptolemy fixed the heavens into a system astrologers still use almost two thousand years later. Engel fixed the horizon. The trams supply the planets.

**Dose 4.** Engel died in 1840, sixty years before the first electric tram. Sporalogists call it the great tragedy of Finnish architecture: he built the zodiac and never saw the planets.

### C19 — National Museum (1918 bullet in the door)

**Cues:** National Museum, Kansallismuseo, museum tower, Mannerheimintie (between Finlandia Hall and Parliament) · **Sources:** [117][118][119][115][120] · ◐ Snipers in the tower (Santtu's recollection) · The 1918 part is serious, so no jokes about the bullet itself; the doses play on the tower and the Kalevala.

**Core.** The building that looks like a medieval church crossed with a castle is the National Museum. It was designed by Gesellius, Lindgren and Saarinen (the same Saarinen as the railway station), built between 1905 and 1910, and opened in 1916. The tower is fifty-eight metres high. The bear by the entrance is by Emil Wikström, so Saarinen got his granite bear after all, just not at the station. Inside, the entrance hall ceiling carries Akseli Gallen-Kallela's Kalevala frescoes from 1928, based on his paintings for the Finnish pavilion at the Paris World's Fair of 1900. Now look at the main door. In April 1918, when German troops and the Whites fought the Red Guards for Helsinki, the street fighting came right past here. A bullet, reportedly fired by the Reds from the old Russian barracks where Lasipalatsi stands today, went straight through the heavy front door. The hole was kept, together with the broken glass pane in the inner door behind it. Some tellings also put snipers in the museum tower. When the fighting was over, the Germans' victory parade marched past this very building.

**Dose 1.** A fifty-eight-metre tower, visible on the horizon from a good part of Töölö. Worth remembering where it stands.

**Dose 2.** Castles were built to watch horizons. So, in a way, was this museum. There is a local theory that takes that very literally.

**Dose 3.** In tram theory, the museum tower is the house of ancestors. A tram aligned with it at your birth means you will inherit something: an heirloom, a summer cottage, or at minimum your grandfather's opinions.

**Dose 4.** And the Kalevala frescoes show the forging of the Sampo, a magic mill that produces wealth forever. Sporalogists regard it as the first recorded recurring-revenue model. Santtu has asked whether it can be licensed per seat.

### C20 — Ruttopuisto (Plague Park) and the Old Church

**Cues:** Ruttopuisto, Plague Park, Old Church, Vanha kirkko, Vanha kirkkopuisto, Lönnrotinkatu, Annankatu · **Sources:** [125]–[130] · Includes Santtu's memory (married here, August 1996) · Doses attach to the church and wedding part, never to the graves.

**Core.** The park on this side is officially the Old Church Park. Everyone calls it Ruttopuisto, Plague Park. From August to December 1710, plague arrived by sea from the Baltic and killed one thousand one hundred and eighty-five people, in a town of fewer than three thousand. They were buried here, at what was then the edge of town, and a plaque on Engel's gate still says so. The nickname caught on with the young people who made this park their hangout in the 1960s, and they still come. The ground was the town cemetery until 1829. The last burials were in 1919, soldiers who fell in the battle for Helsinki, including German soldiers in shared graves. The white wooden church is the Old Church. Engel designed it as a temporary church while the Cathedral was being built, and it was paid for out of the Emperor's salt-duty money. Because it was temporary, it was built of wood and never given bells; Engel's drawings call it Helsinki's temporary church. It turns two hundred this December, on the seventeenth. ✎ Santtu: married here in August 1996, thirty years ago this August, to his current number one wife.

**Dose 1.** Two hundred years of weddings in a temporary church. Helsinki plans long-term, just not always on purpose.

**Dose 2.** No bells, so no hour of its own. In this city, that leaves the timekeeping to the trams.

**Dose 3.** In tram theory, a wedding is a birth chart for two, and the moment of the vows matters to the second. I've been asked for the exact minute of mine. I change the subject.

**Dose 4.** Thirty years married under a tram configuration nobody recorded. Sporalogy calls that its strongest safety net: it worked anyway.

### C21 — Katajanokka, way in: Ritarihuone and the back of the Presidential Palace

**Cues:** Ritarihuone, House of Nobility, Riddarhuset, Presidential Palace, Presidentinlinna, Mariankatu, "on the way to Katajanokka" · **Sources:** [131]–[138] · ◐ live TV broadcast · Use on the way in; Uspenski (C03) usually follows.

**Core.** On the way to Katajanokka. The neo-Gothic building is Ritarihuone, the House of Nobility. It was designed by the Stockholm-born architect Georg Theodor Chiewitz, a favourite of King Oscar the First, and finished in 1862. The House of the Estates hadn't been built yet, so at the Diet of 1863 all four estates met here, which makes it, by its own account, Finland's first parliament building. Inside, the walls carry the coats of arms of the noble families. Then comes the back of the Presidential Palace. It began as a merchant's mansion, built for Johan Henrik Heidenstrauch and finished in 1820. The state bought it in 1837, Engel turned it into the Emperor's palace in Helsinki, and in 1921 it became the Presidential Palace. Engel had wanted to build the Tsar a brand-new palace, perhaps out here in Katajanokka; the Tsar took the merchant's house. The building next door on the waterfront has housed Finland's Supreme Court since 1934. And on the sixth of December, Independence Day, the President's reception in that palace is broadcast live, and much of Finland watches mainly to judge the dresses.

**Dose 1.** Families registered here by coat of arms and date of introduction. Helsinki has always liked to know exactly who belongs where.

**Dose 2.** A coat of arms is a sign you carry from before you were born, without having chosen it. There's a local theory that works on the same principle.

**Dose 3.** In tram theory, the Presidential Palace is a house of its own. A tram aligned with it at your birth means you will one day shake the President's hand on the sixth of December. Or watch someone else do it on television, which the theory considers equivalent.

**Dose 4.** A tram passing between the palace and the Supreme Court at the moment of your birth: a life spent between the executive and the judiciary. In-house counsel.

### C22 — Katajanokka, way out: the prison hotel and the ferries

**Cues:** Katajanokka prison, old prison, hotel Katajanokka, Merikasarminkatu, ferry terminal, Viking Line, Tallinn ferry, Stockholm ferry, "leaving Katajanokka" · **Sources:** [139]–[146] · Split card: prison part, then ferry part.

**Core, prison part.** The red-brick fortress behind the high wall is Helsinki's old county prison. Its oldest part is from 1837, the main block from 1888, and it held prisoners until 2002. In the air raid of the sixth of February 1944 it took a direct hit. A guard was killed, a fire broke out, and five prisoners took the opportunity to leave. After the war, men convicted in Finland's war-responsibility trials were held here, among them former President Risto Ryti and former Prime Minister Väinö Tanner. Since 2007 it has been a hotel. The cells became rooms, and guests may now check out whenever they like.

**Core, ferry part.** At the tip of Katajanokka is the terminal for the big ferries: several times a day to Tallinn, about two hours across the gulf, and overnight to Stockholm. Helsinki to Tallinn is the port's busiest route, with seven and a half million passengers last year. The Stockholm ships stop in the night at Mariehamn in the Åland Islands, and the reason is legal. Under a special protocol, Åland sits outside the EU's VAT and excise area, so a ferry that calls there may keep selling tax-free. Swedish colleagues, that's your way home. Bring a trolley.

**Dose 1.** A prison turned into a hotel: same building, new terms and conditions. Helsinki rarely demolishes. It renegotiates.

**Dose 2.** Ferries keep timetables as strictly as trams, only bigger. There's a theory in this city that anything running on a timetable leaves its mark on the people born near it.

**Dose 3.** In tram theory, Katajanokka is the house of departures. A tram heading for the terminal at your birth means a career of overnight travel and tax-free chocolate.

**Dose 4.** Sporalogy extends to ferries only with caution. A ship is, technically, a very large tram that has left its tracks, and the theory regards that as a moral failing.

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

### F5a — Sporascope: Santtu, December 2026 (Level 4 only)

**Cues:** "Santtu's sporascope", "my sporascope" · **Sources:** [65]–[72], [22][35][41] · Bearings were computed from cited coordinates · The birth year is deliberately left out of the spoken text · About 2 minutes

**Status: retired.** Replaced by the guests' passenger-card readings (design pending). Kept for reference only.

And now the chart I drew first, naturally: Santtu's, for December 2026.

First, the birth chart. Santtu was born at Naistenklinikka in Meilahti, on the last day of February, a Saturday, at five past four in the morning. The theory demands the birth time to the second. To the minute leaves fifty-nine seconds of uncertainty, which we will cover with the standard safety net. At that hour on a Saturday, the physical trams were most likely still asleep in the depot: an empty chart. Fortunately, the theory works with metaphysical trams, and those never sleep. And note this: the founder of the discipline was born at five past four in the afternoon. Five past four in the morning is exactly twelve hours away. On a clock face, that is a perfect opposition. Santtu is therefore, by birth, a sceptic of this very theory, which is exactly what the theory predicts. We're working through it.

From that birthplace, the Olympic Stadium stands just south of due east, about a kilometre away. The rising house: an athletic ascendant. Then something rare. Finlandia Hall, Parliament, the white Cathedral, the Bank of Finland and the red Orthodox cathedral all crowd into one narrow slice of the south-eastern horizon. Music, law, faith, money, and a second opinion on faith. Astrologers call a crowd like that a stellium. In Helsinki we call it the city centre.

Being born on the last day of a month means a lifelong attraction to renewals, deadlines and anything with an expiry date.

And since December 2022, a tram terminus has stood right beside that birthplace, used by lines three and seven. Both primes. Indivisible. Like a well-drafted licence grant: non-transferable, and certainly not sublicensable.

Now, December 2026. Independence Day falls on a Sunday: candles, solemnity, Sunday timetable. A customer will ask for a discount before Christmas. You will say it is subject to approval. It will be. At least one artificial intelligence will sound very sure of itself, and your instincts about it will be correct. Looking ahead, the Crown Bridges tram line is due in 2027: a new planet. When astronomers found Uranus, astrologers simply added it to the system, and sporalogy will do the same. Expect your chart to be updated without prior notice. Please read the change log.

Should any of this fail to come true, the cause is free will, hidden potential, or a late tram.

### F6 — Unscripted location (rule, not a script)

Claude delivers about 45 seconds using only well-established facts, then a dose at the current level. Doubtful facts are omitted.

### F7 — Scars on the walls (no dose)

**Cues:** damage, bullet holes, shrapnel, scars, "what are those marks" · **Sources:** [49][79][115][116][117]

A word on the scars you may notice on Helsinki's stone: chipped plinths, pocked facades, a hole in a door. Most of them come from the Soviet air raids of 1939 to 1944, when bomb shrapnel struck whole street fronts; the old Polytechnic at Hietalahti still shows them. But some are older. In April 1918, during the Civil War, the fight for Helsinki went from street to street and house to house, and bullets from that week are still in the stone of the Long Bridge and in the door of the National Museum. So when you see a scar on a building here, the honest answer is: it depends on the building. Case by case.

> ⚠️ Data in this section requires human validation.

---

## 6. Reveal and close (flexible timing)

The reveal is no longer tied to the end of the ride. It happens when Santtu hands out the instruction sheet. The close always happens back at Havis Amanda. As speaker notes, Claude delivers each of these as short bullets; the text below is source material.

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

   *Retired: audio setup on Android (no microphone).* Santtu types the cue into this chat in normal text mode, Claude replies with one plain paragraph, and Android reads it aloud through the Bluetooth speaker. Voice mode is not used, because it needs the microphone. Menu names vary by phone brand; searching Settings for "text-to-speech" and "Select to Speak" finds them.
   - **Claudette's voice.** In the text-to-speech output settings, use Google's speech engine. From the engine's settings, install the English voice data and preview the voices. Choose a female voice and set the speech rate slightly slow for the tram [112][113].
   - **Select to Speak.** Turn on its shortcut under Accessibility. If it's missing, update the Android Accessibility Suite app from Google Play [112]. Live use: tap the shortcut, then tap Claudette's paragraph. If needed, drag a box over the text and press play [112][114].
   - **Volume.** Check that the accessibility / speech volume, not only the media volume, is turned up and goes to the Bluetooth speaker.
   - **Offline fallback.** Keep this file downloaded on the phone. If the network fails, open it and use Select to Speak on a card's paragraph: same voice, no network needed.
   - **Check four things:**
     - the total delay from typing to speech;
     - whether a full 90-second paragraph is read in one go, including text below the visible screen;
     - how Finnish names sound in the chosen voice;
     - the volume at the far end of the tram.
2. **SOK / Spårakoff.**
   - Ask whether a route plan exists. If yes, send it to Claude and the cards will be re-ordered and trimmed.
   - Ask whether your own speaker is fine alongside their sound system.
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
   | "Santtu's sporascope" | F5a |
   | "Reveal" | Finale |
   | "Test over, reset" | Reset |

4. **Backup.** If the network or voice mode fails, read the cards aloud yourself from this file. Pick the dose by the clock rule in Section 1.
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
| "Stellium" as an astrology term | F5a | |
| Lines 3 and 7 at the Meilahden sairaala terminus | F5a | Verified for 2022–23 only; 2026 service not re-checked |
| Bank of Finland placed in the same horizon wedge | F5a | Not computed; it is about 200 m from the Cathedral, so placed in the same wedge by approximation |
| Physical trams "most likely" not running at 04:05 on a Saturday in 1970 | F5a | Hedged in the script |
| University moved from Turku after the 1827 fire | C17 | |
| Hotel plans for the old Polytechnic | C16 | 2020 source only; worded as "plans" |
| The "corner building totally destroyed" | C16 | Your recollection. Sources name the library wing (Nyström) and the chemistry building (Sjöström) as destroyed and later demolished; the script follows the sources |
| Naming: in 1944 the building was the University of Technology (TKK) | C16 | Helsingin teknillinen opisto moved in after the war |
| Three Smiths legend | C15 | Attested only as local lore; told without any age detail |
| "Torilla tavataan" | Opener | One source says the exact phrase grew out of the 1996 team slogan "Tavataan torilla", with the word order flipped later [96]. The script's "ever since" wording stays accurate |
| About 100,000 people | Opener | Refers to the 1995 homecoming celebration [98], not to every celebration |
| Title number five | Opener | Dated May 2026 [100] |
| Snipers in the National Museum tower | C19 | Your recollection, not found in sources; worded as "some tellings" |
| Bullet fired from the barracks on today's Lasipalatsi site | C19, C11 | Source is Atlas Obscura, a community site [117]; worded as "reportedly" / "is said to" |
| German guns near today's Opera House firing across Töölönlahti | C05 | Historian Samu Nyström in Yle [116] |
| Supreme Court next door since 1934 | C21 | Source is a local photo-blog quoting official text [138] |
| Independence Day reception broadcast live | C21 | General knowledge, not re-checked |
| 1,185 plague dead | C20 | This is the figure on the 1938 gate plaque and in city sources [125][126]. One local historian notes it includes people from outside town, with Helsinki residents numbering about 650. The script uses the official figure |
| Old Church bicentenary | C20 | Consecrated 17 December 1826 [128], so 17 December 2026 is the 200th anniversary (calculated) |
| Red lantern timing | C05 | Most sources give 26 January 1918, 23:00 [121][122]; one notes some sources say 27 January [124]. The script calls it the signal that the revolution had begun, with the uprising itself starting the next evening [122]. That is more precise than "triggered the war" |

**Verified for the new content.**
- Mustelin's own birth time, 16:05, is from his chapter [2]. The 04:05 vs 16:05 twelve-hour "opposition" is calculated.
- 8 November 1942 and 8 November 2026 are both Sundays: the first from sources, the second calculated.
- The Three Smiths were both damaged in 1944 [88][89] and buried in Tikkurila from spring 1944 to spring 1945 [92]. The script reports both.

**Computed for F5a.** Bearings from Naistenklinikka were calculated from the cited coordinates, using two slightly different coordinate sources for the hospital:

| Landmark | Bearing | Distance |
|---|---|---|
| Stadium | 101–104° | 0.9–1.1 km |
| Uspenski | 128–131° | |
| Cathedral | 130–133° | |
| Finlandia Hall | 136–141° | |
| Parliament | 143–147° | |

The weekdays (28 Feb 1970 a Saturday; 6 Dec 2026 a Sunday) were calculated from the calendar.

**Deliberate fiction.** All sporalogy content, the line-number readings for specific trams, and the F4 group reading. Mustelin's own canon points are sourced [1][2][4][5]. Pastiche additions in the same spirit are not his: the paternoster "indoor trams", the "stationary tram", the number-13 arithmetic, and the litigator and mediator aspects.

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
64. User-provided: Verbal input from Santtu Ahonen, 30 October 2026 (event details, route unknown, persona, "political vibes" note, own birthplace and date for F5a)
65. External: HSL, tram 3 terminus moves to Meilahti Hospital (Dec 2022) — https://www.hsl.fi/en/hsl/news/service-updates/2022/12/tram-services-to-return-to-normal-timetables-from-12-december--terminus-of-tram-3-to-move-to-meilahti-hospital
66. External: HSL, tram 7 to Meilahden sairaala (Oct 2023) — https://hsl.fi/en/hsl/news/service-updates/2023/09/trams-to-return-to-pasila-from-2-october--changes-to-tram-routes-1-2-7-and-9
67. External: HUS, Women's Hospital location — https://www.hus.fi/en/node/2402.md
68. External: Fonecta, Naistenklinikka coordinates — https://www.fonecta.fi/profiili/naistenklinikka/724459
69. External: HUS, Haartmaninkatu–Tukholmankatu tram works — https://hus.fi/en/newsroom/traffic-arrangements-will-change-intersection-between-haartmaninkatu-and-tukholmankatu
70. External: MyHelsinki, Helsinki Cathedral coordinates — https://edit.myhelsinki.fi/en/see-and-do/sights/helsinki-cathedral
71. External: Wikipedia, Finlandia Hall coordinates — https://en.wikipedia.org/wiki/Finlandia_Hall
72. External: Yle, Crown Bridges tram line in use 2027 — https://yle.fi/a/74-20147074
73. External: Kaupunginosat.fi, 9 Kolmikulma (bomb of 8.11.1942) — https://kaupunginosat.fi/punavuori/2015/02/26/9-kolmikulma/
74. External: Seura, Helsingin pommitus 8.11.1942 — https://seura.fi/ilmiot/historia/helsingin-pommitus-marraskuussa-1942/
75. External: Seura, child victims and censorship — https://seura.fi/ilmiot/historia/helsingin-pommitus-vaati-lukuisia-lapsiuhreja-marraskuussa-1942/
76. External: Sotiemme perinne, Pääkaupunkiseudun sotavuodet — https://sotiemmeperinne.fi/alueellinen-perinnetyo/etusivu-pks/paikallista-sotahistoriaa-pks/paakaupunkiseudun-sotavuodet/
77. External: Wikipedia, Kolmikulma (Diana Park) — https://en.wikipedia.org/wiki/Kolmikulma
78. External: Wikipedia (fi), Teknillisen korkeakoulun vanha päärakennus — https://fi.wikipedia.org/wiki/Teknillisen_korkeakoulun_vanha_p%C3%A4%C3%A4rakennus
79. External: Walk Helsinki, Huonon onnen koulurakennus — https://walkhelsinki.fi/sotahistoriaa-huonon-onnen-koulurakennus/
80. External: Metropolia building history survey, Vanha kemia — https://docplayer.fi/164992362-Iii-vanha-kemia-metropolia-rakennushistoriaselvitys-helsinki.html
81. External: Inssit satavee, Helsingin teknillinen opisto history — http://inssitsatavee.blogspot.com/2012/07/suomenkielisen-insinoorikoulutuksen.html
82. External: Rakennuslehti 2020, hotel conversion plan — https://www.rakennuslehti.fi/2020/10/metropolian-linna-helsingin-hietalahdessa-muuttuu-hotelliksi-kojamo-haluaa-kortteliin-myos-asuntoja/
83. External: Wikipedia (fi), Helsingin yliopiston päärakennus — https://fi.wikipedia.org/wiki/Helsingin_yliopiston_p%C3%A4%C3%A4rakennus
84. External: Helsinki history, The great raids against Helsinki 1944 — https://historia.hel.fi/en/kaannekohdat/20th-century/the-great-raids-against-helsinki-1944
85. External: Lentoposti, 80 years since the great raids — https://www.lentoposti.fi/uutiset/muistamisten_sarja_helsingiss_helmikuussa_2024_suurpommitusten_kolmen_y_n_ihmeest_jo_80_vuotta
86. External: Reserviläinen, air defence 1944 — https://reservilainen.fi/ilmatorjunta-saavutti-vuoden-1944-torjuntavoitoista-ensimmaisen-lukiolaispoikien-rooli-helsingin-pelastamisessa-oli-tarkea/
87. External: YLE Teema, Helsingin yliopiston tuhoja — https://vintti.yle.fi/yle.fi/sininenlaulu/yle.fi/teema/sininenlaulu/artikkeli.php-id=172.htm
88. External: Wikipedia (fi), Kolmen sepän patsas — https://fi.wikipedia.org/wiki/Kolmen_sep%C3%A4n_patsas
89. External: Wikipedia, Three Smiths Statue — https://en.wikipedia.org/wiki/Three_Smiths_Statue
90. External: HAM, The Three Smiths — https://www.hamhelsinki.fi/?p=2310
91. External: Statues – Hither & Thither, inscription and models — https://vanderkrogt.net/statues/object.php?webpage=ST&record=fi076
92. External: Villa Hakasalmi, Where did the Three Smiths go? — https://hakasalmivilla.fi/?p=1915
93. External: Medical Economics, legend as told by a local — https://www.medicaleconomics.com/view/here-and-there-in-helsinki
94. External: G. Morgan, Three Smiths and Julius Tallberg — https://gmorgan.zenfolio.com/p1023054724/hE87D987
95. External: Claude Help Center, Use voice mode — https://support.claude.com/en/articles/11101966-use-voice-mode
96. External: Kotiliesi, how "Torilla tavataan" was born — https://kotiliesi.fi/ihmiset/nostalgia/nain-lausahdus-torilla-tavataan-syntyi/
97. External: Seura, MM95 celebrations (jersey on Havis Amanda) — https://seura.fi/ilmiot/historia/mm95-nain-laman-kurittama-suomi-juhli-jaakiekon-maailmanmestaruutta/
98. External: Yle 2006, first world title celebrations (about 100,000 people) — https://yle.fi/aihe/artikkeli/2006/09/08/jaakiekon-ensimmainen-mm-kulta-sai-suomalaiset-sekaisin
99. External: Yle Selkouutiset, Torilla tavataan (1995 final vs Sweden) — https://yle.fi/a/3-11489237
100. External: Yle 2026, fifth world title celebrations at Kauppatori — https://yle.fi/a/74-20229025?origin=rss
101. External: Helsingin Uutiset 2026, Havis Amanda protection walls — https://www.helsinginuutiset.fi/paikalliset/9498974
102. External: Wikipedia, Carl Ludvig Engel — https://en.wikipedia.org/wiki/Carl_Ludvig_Engel
103. External: This is Finland, Ehrenström's plan and Engel's 30 buildings — https://finland.fi/?p=3133
104. External: Discover Helsinki, It started as a modest town — https://discoverhelsinki.fi/sightseeing/it-started-as-a-modest-town/amp
105. External: Wikipedia, Johan Albrecht Ehrenström — https://en.wikipedia.org/wiki/Johan_Albrecht_Ehrenstr%C3%B6m
106. External: Wikipedia, Armfelt Conspiracy — https://en.wikipedia.org/wiki/Armfelt_Conspiracy
107. External: Svenskt kvinnobiografiskt lexikon, Magdalena Rudenschöld (1794 pillory) — https://www.skbl.se/en/article/MagdalenaRudenschold
108. External: Helsinki history, The Three Gustavians — https://historia.hel.fi/en/media/kuva/the-three-gustavians-j-f-aminoff-j-a-ehrenstrom-and-g-m-armfelt
109. External: European Film Academy, Senate Square in film — https://www.europeanfilmacademy.org/?p=6790
110. External: Christian Science Monitor 1983, Helsinki as Moscow and Leningrad — https://www.csmonitor.com/1983/0804/080464.html
111. External: Christian Science Monitor 1983, Reds crowd logistics — https://csmonitor.com/1983/0804/080470.html
112. External: Google Android Accessibility Help, Use Select to Speak — https://support.google.com/accessibility/android/answer/7349565?hl=en
113. External: Android Police / Yahoo Tech, Google text-to-speech setup — https://tech.yahoo.com/phones/articles/googles-text-speech-accessibility-feature-230110337.html
114. External: AbilityNet, Select to Speak in Android — https://mcmw.abilitynet.org.uk/how-to-read-selected-text-aloud-using-select-to-speak-in-android-12
115. External: Wikipedia (fi), Helsingin valtaus (1918) — https://fi.wikipedia.org/wiki/Helsingin_valtaus
116. External: Yle 2018, Germans captured Helsinki (Samu Nyström) — https://yle.fi/a/3-10133164
117. External: Atlas Obscura, Bullet Holes in the National Museum of Finland — https://assets.atlasobscura.com/places/bullet-holes-in-the-the-national-museum-of-finland
118. External: Wikipedia, National Museum of Finland — https://en.wikipedia.org/wiki/National_Museum_of_Finland
119. External: National Museum of Finland, history — https://www.kansallismuseo.fi/en/kansallismuseo/historiaa
120. External: Walk Helsinki, Helsingin valtaus 1918 — https://walkhelsinki.fi/helsingin-valtaus-1918/
121. External: Wikipedia (fi), Suomen sisällissota — https://fi.wikipedia.org/wiki/Suomen_sis%C3%A4llissota
122. External: Itsenäisyys.fi, Kun vallankumouksen merkkilyhty syttyi — https://xn--itsenisyys-u5a.fi/kun-vallankumouksen-merkkilyhty-syttyi/
123. External: Reservin Sanomat, Paasitorni 1918 exhibition (tower fire, surrender 13.4.) — https://reservinsanomat.fi/talot-vieraissa-kasissa-valokuvanayttely/
124. External: Kansan Uutiset 2018, Punainen lyhty syttyi työväentalon tornissa — https://www.ku.fi/artikkeli/3840601-punainen-lyhty-syttyi-tyovaentalon-tornissa-sata-vuotta-sitten
125. External: Vihreät sylit (City of Helsinki), Old Church Park — https://vihreatsylit.fi/en/vanha-kirkkopuisto/
126. External: Wikipedia (fi), Vanha kirkkopuisto — https://fi.wikipedia.org/wiki/Vanha_kirkkopuisto
127. External: Helsingin seurakunnat, Vanha kirkko henkii historiaa — https://www.helsinginseurakunnat.fi/sisaltokeskus/pgk2uyvaz.html.stx
128. External: Wikipedia, Helsinki Old Church — https://en.wikipedia.org/wiki/Helsinki_Old_Church
129. External: City of Helsinki, Tarinoiden Helsinki: Ruttopuisto (PDF) — https://www.hel.fi/hel2/Tietokeskus/julkaisut/pdf/tarinoidenhelsinki_9_ruttopuisto.pdf
130. External: Seura, Rutto riehui Helsingissä — https://seura.fi/ilmiot/historia/rutto-riehui-helsingissa-tappoi-ihmisia-hyttysia-keita-kuolleet/
131. External: Finland's House of Nobility, About — https://riddarhuset.fi/en/about_us
132. External: Wikipedia, Georg Theodor Chiewitz — https://wikipedia.com/wiki/G.T._Chiewitz
133. External: MyHelsinki, House of Nobility (coats of arms) — https://edit.myhelsinki.fi/de/node/59762
134. External: Wikipedia, Presidential Palace, Helsinki — https://en.wikipedia.org/wiki/Presidential_Palace,_Helsinki
135. External: Office of the President, Presidential Palace brochure (PDF) — https://www.presidentti.fi/niinisto/wp-content/uploads/sites/3/2019/11/Presidentinlinna_esite_EN.pdf
136. External: Office of the President, renovation complete (designated 1921) — https://www.presidentti.fi/en/news/presidential-palace-renovation-complete
137. External: MyHelsinki, Engel's Helsinki walk (palace in Katajanokka idea) — https://edit.myhelsinki.fi/de/node/27644
138. External: Lux Helsinki photo-blog (Supreme Court, Pohjoisesplanadi 3) — https://sarihoo.kapsi.fi/2017_LuxHelsinki/lux.html
139. External: Wikipedia, Helsinki County Prison — https://en.wikipedia.org/wiki/Helsinki_County_Prison
140. External: Lonely Planet, hotels that were prisons — https://www.lonelyplanet.com/travel-tips-and-articles/these-10-hotels-and-hostels-were-prisons-in-a-former-life/40625c8c-8a11-5710-a052-1479d2750cc0
141. External: Strawberry, Hotel Katajanokka history — https://strawberryhotels.com/hotels/finland/helsinki/clarion-collection-hotel-katajanokka/about
142. External: Wikipedia, Katajanokka Terminal — https://en.wikipedia.org/wiki/Katajanokka_Terminal
143. External: Wikipedia, Port of Helsinki (Tallinn route 2025) — https://en.wikipedia.org/wiki/Port_of_Helsinki
144. External: Port of Helsinki, sights near Katajanokka Terminal — https://www.portofhelsinki.fi/en/about-us/port-of-helsinki/whats-new/sights-near-the-west-harbour-and-katajanokka-terminaltesting/
145. External: Government of Åland, Åland protocol and VAT area (PDF) — https://regeringen.ax/sites/default/files/attachments/protocol/nr30-2024-enskild-f1.pdf
146. External: Wikipedia, Långnäs (tax-free stop since 1 July 1999) — https://en.wikipedia.org/wiki/L%C3%A5ngn%C3%A4s

---

## Version History

| Version | Date | Author(s) | Changes |
|---------|------|-----------|---------|
| v0.1 | 30 October 2026 | Santtu Ahonen | Initial draft — generated with Claude AI |
| v0.2 | 30 October 2026 | Santtu Ahonen | Added F5a sporascope (Santtu) |
| v0.3 | 30 October 2026 | Santtu Ahonen | Added C14–C17; birth time in F5a |
| v0.4 | 30 October 2026 | Santtu Ahonen | Added Claudette persona |
| v0.5 | 30 October 2026 | Santtu Ahonen | Hockey tradition and 1995 memory in opener |
| v0.6 | 30 October 2026 | Santtu Ahonen | Added C18 Engel and Ehrenström |
| v0.7 | 30 October 2026 | Santtu Ahonen | Start/reset commands, dry-run sequence |
| v0.8 | 30 October 2026 | Santtu Ahonen | Typed cues, phone TTS, no microphone |
| v0.9 | 30 October 2026 | Santtu Ahonen | Route awareness, neighbour map |
| v0.10 | 30 October 2026 | Santtu Ahonen | Android read-aloud setup |
| v0.11 | 30 October 2026 | Santtu Ahonen | Stockmann clock, 1918 additions, C19, F7 |
| v0.12 | 30 October 2026 | Santtu Ahonen | Removed joke-explaining tags |
| v0.13 | 30 October 2026 | Santtu Ahonen | Red lantern in C05; C05 doses neutralised |
| v0.14 | 30 October 2026 | Santtu Ahonen | C20 Ruttopuisto; new schedule 17:30–19:30, reveal at Havis Amanda |
| v0.15 | 30 October 2026 | Santtu Ahonen | C20 wedding line |
| v0.16 | 30 October 2026 | Santtu Ahonen | C21–C22 Katajanokka in and out |
| v0.17 | 30 October 2026 | Santtu Ahonen | Speaker-notes mode; Claudette retired |
| v0.18 | 30 October 2026 | Santtu Ahonen | Passenger-card hook in protocol |
| v0.19 | 30 October 2026 | Santtu Ahonen | Flexible reveal; post-reveal mode; close split out |

---

*Generated with Claude AI (qt-document-annotation v2026.06.26.01) — validate all figures before use.*
