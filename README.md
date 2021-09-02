# (Haiku Checker/Generator)

#### (This web application will either take a user's input to check whether it is a Haiku following the 5-7-5 syllable format. It can also generate a random haiku from a dictionary containing 1000 English words.)

#### By (Connor Hansen)

## Technologies Used

* JavaScript
* Jest
* Node Package Manager
* JQuery
* CSS
* HTML

## Description

_This application has been created to demonstrate using a project template and implementing classes with Jest for TDD._

* User enters 3 lines of text, which are checked for Haiku syllable formatting:
  - {not example bread} -- 5 syllables
  - {fraction found huge invent horse} -- 7 syllables
  - {morning four state far} -- 5 syllables
* If it does not have the correct number of syllables, a message will appear, saying such.
* A user may randomly generate a Haiku when a button is pressed.

## Setup/Installation Requirements

- _To clone and run from [GitHub Repo](https://github.com/chansen1395/haiku-generator-tester9-2):_

  - _In bash at a folder of your choice, type the following:_
    - $ git clone https://github.com/chansen1395/haiku-generator-tester9-2
    - $ code .
    - $ npm install
    - $ npm run start
- _Use a program such as VSCode to view and run the program._

## Known Bugs

* _Due to the number of exceptions to syllabic rules, not all words will be correctly parsed for the syllable count. Because of this inconsistency, the generator may occasionally incorrectly choose the incorrect number of syllables._

## License

{Let me know if you run into any issues or have questions, ideas or concerns. I encourage you to contact me or make a contribution to the code.}

## Contact Information

- _{<chansen13@georgefox.edu>}_
- _{[GitHub Repo - main](https://github.com/chansen1395/haiku-generator-tester9-2)}_