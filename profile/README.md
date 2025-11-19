<p align="center">
  <img src="https://github.com/user-attachments/assets/ecbe377c-cec0-41a5-a5d8-df406de9f261" alt="Kardenwort Logo" width="300">
</p>

# The Kardenwort Philosophy

> *Kontext. Kern. Karte.* (Context. Core. Card.)

The name **Kardenwort** evokes "carding"—the process of combing and straightening tangled fibers. In the same way, our toolkit processes raw, complex texts, meticulously organizing them into simple, clear, and context-rich vocabulary lists for language learners.

This philosophy is deeply inspired by Rich Hickey's influential talk, "Simple Made Easy." Kardenwort embodies the principle that achieving simplicity is hard work. The tool undertakes the difficult task of parsing linguistic complexity to produce a result that is truly simple: an untangled, organized list. This foundational simplicity, in turn, makes the process of creating cards and learning vocabulary easy for the end-user.

Our approach is built on a simple but powerful mantra: **Kontext. Kern. Karte.**
*   **Kontext (Context):** Words cannot be learned in a vacuum. Kardenwort ensures that every vocabulary item retains its original sentence and surrounding phrases, allowing you to understand usage, nuance, and grammar naturally.
*   **Kern (Core):** Our engine drills down to find the lexical kernel (the lemma or base form) of every word. It intelligently handles complex grammar to give you the most accurate and useful information.
*   **Karte (Card):** The final output is a perfectly structured dataset, ready to become a rich learning card in Anki or a clear list in GoldenDict. It's not just a word; it's a data-filled canvas for learning.

All you need is Plain Text in the AI era.

---

## Start Here: The Assembly Point

Ready to dive in? The Kardenwort ecosystem is a collection of tools that work together. The best place to begin is with the main application, which serves as the central assembly point and contains detailed instructions for setting up the entire workflow.

