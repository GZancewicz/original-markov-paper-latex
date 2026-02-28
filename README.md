# LaTeX Transcription of Original 1906 Russian Markov Process Paper

**[View the compiled PDF](Markov_1906_Russian.pdf)**

## Original Paper

**A. A. Markov**, "Extension of the Law of Large Numbers to Quantities Dependent on Each Other"
(*Rasprostranenie zakona bol'shikh chisel na velichiny, zavisyashchie drug ot druga*)

Published in *Izvestiya Fiziko-matematicheskogo obshchestva pri Kazanskom universitete*
(Proceedings of the Physico-Mathematical Society at Kazan University), 2nd Series, Vol. 15, 1906, pp. 135–156.

The PDF in this directory (`Markov_1906_Extension_Law_Large_Numbers_Reprint_JEHPS.pdf`) is a scanned reprint sourced from the *Journal Electronique d'Histoire des Probabilites et de la Statistique* (JEHPS). It contains 12 pages of two-page spreads covering the original pp. 135–156.

This is the foundational paper in which Markov introduces what are now known as **Markov chains** — sequences of dependent random variables where each variable depends only on the immediately preceding one. Markov proves that the law of large numbers extends to such dependent quantities under suitable conditions.

## LaTeX Transcription

The file `Markov_1906_Russian.tex` (in the parent directory) is a manual transcription of the full paper from the scanned PDF into LaTeX.

### Transcription method

The scanned PDF is image-based (no OCR text layer). The transcription was performed by Claude Code using parallel AI agents — three agents each transcribed 4 pages of the 12-page document by reading the scanned images directly. A second round of three verification agents then compared the transcription against the original, identifying and correcting errors.

### Compilation

The document requires **XeLaTeX** (not pdflatex) due to the use of pre-revolutionary Russian orthography with Unicode characters (ъ, ѣ, і, ѳ):

```bash
xelatex Markov_1906_Russian.tex
```

Dependencies: `fontspec`, `polyglossia`, `amsmath`, `amssymb`. The font used is **PT Serif** (must be installed on the system).

### Orthographic notes

The transcription preserves the original pre-revolutionary Russian orthography exactly, including:
- Hard sign (ъ) at the end of words ending in consonants
- Yat (ѣ) in place of modern е in certain words
- Decimal і in place of modern и before vowels
- Fita (ѳ) in words like "ариѳметическое"

### Structure

The paper consists of five sections (§1–§5), with two dates appearing in the text:
- 16 January 1907 (after §4)
- 25 March 1907 (at the end, after §5)
