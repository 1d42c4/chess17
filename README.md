# Tactics, Made Visible

**[Read the GitHub Pages collection](https://1d42c4.github.io/chess17/)**

Sixteen fully explained tactical ideas with the moves already shown.

For players who want to understand tactical mechanisms before solving puzzles.

## Format

- 16 direct lessons, each a self-contained HTML file with its own styles and embedded vector chess pieces.
- 32 lesson diagrams: the starting position and the result of the fully explained line.
- Visible explanations throughout: no answer inputs, hidden solutions, scores, progress controls, or client-side JavaScript.
- One printable collection, Markdown notes, and PGN move sequences.

A single lesson can be saved or copied on its own and read offline. Navigation to other lessons requires those neighboring files, but the lesson text and diagrams do not. Open [collection.html](collection.html) and use your browser’s Print command to print or save as PDF.

## Lessons

1. [A knight fork creates two threats at once](lessons/01-a-knight-fork-creates-two-threats-at-once.html)
2. [A pawn can fork two pieces](lessons/02-a-pawn-can-fork-two-pieces.html)
3. [An absolute pin limits legal movement](lessons/03-an-absolute-pin-limits-legal-movement.html)
4. [A relative pin can be broken with a forcing move](lessons/04-a-relative-pin-can-be-broken-with-a-forcing-move.html)
5. [A skewer attacks the front piece to reach the one behind](lessons/05-a-skewer-attacks-the-front-piece-to-reach-the-one-behind.html)
6. [A discovered attack gives a line back to another piece](lessons/06-a-discovered-attack-gives-a-line-back-to-another-piece.html)
7. [Double check requires a king move](lessons/07-double-check-requires-a-king-move.html)
8. [Remove the defender before taking its target](lessons/08-remove-the-defender-before-taking-its-target.html)
9. [A back-rank trap is a shortage of exits](lessons/09-a-back-rank-trap-is-a-shortage-of-exits.html)
10. [A protected queen can mate next to the king](lessons/10-a-protected-queen-can-mate-next-to-the-king.html)
11. [A smothered king cannot answer a knight check](lessons/11-a-smothered-king-cannot-answer-a-knight-check.html)
12. [Two attackers can make a pawn an entry square](lessons/12-two-attackers-can-make-a-pawn-an-entry-square.html)
13. [A knight promotion can create an immediate fork](lessons/13-a-knight-promotion-can-create-an-immediate-fork.html)
14. [Stalemate is a tactical resource for the defender](lessons/14-stalemate-is-a-tactical-resource-for-the-defender.html)
15. [Winning the exchange means a rook for a minor piece](lessons/15-winning-the-exchange-means-a-rook-for-a-minor-piece.html)
16. [A material capture can lose to an immediate mate](lessons/16-a-material-capture-can-lose-to-an-immediate-mate.html)

## Four companion collections

| Repository | Collection | Live site |
| --- | --- | --- |
| [chess15](https://github.com/1d42c4/chess15) | Chess, Clearly | [Read](https://1d42c4.github.io/chess15/) |
| [chess16](https://github.com/1d42c4/chess16) | Openings, Explained | [Read](https://1d42c4.github.io/chess16/) |
| [chess17](https://github.com/1d42c4/chess17) | Tactics, Made Visible | [Read](https://1d42c4.github.io/chess17/) |
| [chess18](https://github.com/1d42c4/chess18) | Endgames, Step by Step | [Read](https://1d42c4.github.io/chess18/) |

## Verification and maintenance

[Sources and verification](sources.html) explains the scope. [VERIFICATION.json](VERIFICATION.json) records legal move, diagram, PGN, self-containment, and directory-size checks. The endgame collection also includes exact tablebase results. Illustrative tactical continuations are not claims of exhaustive analysis.

Edit [source/course.json](source/course.json), run `node tools/build.mjs`, then run `node tools/verify.cjs`. All directories must remain below 1,000 entries.

GitHub Pages publishes the root of `main` through `.nojekyll`. Default-branch rules require pull requests and block force pushes and branch deletion, without bypass actors. An owner can still alter settings or delete a repository.

## Credits

Original AI-created lessons prepared for 1d42c4. Cburnett pieces by Colin M. L. Burnett are supplied under GPL-2.0-or-later, with [unmodified SVG sources, provenance, and license](source/pieces/README.md). The artwork’s full license is also embedded as a comment in each standalone HTML file. chess.js is used for authoring checks under its [BSD-2-Clause license](vendor/chess-LICENSE.txt).
