# Ancient Church: Project Plan

Oct 26, 2026

## Project overview
Ancient Church is an app that puts the Bible, the writings of the Church Fathers, and the canons and councils of the Oriental Orthodox Church in one place, with an AI assistant that answers questions using those sources.

- **Who it is for:** members of all Oriental Orthodox churches (Coptic, Ethiopian, Eritrean, Armenian, Syriac, and Indian (Malankara) Orthodox), plus anyone curious about the faith.
- **The problem:** people often have questions about the faith but have to wait until they can ask a priest or scholar to get a reliable answer.
- **The solution:** an app where they can read the original sources and ask an AI that answers only from approved Church sources, shows where each answer came from, and reminds users to confirm important matters with their priest.

The app will be released to the public in early May 2027.

## Goal and approach
The goal is a finished, public app by early May 2027, built website first and then turned into a phone app.

- **Website first:** a website is faster to build and easy to test. Priests and friends can try it from a link without installing anything.
- **Phone app second:** once the website works, the same code is turned into an iPhone and Android app (for example with React Native / Expo).
- **Four reading sections:** Bible, Church Fathers, canons, and councils.
- **AI question section:** the AI searches the app's own source library and answers only from it, quoting the source for every answer. If the sources don't cover a question, it says so instead of guessing.
- **Starting sources:** public-domain texts, such as the Brenton English Septuagint, writings of Fathers like St. Athanasius, St. Cyril of Alexandria, St. Ephrem the Syrian, and St. Severus of Antioch, and the canons of the councils of Nicaea, Constantinople, and Ephesus.

## Milestones and deliverables (Nov 2026 to May 2027)
Each month ends with one deliverable; the month-by-month plan below lists the tasks behind each one.

| Month | Deliverable |
|---|---|
| Nov 2026 | Source list and sketches of every screen |
| Dec 2026 | Working website for reading the Bible and Church Fathers |
| Jan 2027 | First demo of the AI answering questions with sources |
| Feb 2027 | All four sections working, plus feedback from the first testers |
| Mar 2027 | Beta version tested by priests from several Oriental Orthodox churches |
| Apr 2027 | Release-ready website and phone app |
| Early May 2027 | Public release and final presentation |

## Month-by-month plan

### November 2026: Plan and gather sources
Deliverable: a source list and sketches of every screen.
- Choose the tools (website framework, database, AI service) and learn the basics
- Collect public-domain texts for the Bible, Church Fathers, canons, and councils
- Check that every source is accepted across the Oriental Orthodox churches
- Sketch the home screen, the four reading sections, and the AI question screen

### December 2026: Build the reading website
Deliverable: a working website where users can read the Bible and Church Fathers.
- Set up the project and put the code on GitHub
- Load the Bible and Church Fathers texts into the app
- Build the reading pages with chapter and book navigation

### January 2027: Add the AI question section
Deliverable: a first demo of the AI answering questions with sources.
- Connect the AI service to the app's source library
- Make the AI answer only from the sources and show which source it used
- Add a message that the AI does not replace asking a priest
- Write 25 test questions to check the AI's answers

### February 2027: Complete the app and first test
Deliverable: all four sections working, plus feedback from the first testers.
- Add the canons and councils sections
- Add search and bookmarks
- First test: 2–3 priests and 5–10 friends or church members try the app
- Write a fix list from their feedback

### March 2027: Wider priest testing and phone app
Deliverable: a beta version tested by priests from several Oriental Orthodox churches.
- Fix the problems found in February
- Invite priests from as many of the six churches as possible to review AI answers
- Start turning the website into a phone app

### April 2027: Final fixes and app store prep
Deliverable: a release-ready website and phone app.
- Fix the problems found in March
- Finish and test the phone app on iPhone and Android
- Create app store accounts, screenshots, and descriptions
- Submit the app to the Apple App Store and Google Play

### Early May 2027: Public release
Deliverable: Ancient Church available to the public, and a final presentation.
- Launch the website and phone app
- Share it with churches and youth groups
- Present the finished project

## Testing and priest review
Priests check the AI's answers in two rounds before release, so the app stays faithful to the Church's teaching.

- **Round 1 (February):** 2–3 priests from my own church and 5–10 friends or church members. Priests review the AI's answers to the 25 test questions and mark each one correct, partly correct, or wrong.
- **Round 2 (March):** priests from as many of the Coptic, Ethiopian, Eritrean, Armenian, Syriac, and Indian Orthodox churches as I can reach, so the app works for all Oriental Orthodox churches, not just one.
- **What I measure:** how many answers priests mark correct, whether every answer shows its source, and what testers find confusing.
- **Goal before release:** priests mark at least 90% of test answers correct, and the AI never gives an answer without a source.

## Tools, costs, and risks
The app can be built for under about $150 in its first year.

| Item | Cost | When |
|---|---|---|
| Apple Developer account | $99 per year | April 2027 |
| Google Play developer account | $25 one time | April 2027 |
| AI service | About $5–20 per month (approximate, depends on use) | January 2027 on |
| Website hosting | Free tier at first | December 2026 on |

### Risks and backup plans
- **The AI gives a wrong answer.** It answers only from the sources, shows its source every time, tells users to confirm with their priest, and is checked by priests before release.
- **Some translations are copyrighted.** Start with public-domain texts and ask permission before adding any copyrighted translation.
- **Building takes longer than planned.** The website is the main goal; if the phone app falls behind, release the website in May and the phone app after.
- **Priests are hard to reach.** Ask my own priest first and ask him to connect me with priests from other churches.
