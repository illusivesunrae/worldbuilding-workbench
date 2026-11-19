# Worldbuilding Workbench

The goal of this project is to learn and experiment with Python. The app is aimed at people looking to document their worldbuilding, but want help with language building. It will allow users to design parameters around a language engine, which can then be used to feed into their lore entries as they write them.

The initial application will be divided into three main parts:

- setting up a language engine where users can select and combine different preset (for now) language and media archetypes as influences (ex. Russian + Gothic Horror)
- generating lists of candidate words and names
- writing lore entries with live glossary auto-linking

I have a tendency to bite off more than I can chew when it comes to personal projects and time management, so keeping the scope limited at first will hopefully enable me to stick with it and iterate on this over time.

## Roadmap

### CLI Core

**Milestone:** Syllable and word generator

When completed, I will be able to:

- define consonants, vowels, and syllable patterns in a Python script
- generate 20 pronounceable words in your terminal

Python concepts I will learn:

- lists
- dicts
- functions
- random.choices
- re (regex)

### Influence Engine

**Milestone:** Preset Profiles & Affixes

When completed, I will be able to:

- pick 1–2 linguistic/genre influences
- blend sound profiles
- attach prefixes/suffixes (e.g., -heim, -ov, mal-) with meanings

Python concepts I will learn:

- JSON/YAML file I/O
- data merging
- string formatting

### Web API & DB

**Milestone:** Lexicon & Lore Storage

When completed, I will be able to:

- run a local web app
- save favorite generated words to a dictionary
- attach words to Cultures and Lore entries.

Python concepts I will learn:

- FastAPI
- sqlite3
- Pydantic data models
- REST endpoints

### Smart Parser

**Milestone:** Auto-Linking & Sound Shifts

When completed, I will be able to:

- Write a TTRPG session note or story scene and watch your invented terms auto-highlight with their etymology and translations.

Python concepts I will learn:

- text processing
- rule pipelines
- Markdown rendering