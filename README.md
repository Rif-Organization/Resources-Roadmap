# Resources-Roadmap

All the Tarifit related resources that will be aggregated for AI and software projects.

## Target Projects

- **Tarifit Learning App** - Language learning application for Tarifit
- **Translation Model** - Machine translation model for Tarifit ↔ other languages

---

## Resource Collection Checklist

### Text & Parallel Corpus Data

- [ ] Tarifit-English parallel sentences
- [ ] Tarifit-Arabic parallel sentences
- [ ] Tarifit-French parallel sentences
- [ ] Tarifit-Dutch parallel sentences
- [ ] Monolingual Tarifit text corpus
- [ ] Tarifit proverbs and sayings collection
- [ ] Tarifit folk tales and stories
- [ ] Tarifit poetry and songs lyrics
- [ ] Religious texts in Tarifit
- [ ] Tarifit news articles and publications

### Dictionary & Lexicon Resources

- [ ] Tarifit-English dictionary entries
- [ ] Tarifit-Arabic dictionary entries
- [ ] Tarifit-French dictionary entries
- [ ] Tarifit word frequency list
- [ ] Tarifit verb conjugation tables
- [ ] Tarifit noun declension tables
- [ ] Tarifit common phrases and expressions

### Audio & Speech Data

- [ ] Native speaker audio recordings
- [ ] Tarifit pronunciation guides
- [ ] Tarifit audio-text aligned corpus
- [ ] Tarifit speech transcriptions
- [ ] Regional dialect audio samples

### Grammar & Linguistic Resources

- [ ] Tarifit grammar rules documentation
- [ ] Tarifit alphabet and writing system (Tifinagh, Latin, Arabic scripts)
- [ ] Tarifit phonology documentation
- [ ] Tarifit morphology rules
- [ ] Tarifit syntax patterns

### Learning App Specific Resources

- [ ] Vocabulary lists by category (greetings, numbers, colors, etc.)
- [ ] Common conversation dialogues
- [ ] Grammar exercises and quizzes
- [ ] Flashcard content (word-image pairs)
- [ ] Spaced repetition word lists
- [ ] Difficulty-graded reading passages
- [ ] Interactive lesson content

### Translation Model Specific Resources

- [ ] Sentence-aligned parallel corpus (goal: 50K+ pairs for quality results)
- [ ] Domain-specific terminology (medical, legal, technical)
- [ ] Named entity lists (places, names)
- [ ] Bilingual terminology glossaries
- [ ] Translation memory files (TMX format)
- [ ] Quality-validated translation samples

---

## Data Formats

Resources should be compiled into the following formats for AI and software usability:

| Resource Type | Recommended Format | Description |
|---------------|-------------------|-------------|
| Parallel corpus | `.tsv`, `.csv`, `.jsonl` | Tab/comma separated or JSON lines with source-target pairs |
| Dictionary | `.json`, `.sqlite` | Structured key-value pairs with metadata |
| Audio | `.wav`, `.mp3` | With corresponding transcription files |
| Grammar rules | `.md`, `.yaml` | Human-readable with structured data |
| Vocabulary lists | `.json`, `.csv` | Categorized word lists with translations |
| Flashcards | `.json`, `.apkg` | Custom JSON or `.apkg` (Anki deck export format) |

---

## Resource Status Legend

- [ ] Not started / Not collected
- [x] Collected and formatted
- 🔄 In progress
- ⚠️ Needs review/verification

---

## Contributing

To contribute resources:
1. Ensure content is properly licensed or in the public domain
2. Format data according to the specifications above
3. Include metadata about source and quality
4. Submit via pull request with description of the resource

---

## Notes

- Priority focus: Building parallel corpus for translation model
- Secondary focus: Vocabulary and audio for learning app
- All data should be normalized to UTF-8 encoding
- Tifinagh script content should also include Latin transliteration
