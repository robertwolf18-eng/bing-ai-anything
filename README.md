# Thanksgiving BingAI 🦃

**Good food. Great company. Unexpected bingo.**

Turn the things your family and friends say around the dinner table into a personalized bingo game. Customize your words, generate differently arranged boards, and print a board for each guest.

## Play the game

**[Open Thanksgiving BingAI](https://robertwolf18-eng.github.io/thanksgiving-bingai/)**

No account, subscription, or app installation is needed. The website prepares the boards; guests play on paper during dinner.

## How to make your game

1. **Choose a title.** Keep “Thanksgiving BingAI,” or name it for your own gathering.
2. **Customize the 24 entries.** Use words or short phrases your guests are likely to say. Edit the entries individually, or expand **Paste a whole list instead** and enter one item per line.
3. **Choose the number of boards.** Make one per player, or one per team. The default is 12; you can generate between 1 and 100.
4. **Add guest names, if you like.** Expand **Add guest names (optional)** and enter one name per line, in board order.
5. **Select Generate.** The game creates a different arrangement for each board.
6. **Print your boards.** Choose one or two boards per page, then select **Print / Save as PDF**.

Each board has a **5 × 5 grid**, with **24 entries and a FREE center square**. All boards use the same entries in different positions. Printing does not reshuffle them. If you change your words, title, board count, or guest names, select **Generate** to apply those changes before printing.

## Make it personal

Mix familiar Thanksgiving words with details that fit your crowd:

| Thanksgiving | Everyday conversation | Your family and friends |
| --- | --- | --- |
| Turkey | Traffic | A grandchild’s name |
| Stuffing | Vacation | A pet’s name |
| Gravy | Football | A favorite team |
| Pie | Weather | A hometown or vacation spot |
| Leftovers | Netflix | A favorite family expression |
| Delicious | Phone | “Remember when…” |

Replace descriptions such as “A grandchild’s name” with the actual name you want to listen for. The sample game includes “Grandma,” “The dog,” “The Yankees,” and “New York” as examples you can replace.

Choose mostly entries likely to come up naturally, with a few funny or distinctive ones. Keep the game friendly and avoid topics that would embarrass a guest.

Entries must be different and cannot be blank. Keep each entry to 60 characters or fewer; short entries are easiest to read on paper.

## Beyond Thanksgiving: more ways to play

The same generator works wherever people have something to listen for. Change the title and replace the 24 entries to suit the occasion.

### 2. Football bingo: get the non-football fans into the game!

Give everyone at the watch party something to cheer about—even the guests who came mostly for the snacks. Mix football terms with familiar things the announcers or people on the couch are likely to say.

**Sample words and phrases:** beer, injury, fumble, touchdown, penalty, quarterback, interception, timeout, referee, replay, halftime, field goal, commercial, “What a catch!”, and “Pass the chips!”

Agree whether words count when said by the TV commentators, people in the room, or either. For a listening game, mark “fumble” when someone says it; if you prefer to mark events you see on screen, agree on that variation before kickoff. Watching an ordinary play can suddenly become exciting when someone is one square away from BINGO.

### 3. Classroom bingo: give students something to listen for

Teachers can turn a lesson, documentary, or review session into a listening activity. A history teacher introducing the American Revolution, for example, could build boards around key vocabulary, people, and ideas.

**Sample words and phrases:** war, revolution, causes, colony, taxation, protest, boycott, Parliament, representation, liberty, independence, king, patriot, Loyalist, constitution, and treaty.

Students mark words as they hear them during the lesson. To turn a winning board into a learning opportunity, ask the student to explain one marked term or connect two squares: “How did taxation contribute to protest?” For review, read definitions or clues and let students mark the matching terms instead.

Keep the focus on understanding as well as spotting words. A quiet hand signal for BINGO can keep the lesson moving.

*These are starting ideas, not complete 24-entry lists. Add topic-specific words to fill every board, and change the title to match your game.*

## Rules for the table

- Mark a square when someone says its word or phrase aloud for the group to hear.
- Mark the center **FREE** square at the start.
- The first player to complete **five squares in a row, column, or diagonal** calls **BINGO!**
- Check the winning line together. Ties share the win.
- Agree before starting whether deliberately prompting someone to say a word is allowed, and whether variations of a word count.

**Will someone win?** More boards generally create more opportunities for an early winner, but no number of boards guarantees one: enough listed words must actually be said. If all 24 entries are heard, every board will eventually win. Choosing likely conversation words keeps the game moving.

## Printing and saving a PDF

The print button opens your browser’s print dialog. Available printers and PDF options depend on your device and browser.

- Use **US Letter (8½ × 11 inches)** paper in **portrait** orientation.
- Choose **one board per page** for larger text, or **two per page** to save paper.
- Start with **100% scale** and check the preview before printing the full set.
- Turn off browser headers and footers if they appear.
- Use your browser or device’s PDF saving option to keep or send a printable copy.

The print layout hides the editing controls and is designed to keep each board together. Printer settings can affect the result. Physical printer output and iPad printing have not yet been verified.

## Save or share a customized game

Your settings and generated boards are saved in the browser you use. They do not automatically transfer to another device or browser, and clearing browser data can remove them.

- **Export game** downloads a JSON file containing your settings and current boards.
- **Import game** opens a previously exported game file.
- Share the **website link** so someone can make their own game.
- Share an **exported game file** to transfer your customization and board arrangements, or share a **PDF** for printing.

Exported files can contain the guest names and words you entered. Share those files only with the people you intend. Export and import still need end-to-end verification.

## About the project

The game is a self-contained web page built with HTML, CSS, and JavaScript. There is no build step, paid API, or AI service required to play. The app does not send customized entries to a server; it stores them locally in the browser. GitHub Pages serves the website.

### Repository files

- `index.html` — the complete game, including styling, board generation, customization, and print layouts.
- `README.md` — this guide.

### Hosting

The live game is published through **GitHub Pages** from the `main` branch and the repository root. In **Settings → Pages**, the source is **Deploy from a branch**, with `main` and `/ (root)` selected. Changes committed to the published branch trigger an updated deployment.

### Verification

The published site was checked to confirm that it loads and generates 12 sample boards. The original model was also checked for unique arrangements, the same 24 entries on every board, FREE centers, and rejection of duplicate entries. These checks do not establish compatibility with every browser or printer.

---

**Listen closely. Laugh often. First to five calls BINGO!**
