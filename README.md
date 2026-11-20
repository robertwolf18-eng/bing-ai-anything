# Thanksgiving BingAI

A customizable dinner conversation bingo game. Hosts edit 24 words or short phrases, generate unique 5 × 5 boards with a FREE center, and print them for their guests.

## Play

1. Edit the title and conversation words.
2. Set the number of boards and optionally add guest names.
3. Select **Generate** to apply changes.
4. Choose one or two boards per US Letter page, then **Print / Save as PDF**.

Five in a row, column, or diagonal wins. Agree whether deliberately prompting words is allowed. Ties share the win.

## Privacy and saved games

The app has no server, analytics, external fonts, paid APIs, or AI account requirement. Settings and generated boards are saved in the current browser. Use **Export game** and **Import game** to transfer settings and boards between devices. Exported game files may contain the guest names and words you entered; share them only with intended recipients.

## Website

The application is entirely in `index.html`, with no build step or dependencies. Serve it through HTTPS for reliable browser features.

To publish with GitHub Pages, use repository **Settings → Pages**, choose **Deploy from a branch**, and select **main** and **/ (root)**. GitHub shows the resulting website address after deployment. Repository visibility and account plan can affect Pages availability.

## Printing

The print button opens the browser print dialog. Use Letter paper, portrait orientation, and 100% scale; turn off browser headers and footers if they appear. Printer and browser settings can affect page layout.

## Verification

The original model was checked for 12 unique arrangements, all 24 words on each board, FREE centers, and rejection of duplicate entries. Physical printer output and iPad printing have not been verified. Export/import still needs end-to-end testing.
