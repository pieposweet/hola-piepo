# Spanish Flashcard System — Setup Prompt

Copy everything below the line and paste it to your AI assistant. It will build the same Spanish learning system.

---

I want to build a Spanish flashcard learning system for daily life. I live in [CITY, COUNTRY] and I'm learning Spanish for everyday situations — ordering food, taxis, markets, neighbors — not classroom material. Explain grammar in English when it gets hard.

## The system: four decks + one master app

Build four separate flashcard decks, then combine them into one master application with tab navigation between decks.

### 1. Phrase deck ("Spanish Phrases Flashcards")
- Tap-to-flip cards: Spanish on the front; English translation, pronunciation guide, and usage note on the back.
- Organize cards into named stacks (categories), e.g. Greetings, Food, Market & Shopping, Grammar, Daily Life, Thank You, Household.
- Shuffle mode, category filtering, and progress tracking.
- "Got it" marks a card learned: remove it from the active rotation but keep it counted in progress; "Again" keeps it in rotation. A reset restores all cards.
- Add-your-own-card flow (Spanish, English, pronunciation, note, category), plus edit and delete for custom cards.
- Spanish audio on every card: Listen button with normal and slower playback (Mexican Spanish). New cards get audio automatically.
- Layout: the Listen & Repeat audio controls go BELOW the Back / Again / Got It buttons.

### 2. Verb deck ("Spanish Verb Conjugations") — the 100 most common Spanish verbs
- Infinitive on the front; complete six-person present, preterite (past), and future conjugation tables on the back.
- Shuffle, Again / Got it progress, learned-card removal, reset, and filtering by conjugation pattern (regular, stem-changing, spelling-changing, irregular).
- Same audio and button layout as the phrase deck.

### 3. Adjective deck ("Spanish Adjectives") — the 100 most common Spanish adjectives
- Adjective on the front; masculine / feminine / plural forms, English meaning, pronunciation, and bilingual example usage on the back.
- Category filtering, shuffle, progress tracking, add / edit / delete, audio, same button layout.

### 4. Noun deck ("Spanish Nouns") — the 500 most common Spanish nouns
- Noun on the front; article (el/la), grammatical gender, plural form, English meaning, and a Spanish example sentence with English translation on the back.
- Topic and gender filters, searchable index, shuffle, progress tracking, add / edit / delete, audio, same button layout.

### 5. Master deck ("Spanish Master Deck")
- One application combining all four decks with tab navigation and a shared design language. Every card from every deck, all features above working.

## Cross-linking (important)
- Words link across decks: tapping a verb in a phrase card opens its conjugation card. Match conjugated forms too, not just infinitives (e.g. "tengas" → "tener").
- Tapping a noun or adjective in any card opens its entry in the noun / adjective deck.
- Related-word links within decks where natural (e.g. related adjectives, related nouns).

## Ongoing workflow
- When I send photos of Spanish vocabulary or phrases, parse them and add each item to the matching deck: phrases and full sentences → phrase deck (under a sensible stack); verbs → verb deck; adjectives → adjective deck; nouns → noun deck. Never put single vocabulary words into the phrase deck.
- Deduplicate against existing cards before adding. Skip exact duplicates.
- After each batch, report: how many cards added per deck/stack, how many skipped as duplicates, and anything unreadable.
- Every new card gets pronunciation audio automatically.

## Standing targets
- 100 most common verbs, 500 most common nouns, 100 most common adjectives.
- Beyond those, new vocabulary comes from my own daily life via the add-your-own-card flow — that's the main way the system keeps growing.
