# Anki flashcard decks for FCC commercial radio operator licensing examinations

## Overview

This project consists of flashcard decks for the complete questions pools for
all of the written examination elements used in the Federal Communications
Commission's [Commercial Radio Operator License Program][1] at the time of
release.

These decks are for use with [Anki][2], a spaced-repetition flashcard program.
The decks are in CrowdAnki JSON format and may be imported to Anki using the
[CrowdAnki plugin][3].

### Decks included

This project includes decks for the following written exam elements:

| Element    | Description                                      |
|------------|--------------------------------------------------|
| Element 1  | Basic radio law and operating practice           |
| Element 3  | General Radiotelephone                           |
| Element 6  | Advanced Radiotelegraph                          |
| Element 7  | GMDSS Radio Operating Practices                  |
| Element 7R | Restricted GMDSS Radio Operating Practices       |
| Element 8  | Ship Radar Techniques                            |
| Element 9  | GMDSS Radio Maintenance Practices and Procedures |

Each deck, to my best of my knowledge, contains all of the questions and correct
responses that appear in all the question pools in use as of the time of
release.

The question pool documents were retrieved from the FCC website between December
2018 and April 2019.

### More information about FCC licensing

For more information about FCC commercial radio operator licensing examinations
and to obtain the original question pool documents from which these decks were
created, visit the FCC's [commercial operator license examinations page][4].

Before investing time in study, you are advised to check the FCC website to
ensure that the question pools used for these decks are still valid and in use.

## Getting started

### Prerequisites

1. Download and install [Anki][2] software version 2.0.x or 2.1.x.
2. Install the [CrowdAnki plugin][3] for Anki (as of 7 May 2019, CrowdAnki is
   compatible with Anki 2.0.x and 2.1.x.)

### Download

Go to the [project's downloads page][5], select the Tags tab, and download the
desired version.

If you prefer, you may instead use Git to download the decks to your computer,
by simply cloning the [project repository][6].

### Import

After downloading the deck(s), refer to the [Import section of the CrowdAnki
README][7]. Follow the "import from disk" instructions.

You will need to import each deck individually, so repeat this step as needed
for each deck that you plan to study.

## Usage

Once you have the deck(s) installed, select a deck to begin reviewing that deck.

Refer to the [Anki user manual][8] to understand how Anki works and how to use
it.

### Card format

FCC commercial operator written exams are administered in multiple choice form.
For these decks, however, I have largely employed a question-and-answer format
instead of including the multiple choices on the card. This decision was based
on the [Anki Manual's recommendations studying for a multiple-choice exam][9].

For some question types, however, a question-and-answer format is not ideal, as
omitting the multiple choices responses sometimes removes important context,
making it difficult to answer the question based on the information given. In
such cases, I generally have kept the multiple choice options intact.

Here are some examples of question types where this format is commonly used:

- Questions that are phrased as "Which of the following..."
- Questions with compound answers, e.g. where the correct answer is "All of the
  above", "A and C", etc.
- Negative questions, i.e. those that ask you to identify which of these is
  *not* correct, which of these does *not* apply, etc.

The Element 6 question pool in particular makes heavy use of compound questions;
they are the rule rather than the exception. Because of this, I chose to keep
the multiple choice options intact for that entire deck.

#### Conventions used

For the most part, the cards adhere to the following formatting and style
conventions.

**The front side of each card always contains the question ID and question
text.** In some cases, for reasons stated in the previous section, the front may
also include a list of multiple choice responses.

**The back side of each card contains the full text of the correct answer
choice.** The actual FCC exams will not necessarily list the answer choices in
the same order that they appear in the question pools, so memorizing the letter
(A, B, C, or D) of each response is not a good study technique.

**Remarks from the deck author are enclosed in square brackets and begin with
"Edit:"** On the front of cards, in cases where the question text alone doesn't
make it clear what precisely the question is asking for, I have sometimes
deviated from the aforementioned practice of including the multiple-choice
responses back and instead have added a remark containing a hint to help clarify
what type of response the question is seeking. On the back of cards, remarks may
point out suspected errors in the question pools, provide further detail about a
concept, or suggest a mnemonic device.

### Editing cards

You are encouraged to edit the cards to suit your needs. For example, you may
wish to add or remove multiple-choice options from a card, or add your own
hints, mnemonics, and so on.

The [Editing and More section][10] of the Anki User Manual explains how to do
this.

## Version History

Refer to HISTORY.md

## License

This project is distributed under the MIT License. Refer to LICENSE.md

## Contributing to this project

Refer to CONTRIBUTING.md

## Supporting this project

Your support is appreciated! 

Cash gifts may be sent via [PayPal](https://paypal.me/mattschonert).

Cryptocurrency may be sent using the following addresses:

- ETH: 0x50865e420E5FCc977B18c96dC396fba6Ce80B9A9
- BTC: 17AQVqZ7NgApTSoB8YaBP4ocrfUKwCbe69
- LTC: MUjtSpiQQ2CPEgLYQ3KLMQB7Fz7b5t6hjh

[1]: https://www.fcc.gov/wireless/bureau-divisions/mobility-division/commercial-radio-operator-license-program
[2]: https://apps.ankiweb.net
[3]: https://ankiweb.net/shared/info/1788670778
[4]: https://www.fcc.gov/wireless/bureau-divisions/mobility-division/commercial-radio-operator-license-program/examinations
[5]: https://bitbucket.org/mschonert/anki-decks-fcc-commercial-radio-operator-exams/downloads/?tab=tags
[6]: https://bitbucket.org/mschonert/anki-decks-fcc-commercial-radio-operator-exams/
[7]: https://github.com/Stvad/CrowdAnki/blob/master/README.md#import
[8]: https://apps.ankiweb.net/docs/manual.html
[9]: https://apps.ankiweb.net/docs/manual.html#_can_i_do_multiple_choice_questions
[10]:https://apps.ankiweb.net/docs/manual.html#editing-and-more
