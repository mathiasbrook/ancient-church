# Ancient Church

> 🚧 **Work in progress.** I'm in the planning stage right now. There's no app code in this repo yet; it goes up here as I build it (starting December 2026).

Ancient Church puts the Bible, the writings of the Church Fathers, and the canons and councils of the Oriental Orthodox Church in one place, with an AI assistant that answers questions using only those sources.

## Who it's for
Members of all the Oriental Orthodox churches (Coptic, Ethiopian, Eritrean, Armenian, Syriac, and Indian (Malankara) Orthodox), plus anyone curious about the faith.

People often have questions about the faith but have to wait until they can ask a priest or scholar to get a reliable answer. This app lets them read the original sources and ask an AI that answers only from approved Church sources, shows where every answer came from, and reminds them to confirm important things with their priest.

## Planned features
- **Four reading sections:** Bible, Church Fathers, canons, and councils, with book and chapter navigation
- **AI questions:** searches the app's own source library and answers only from it, with a citation for every answer. If the sources don't cover a question, it says so instead of guessing
- A reminder that the AI doesn't replace asking a priest
- Search and bookmarks
- Website first, then an iPhone and Android app

Starting sources are public-domain texts, like the Brenton English Septuagint, the writings of St. Athanasius, St. Cyril of Alexandria, St. Ephrem the Syrian and St. Severus of Antioch, and the canons of the councils of Nicaea, Constantinople and Ephesus.

## Planned tech stack
| Part | Plan |
|---|---|
| Website | Built first so priests and friends can test it from a link (framework picked in November) |
| Phone app | Turn the website into an iPhone/Android app with React Native / Expo |
| Database | Stores the source texts (picked in November) |
| AI service | Answers only from the app's source library and cites the source it used |
| Hosting | Free tier to start |

## Current status
**Planning (November 2026 milestone):** choosing the tools, collecting the public-domain texts, checking the sources are accepted across the Oriental Orthodox churches, and sketching every screen.

## Roadmap
| Month | Goal |
|---|---|
| Nov 2026 | Plan and gather sources: source list and sketches of every screen |
| Dec 2026 | Reading website for the Bible and Church Fathers |
| Jan 2027 | AI question section: first demo answering with sources, 25 test questions |
| Feb 2027 | Canons and councils sections, search, bookmarks; first test with 2–3 priests and 5–10 friends |
| Mar 2027 | Fixes, wider priest review across the Oriental Orthodox churches, start the phone app |
| Apr 2027 | Final fixes, finish the phone app, submit to the App Store and Google Play |
| Early May 2027 | Public launch of the website and phone app |

Before release, priests review the AI's answers in two rounds. The goal is at least 90% of test answers marked correct, and no answer ever given without a source.

The full plan (testing, costs, risks) is in [docs/project-plan.md](docs/project-plan.md).

## License
[MIT](LICENSE)