**Go to the Kardenwort Core Engine Repository:** **[20250913122858-kardenwort](https://github.com/kardenwort/20250913122858-kardenwort)**

The `README.md` file in that repository provides a complete, step-by-step guide to clone all necessary projects, set up your environment, and run your first text analysis. It's the "main" function of our entire project.

---

## Map of Contents
*   [Start Here: The Assembly Point](#start-here-the-assembly-point)
*   [A Personal Journey: The "Why"](#a-personal-journey-the-why)
*   [Core Philosophy: Our Approach to Language Learning](#core-philosophy-our-approach-to-language-learning)
    *   [Guiding Principles](#guiding-principles)
    *   [The Primacy of the Word](#the-primacy-of-the-word)
    *   [Taming Complexity: Why German Needs Deconstruction](#taming-complexity-why-german-needs-deconstruction)
    *   ["Simple as a Stump": The Core Principle](#simple-as-a-stump-the-core-principle)
    *   [Inspired by Zettelkasten: Structured Knowledge](#inspired-by-zettelkasten-structured-knowledge)
*   [Key Advantages of the Kardenwort Method](#key-advantages-of-the-kardenwort-method)
    *   [Reducing Cognitive Load: Separating Reading from Studying](#reducing-cognitive-load-separating-reading-from-studying)
    *   [Freedom from "Readers": Working with Original Media](#freedom-from-readers-working-with-original-media)
    *   [Quality You Control: The Trainable System](#quality-you-control-the-trainable-system)
    *   [Why Anki is the Right Tool](#why-anki-is-the-right-tool)
    *   [Offline First: Your Data, Your Rules](#offline-first-your-data-your-rules)
*   [Who Can Benefit?](#who-can-benefit)
    *   [Aiding Focus for Users with ADHD and Disabilities](#aiding-focus-for-users-with-adhd-and-disabilities)
    *   [For Learners of All Styles](#for-learners-of-all-styles)
*   [The Vision: A Bridge Between Cultures](#the-vision-a-bridge-between-cultures)
*   [Our Ecosystem](#our-ecosystem)
*   [Development Repositories](#development-repositories)
*   [Kardenwort Ecosystem](#kardenwort-ecosystem)
*   [License & Creator](#license--creator)

---

## A Personal Journey: The "Why"

Several years ago, I faced the most significant challenge of my life: my first serious attempt to learn a foreign language, German, while living abroad. It was incredibly difficult. With a 12-year background as a systems administrator and the last 7 years deeply involved in software development, I turned to the tools I knew best. I created Anki templates, manually entered thousands of words using tools like VocabSieve, and delved into sentence mining.

This journey led me to a simple truth: everything is the word, and context is everything. It became clear that different skills must be trained in separate sessions, and consistency is paramount. I realized that a solid grasp of grammar is a powerful accelerator. I created a set of five tables that map the entire German grammar up to the C1 level, which I use as my guide. This process ignited a lasting interest in computational linguistics, right as the AI boom began. I passed my German B1 exam.

Throughout this time, I observed my colleagues' struggles and tried to address them in my tools. I arrived at the conclusion that the most effective methods have been known for a long time. The most reliable things are simple. The key is to reduce cognitive load wherever it isn't the primary goal of the activity.

My first native language is Russian, my second is Ukrainian. I am learning German for life in Germany and English for my work in IT. This multicultural experience fuels my motivation. I strive to make this utility accessible to a broad audience, to be able to share it with a colleague and explain the approach, to help someone facing the same life circumstances many of us find ourselves in today. I believe in mutual prosperity; if everyone in society thrives, so do I. Together, we can lift each other up towards a brighter future.

[Return to Top](#map-of-contents)

---

## Core Philosophy: Our Approach to Language Learning

We are building not just tools, but a philosophy—a set of high-level concepts for language acquisition that prioritizes clarity, efficiency, and learner autonomy.

### Guiding Principles
Our philosophy is supported by three core principles:
1.  **Openness and Free Access:** This is an open-source development that can be used anywhere without restrictions, fostering a community of learners and developers.
2.  **Your Data in Your Hands:** The project does not require registration or subscriptions. You are not dependent on third-party services that might one day charge a fee for access to the very cards you spent hours creating.
3.  **Maximum Flexibility:** The output of the utility is a starting point, not a rigid system. You get full control over your learning materials to adapt them to your personal needs.

### The Primacy of the Word
First, there was the word. Words are the fundamental building blocks of language. You can combine them in countless ways, and even without perfect grammar, a strong vocabulary allows you to communicate. Acquiring words is the most challenging and time-consuming part of learning a language; it requires constant, sustained effort. This program is dedicated to improving comprehension by breaking down language to its core component: the word. Understanding words in their varied contexts is the essential first step before we can effectively produce speech.

### Taming Complexity: Why German Needs Deconstruction
German is largely a synthetic language, meaning it relies heavily on inflections (changes in word endings) and compounding (joining words together) to convey grammatical relationships. This contrasts with analytic languages like English, which use word order and helper words. This synthetic nature is why a single German word can be so intimidating and hard to find in a dictionary.

The real challenge isn't looking up a translation; it's correctly deconstructing an inflected or compound word to find its base form (lemma). Kardenwort was created specifically to fight this complexity. It automates the process of decomposition, allowing you to understand any text by breaking it down into its constituent parts.

### "Simple as a Stump": The Core Principle
This Russian aphorism ("простой как пень") captures our core design principle. The tools and methods must be incredibly simple to integrate into a regular study routine. They should not add extra cognitive load to the primary task: analyzing foreign language material. The idea is to set it up once and then just use it. This approach is as fundamental as annotating words in the margins of a physical book—a practice Kardenwort digitizes and automates.

### Inspired by Zettelkasten: Structured Knowledge
I am a firm believer in the Zettelkasten method, which uses unique identifiers (ZID) to link notes. This inspiration is reflected in our workflow: Kardenwort generates a unique, timestamp-based ID for each export. This ZID is used as the filename and the Anki deck name, creating a clear link between a specific text and the vocabulary derived from it.

[Return to Top](#map-of-contents)

---

## Key Advantages of the Kardenwort Method

### Reducing Cognitive Load: Separating Reading from Studying
Our process deliberately separates the act of reading from the act of vocabulary acquisition. When you read, you can fully immerse yourself in the material without constantly stopping to look up words and create flashcards. Later, in a dedicated session, you can efficiently work through the pre-processed, context-rich vocabulary list. This division of labor makes both activities more focused and effective.

### Freedom from "Readers": Working with Original Media
Many language learning apps, unlike many dedicated reading applications (such as LWT, Lute, VocabSieve, LinguaCafe, alexandria-reader, LingQ, Readlang, LanguageCrush, lemmatize, Smart Book - KursX, KOReader, and others), are e-readers that work well for novels but fail with complex, non-linear content. Technical books, academic papers, and articles are filled with essential diagrams, code snippets, formulas, and footnotes. E-readers strip this context away.

Kardenwort acts as a **companion** to your original source material, not a replacement. You can read from a physical book, a PDF, or any other source. Our tool decouples the vocabulary work from the medium, allowing you to preserve the full, rich context of the original. The ZID ensures you can always trace your vocabulary back to the source text.

### Quality You Control: The Trainable System
The accuracy of NLP analysis is a compromise. Kardenwort bridges this gap by giving you direct control. Through a simple rules file (`lemma_override.tsv`), you can "train" the system by providing corrections for your specific texts. Once a rule is added, it is saved forever and automatically reapplied in the future. This allows you to achieve perfect processing for your materials without repeating work.

### Why Anki is the Right Tool
While other platforms exist, Anki is superior for serious learners for several key reasons:
*   **Full Control & Customization:** You control every aspect of your cards and study algorithm.
*   **Offline First:** Your data is yours. It lives on your machine, accessible anytime, anywhere.
*   **Open Ecosystem:** A massive community provides add-ons to tailor your workflow.
*   **Overcoming Complexity:** Anki's initial learning curve can be steep. Our pre-configured `20250913123501-kardenwort-anki-templates` project eliminates this barrier, providing a powerful, ready-to-use template out of the box.

Decks themselves are cheap to create and ultimately disposable. Like equipment at a gym, they are tools to build strength. The knowledge should end up in your head, not locked in a proprietary system.

### Offline First: Your Data, Your Rules
Kardenwort is completely independent of the internet and resource-hungry AI models.
*   **Privacy:** You are not sending your data to any third-party service for processing or to train their models. No one knows what you are reading. This is crucial when working with copyrighted, confidential, or sensitive materials.
*   **Reliability:** It delivers consistent, high-quality results without relying on a network connection or powerful hardware.

*(Note: While Kardenwort itself is offline, your data will be sent to Anki's servers if you choose to use their synchronization service.)*

[Return to Top](#map-of-contents)

---

## Who Can Benefit?

### Aiding Focus for Users with ADHD and Disabilities
The modern world is filled with distractions. Language learning apps often compound this with complex interfaces and notifications. Kardenwort offers a focused, streamlined alternative to distracting apps:
*   **Measurable Progress:** Learning is broken down into small, manageable steps—one card at a time—providing a clear sense of accomplishment.
*   **Gamified Feedback Loop:** The process of finding a complex word and "catching" it by adding a rule to your override file is highly engaging, creating a positive feedback loop.
*   **Distraction-Free Environment:** Work offline, away from the noise of the internet. You can even print your decks and study on paper.
*   **Set It and Forget It:** The system is designed to be configured once. You spend your time learning, not fiddling with settings in a complicated UI.
*   **Auditory-Centered Learning:** We learn living languages. The cards are built around audio to prepare you for producing and understanding real speech. This also enhances reading comprehension, even when reading silently.

### For Learners of All Styles
*   **The Autonomous Learner:** Learn on your own terms. Use AI to generate texts on topics you love, then use Kardenwort to extract the vocabulary. Explore the same topic from multiple angles to build a rich, multi-faceted vocabulary.
*   **The Methodical Learner:** Our approach is similar to the time-tested **Grammar-Translation Method**. It provides a solid foundation, especially at the beginner stages, and can be integrated into any other methodology, including the popular communicative approach.

[Return to Top](#map-of-contents)

---

## The Vision: A Bridge Between Cultures
Currently, Kardenwort fully supports **English (en)** and **German (de)**. We plan to expand support to include **Russian (ru)** and **Ukrainian (uk)**. Our goal is to foster linguistic exchange, helping people from different cultures understand each other better, live together happily, and build a brighter, more developed future.

[Return to Top](#map-of-contents)

---

## Our Ecosystem

Kardenwort is a suite of integrated tools designed to work together seamlessly:

*   **Kardenwort (Core Engine):** [**20250913122858-kardenwort**](https://github.com/kardenwort/20250913122858-kardenwort)
    *   The core intelligent engine for text processing and vocabulary extraction.
*   **Anki CSV Importer:** [**20250913123240-kardenwort-anki-csv-importer**](https://github.com/kardenwort/20250913123240-kardenwort-anki-csv-importer)
    *   The bridge that automatically imports the generated vocabulary files into Anki.
*   **Anki Templates:** [**20250913123501-kardenwort-anki-templates**](https://github.com/kardenwort/20250913123501-kardenwort-anki-templates)
    *   The powerful and feature-rich Anki card template that brings your vocabulary to life.
*   **AnkiConnect Fork:** [**20251110002755-kardenwort-ankiconnect**](https://github.com/voothi/20251110002755-kardenwort-ankiconnect)
    *   This is a custom build of the official AnkiConnect add-on, extended with a new API action to enable deeper integration with external tools, specifically the Kardenwort language learning ecosystem.

## Development Repositories

For those who want the latest features, bug fixes, or wish to explore the development history, we maintain a set of active development repositories. Code is periodically merged from these repos into the stable public ones listed above.

*   **Kardenwort (Core Engine):** [**20241223170748-kardenwort**](https://github.com/voothi/20241223170748-kardenwort)
*   **Anki CSV Importer:** [**20250401192017-kardenwort-anki-csv-importer**](https://github.com/voothi/20250401192017-kardenwort-anki-csv-importer)
*   **Anki Templates:** [**20241106211123-kardenwort-anki-templates**](https://github.com/voothi/20241106211123-kardenwort-anki-templates)
*   **AnkiConnect Fork:** [**20251110002755-kardenwort-ankiconnect**](https://github.com/voothi/20251110002755-kardenwort-ankiconnect)

**Related Repositories in Development:**
*   **AutoHotkey Scripts:** [**20240411110510-autohotkey**](https://github.com/voothi/20240411110510-autohotkey)

[Return to Top](#map-of-contents)

## Kardenwort Ecosystem

This project is part of the **[Kardenwort](https://github.com/kardenwort)** environment, designed to create a focused and efficient learning ecosystem.

[Return to Top](#map-of-contents)

---

## License & Creator

This project was created by and is maintained by **Denis Novikov (voothi)**.

It is licensed under the **MIT License**. See the `LICENSE` file in the project repository for full details.

[Return to Top](#map-of-contents)
