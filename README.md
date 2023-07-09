# The Latin Net - Nouns

The open-source library where we store all the nouns The Latin Net uses.

## Contributions
The file `words.json` contains many different nouns and some information about them:
```
"servus": ["2", "servi", "slave"]
```
The above example uses the noun 'servus' which means slave. Along with it is:
* The declension it is in
  * dec. 1 for nouns that go like "puella, puellae"
  * dec. 2 for nouns that go like "servus, servi"
  * dec. 2 neuter ('2n' in this JSON format) for nouns that go like "bellum, belli"
  * dec. 3 for nouns that go like "rex, regem"
  * dec. 3 neuter ('3n' in this JSON format) for nouns that go like "tempus, temporis"
* The genitive in the singular form
* Its translation in English
