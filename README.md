# fix-my-text

paste your text, get clean punctuation, capitalization and grammar back. your words are never changed or reworded.

## use it

live page: https://divsvash.github.io/fix-my-text/

or download `index.html` and open it in any browser. single self-contained file, no build step, no server, works fully offline.

## what it fixes

- extra spaces and spacing around punctuation
- jammed sentences ("fine.they" -> "fine. they", with domains like site.com left alone)
- capitalization at sentence starts, line starts and standalone "i"
- missing apostrophes in common contractions (dont -> don't, im -> i'm)
- a/an agreement ("a apple" -> "an apple", "an university" -> "a university")
- doubled words ("the the" -> "the")
- repeated punctuation (!!, ??) and ellipses
- adds a final period when a multi-word text ends bare

## limits

rule-based, no AI model, nothing leaves the page. it does not fix spelling or tense, and ambiguous cases like its/it's and your/you're are left alone on purpose rather than guessed wrong.
