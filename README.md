# Ethics in Artificial Intelligence

An interactive lecture on how to judge a decision when a machine is part of it. Students make five real decisions, work through ten short modules, judge a real case as a team, and save their notes.

**Open the lecture:** https://cynthialmcginnis.github.io/ai-ethics/

## What is in the lecture

The lecture has 42 screens in this order.

| Part | What students do |
| --- | --- |
| Opening | Make five decisions based on real cases, then see what the real people chose |
| Module 1. Foundations of AI ethics | The trolley problem in three cases, six ethical lenses, how to apply a lens |
| Module 2. Human-AI interaction | Choose the design for a health app that books appointments |
| Module 3. Safety and security | The Uber self-driving car death, 2018 |
| Module 4. Fairness, non-discrimination and inclusion | A child welfare risk score, a 3D lab, and a fairness lab |
| Module 5. Privacy, data protection and data governance | Italy's 2023 ban on ChatGPT |
| Module 6. Transparency, explainability and accountability | The right to a reason, and who answers for an AI mistake |
| Module 7. AI, environment and sustainability | The environmental cost of AI, and a town deciding on a data center |
| Module 8. Proportionality and do no harm | Facial recognition in a school lunch line |
| Module 9. Human autonomy, meaningful work, and the AI economy | Michigan's automated unemployment fraud system |
| Module 10. Global AI governance | The European Union, the United States, and Japan |
| AI Lab Sprint: The Verdict | Teams judge one real case with two ethical lenses |
| Your decision | A bank's loan model, then the student's saved notes |

Each module opens with a title page: the module question, the case study, words to know, and resources to read after class.

## For students

1. Open the link above, or download `index.html` and open it in a web browser.
2. Type your name on the cover page.
3. Use **Next** and **Back** at the bottom of the screen, or the left and right arrow keys.
4. Teal boxes are work you do. Amber boxes are questions the class talks about.
5. On the last screen, select **Download my notes** or **Print or save as PDF**. Upload that file where your instructor asks.

Your answers save in your own browser as you type. They are not sent anywhere. Clearing your browser data erases them.

## For the instructor

The controls are in the bottom bar.

- **Sections** jumps to any screen.
- **Call on a student** picks a name from the class list and does not repeat a name until everyone has been called.
- **Class list** changes the names for this browser only.
- **Dark** switches between light and dark.
- **Full screen** fills the projector screen.

### Change the class list for a new class

Open `index.html` in a text editor such as Notepad. Search for `ROSTER_DEFAULT`. Replace the names, keeping each one in double quotes with commas between them:

```js
const ROSTER_DEFAULT = ["Name one", "Name two", "Name three"];
```

Save the file and upload it again. To use no names, leave the list empty: `[]`.

The student first names are written into the file. Anyone who opens the public link can read them.

### Change the agenda

Search for `const AGENDA` in the same file. Each row has a label, a description, and the section it jumps to.

## Requirements

- A current web browser: Chrome, Edge, Firefox, or Safari.
- No internet connection is needed after the page loads. Everything is in one file, including the 3D library.
- Works on laptops and tablets. Phones work, with more scrolling.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole lecture |
| `README.md` | This page |

A printed handout and an instructor guide go with the lecture for students without a device. They are not posted here.

## Case studies

Real cases: Amazon's hiring tool, Amazon's Alexa recordings, the COMPAS risk score, the Uber test car, the arrest of Robert Williams in Detroit, the Allegheny Family Screening Tool, Italy's action against ChatGPT, Chelmer Valley High School, and Michigan's MiDAS system.

Teaching examples written for this lecture: the maternal health app, the town data center, the GenAI assistant across three markets, and Case 2 of the trolley problem. Each is labeled on screen as made up for teaching. The people in the two labs are simulated.

## Sources

- Digital Cooperation Organization. (2025). *Rights by design: Embedding human rights principles in AI systems*.
- Hellman, D. (2025). Algorithmic fairness. In *The Stanford encyclopedia of philosophy*. https://plato.stanford.edu/entries/algorithmic-fairness/
- Mohamed, S., Png, M.-T., & Isaac, W. (2020). Decolonial AI: Decolonial theory as sociotechnical foresight in artificial intelligence. *Philosophy & Technology, 33*(4), 659–684. https://doi.org/10.1007/s13347-020-00405-8
- Travaglianti, M., & Both, T. (n.d.). *Ethics toolkit*. McCoy Family Center for Ethics in Society, Stanford University. https://ethicsinsociety.stanford.edu/tech-ethics/ethics-toolkit
- UNESCO. (2021). *Recommendation on the ethics of artificial intelligence*. https://unesdoc.unesco.org/ark:/48223/pf0000381137

Each module title page lists more resources for reading after class.

## Credits

Written and built by Cynthia McGinnis.

The 3D views use three.js, version 149, released under the MIT License. Copyright 2010 to 2023, three.js authors.
