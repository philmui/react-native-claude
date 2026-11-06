# CS 147L Interview 2 Prep Kit

An interactive study kit for React Native and TypeScript, based on the [home page](index.html). It prepares you to build a small app with a list held in state, reusable cards, and a form that adds items through a callback.

## Open the kit

Open `index.html` in a browser. There is no dependency installation or build step: the five pages contain their own styles and JavaScript.

For a local HTTP preview, run this command from the repository directory with Python 3 installed:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Then visit `http://127.0.0.1:8000/`. Stop the server with `Ctrl+C`. Use [Expo Snack](https://snack.expo.dev/) to write and run the React Native exercises; this repository itself is a static study site.

## Find your starting point

| Page | What you can do |
| --- | --- |
| [Home](index.html) | Explore the eight core ideas, select a study route, rate topic confidence, and review the five Golden Patterns. |
| [Concepts](concepts.html) | Learn all thirteen topics through explanations, diagrams, and interactive simulators. |
| [Practice](practice.html) | Try bug fixes, fill-in-the-blank drills, exercises with tiered hints, and full builds. |
| [Mock Interview](mock-interview.html) | Try three timed mocks, rapid-fire questions, and self-assessment rubrics. |
| [Cheat Sheet](cheat-sheet.html) | Review printable patterns, common mistakes, and an error-message decoder. |

Press `/` or `Ctrl+K` to open the kit's finder, use the arrow keys to move through results, `Enter` to open one, and `Esc` to close it. Try searches such as `TextInput`, `filter`, or `never`.

On the home page, confidence ratings and study checklist ticks last only while the page is open and reset on reload.

## One app, eight ideas

The [big-picture explorer](index.html#overview) connects a sample app to these ideas:

1. **Describe the data with a type:** define the shape of an item.
2. **Keep the list in state:** use `useState` to retain data between renders.
3. **Turn data into cards with `map`:** return JSX for each item and supply a stable, unique key.
4. **Make a card component with props:** receive and destructure a props object.
5. **Build controlled inputs:** connect `TextInput` and `Switch` to form state.
6. **Pass a function to `onPress`:** run the handler when pressed.
7. **Send new items up through a callback:** let the parent update its list with a new array.
8. **Lay out the screen with Flexbox:** work with rows, columns, and alignment.

The [five Golden Patterns](index.html#golden) provide a shorter recall exercise: state from data, mapping to components, immutable additions, parent–child callbacks, and controlled inputs. Turn on **Hide the code**, write a pattern in Snack, then reveal it to compare.

## Topic reference

The priorities below follow the home page's topic explorer. Each topic has a direct link to all four study modes.

| Topic | Priority | Learn | Practice | Test | Review |
| --- | --- | --- | --- | --- | --- |
| Arrow functions | Must-know | [Concept](concepts.html#arrows) | [Exercises](practice.html#arrows) | [Questions](mock-interview.html#arrows) | [Cheat card](cheat-sheet.html#arrows) |
| `map` and lists | Must-know | [Concept](concepts.html#map) | [Exercises](practice.html#map) | [Questions](mock-interview.html#map) | [Cheat card](cheat-sheet.html#map) |
| State (`useState`) | Must-know | [Concept](concepts.html#state) | [Exercises](practice.html#state) | [Questions](mock-interview.html#state) | [Cheat card](cheat-sheet.html#state) |
| Immutable updates | Must-know | [Concept](concepts.html#spread) | [Exercises](practice.html#spread) | [Questions](mock-interview.html#spread) | [Cheat card](cheat-sheet.html#spread) |
| Components and props | Must-know | [Concept](concepts.html#components) | [Exercises](practice.html#components) | [Questions](mock-interview.html#components) | [Cheat card](cheat-sheet.html#components) |
| Callbacks between components | Must-know | [Concept](concepts.html#callbacks) | [Exercises](practice.html#callbacks) | [Questions](mock-interview.html#callbacks) | [Cheat card](cheat-sheet.html#callbacks) |
| Inputs | Must-know | [Concept](concepts.html#inputs) | [Exercises](practice.html#inputs) | [Questions](mock-interview.html#inputs) | [Cheat card](cheat-sheet.html#inputs) |
| TypeScript | Good to know | [Concept](concepts.html#typescript) | [Exercises](practice.html#typescript) | [Questions](mock-interview.html#typescript) | [Cheat card](cheat-sheet.html#typescript) |
| Layout and Flexbox | Good to know | [Concept](concepts.html#layout) | [Exercises](practice.html#layout) | [Questions](mock-interview.html#layout) | [Cheat card](cheat-sheet.html#layout) |
| Conditional rendering | Good to know | [Concept](concepts.html#conditional) | [Exercises](practice.html#conditional) | [Questions](mock-interview.html#conditional) | [Cheat card](cheat-sheet.html#conditional) |
| Effects, timers, and Promises | Quick refresh | [Concept](concepts.html#effects) | [Exercises](practice.html#effects) | [Questions](mock-interview.html#effects) | [Cheat card](cheat-sheet.html#effects) |
| The mental model | Quick refresh | [Concept](concepts.html#mental-model) | [Exercises](practice.html#mental-model) | [Questions](mock-interview.html#mental-model) | [Cheat card](cheat-sheet.html#mental-model) |
| Interview craft | Quick refresh | [Concept](concepts.html#interview-craft) | [Exercises](practice.html#interview-craft) | [Questions](mock-interview.html#interview-craft) | [Cheat card](cheat-sheet.html#interview-craft) |

## Suggested study sessions

- **About 10 minutes:** recall the [Golden Patterns](index.html#golden), skim [wrong vs. right examples](cheat-sheet.html#gotchas), then try two [bug-fix drills](practice.html#drills-fix).
- **About 25 minutes:** choose a weak topic from the [big picture](index.html#overview), complete an exercise, answer five [rapid-fire questions](mock-interview.html#quizmode), and rehearse the parent–child callback pattern.
- **45 minutes or more:** complete [Mock 1: Café Menu](mock-interview.html#mock1) with its 25-minute timer, [score it](mock-interview.html#mock1-rubric), and rebuild the weakest part from a blank file.

For a guided build, start with [Build A: Café Menu](practice.html#build-a). For syntax recall, try the [fill-in-the-blank drills](practice.html#drills-fill).

## Interview guidance and source scope

The kit describes a 25-minute interview in Expo Snack, using a handout with a screenshot and a step-by-step breakdown. Its advice emphasizes thinking aloud, running the app frequently, reading errors, and explaining the process. See [interview-day essentials](index.html#day-of) for the kit's format and resource guidance.

These interview details are attributed to the kit. The home page credits course lectures 1a–5b and attributes its search examples to Lecture 4a, slide 11, but the lecture originals are not included or linked in this repository. Those course references and current assessment rules could not be independently verified; confirm current rules with the course staff before the interview.

## Downloads

| File | Purpose |
| --- | --- |
| [Prep Guide (PDF)](downloads/CS147L-Interview2-Prep-Guide.pdf) | Readable document version of the kit. |
| [Prep Guide (Word)](downloads/CS147L-Interview2-Prep-Guide.docx) | Editable guide for personal notes. |
| [Cheat Sheet (PDF)](downloads/CS147L-Interview2-Cheat-Sheet.pdf) | Compact, printable reference. |

## Official references

These are the nine external resources linked from the home page. The documentation pages were checked for both accessibility and the subject described below; Snack was checked for accessibility.

| Reference | What it supports |
| --- | --- |
| [React: Updating Arrays in State](https://react.dev/learn/updating-arrays-in-state) | Adding, removing, and replacing array items without mutating state. |
| [React: Sharing State Between Components](https://react.dev/learn/sharing-state-between-components) | Lifting state to a common parent and passing data and handlers through props. |
| [React: Rendering Lists](https://react.dev/learn/rendering-lists) | Using `map`, filtering lists, and choosing keys. |
| [React Native: TextInput](https://reactnative.dev/docs/textinput) | Controlled text values, `onChangeText`, and placeholders. |
| [React Native: Pressable](https://reactnative.dev/docs/pressable) | Press interactions and the `onPress` handler. |
| [React Native: Switch](https://reactnative.dev/docs/switch) | Boolean values and `onValueChange`. |
| [React Native: Layout with Flexbox](https://reactnative.dev/docs/flexbox) | Default column direction, `justifyContent`, and `alignItems`. |
| [Expo Snack](https://snack.expo.dev/) | Browser-based React Native editor for practice. |
| [TypeScript Handbook: Everyday Types](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html) | Primitive types, arrays, object types, aliases, and unions. |

## Verification notes

Links checked on **November 6, 2026**:

- Every relative Markdown link in this README was checked against the repository, including the exact destination ID for each HTML fragment.
- The home page's local links and literal JavaScript topic destinations were also checked for existing files and anchors.
- All three downloadable files exist and have the expected PDF or DOCX file signatures.
- All nine external reference URLs opened successfully. External content and URLs may change after this check.

The course-source limitation is documented above. Link verification does not certify every statement in the study kit or the contents of its downloadable guides.
