# VEMC Vocabulary Trainer 📖

> *Made for pushing through the grind of vocabulary learning without mercy.*

A fast, highly aesthetic, local-first flashcard application designed to rapidly build English vocabulary. Designed primarily for test prep (IELTS, GRE, SAT, BCS) and language learners, VEMC provides a distraction-free dark mode environment loaded with features that automate the heavy lifting of language acquisition.

## 🌟 Key Features

- **Automated Dictionary Lookup:** Automatically fetches definitions, phonetics, audio pronunciations, synonyms, sentences, and parts of speech using the [Free Dictionary API](https://dictionaryapi.dev/).
- **Instant Bengali Translation:** Seamlessly integrates with Google Translate to provide accurate Bengali meanings with multiple contextual alternatives.
- **Accurate Synonyms:** Pulls high-quality, context-aware synonyms from Google Translate's synonym corpus, prioritized by part of speech and relevance.
- **Contextual Example Sentences:** Displays up to 3 real-world example sentences with the target vocabulary word **highlighted in gold**. Sources examples from both dictionary entries and Google Translate's sentence corpus, with smart fallbacks.
- **Advanced Sorting & Ordering:**
  - **Shuffle** (default) — randomized order every session
  - **A → Z / Z → A** — alphabetical sorting
  - **By Alphabet** — filter words by specific starting letter with an interactive A–Z grid
- **Smart Filtering & Search:** Filter your database by "Known", "Still Learning", or "Unseen" words. Features an instant text search to locate words immediately.
- **Offline Resilience & Caching:** Once a word definition is fetched, it is cached permanently into your browser's `localStorage` ensuring blazing-fast loads and offline capability.
- **Exam Mode & Analytics:** Challenge yourself with time-attack practice exams. Every attempt is scored and recorded. View historical metrics via beautiful line charts to track improvements.
- **Data Safety Management:** Your data stays perfectly safe on your machine with a native pop-up flow to clear specific histories or restart the trainer.

## ⌨️ Keyboard Shortcuts

Speed up your learning by never touching the mouse:

* `<Space>` : Flip the flashcard
* `←` / `→` : Navigate to the previous or next word
* `K` : Mark current word as **Known**
* `L` : Mark current word as **Still Learning**

## 🚀 Getting Started

Since VEMC relies entirely on frontend web technologies and LocalStorage, there is zero setup required.

1. Clone or download the repository to your machine.
2. Double-click `index.html` to open it in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Start learning instantly!

## 🛠️ Technology Stack

* **Front-end:** Vanilla HTML5, CSS3, JavaScript (ES6+).
* **APIs:** [Free Dictionary API](https://dictionaryapi.dev/), Google Translate API (translation, synonyms, examples).
* **Storage:** Native Browser `localStorage`.
* **Libraries:** None. 100% dependency-free processing and charting algorithms.

---

Created by **Sakib Nawar Tanmoy** •  [GitHub](https://github.com/sakibntanmoy006) | [LinkedIn](https://www.linkedin.com/in/snt006/)
