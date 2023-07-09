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
  * dec. 4 for nouns that go like "adventus, adventus"
  * dec. 5 for nouns that go like "res, rei"
* The genitive in the singular form
* Its translation in English

Here are examples for all declensions:
```
"epistula": ["1", "epistulae", "letter"]
"equus": ["2", "equi", "horse"]
"donum": ["2n", "doni", "gift"]
"clamor": ["3", "clamoris", "noise"]
"nomen": ["3n", "nominis", "name"]
"manus": ["4", "manus", "hand"]
"fides": ["5", "fidei", "faith"]
```

Fork this repository and add your noun to the end of the previous one, remembering to **add a comma**.
