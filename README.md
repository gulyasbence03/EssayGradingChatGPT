# EssayGrading

Alkalmazott AI tantárgy féléves házifeladata.

## Feladat leírás

23_05d Automated Essay Scorer:
Design a system that scores essays based on factors like grammar, coherence, and vocabulary.
Use Natural Language Processing techniques and get assistance with libraries like NLTK or spaCy.

## Használat

1.) Először futtatni kell a szükséges letöltéseket
 
```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('averaged_perceptron_tagger')
nltk.download('wordnet')
!pip install language-tool-python
```
2.) Esszét megadni string formátumú essay változónak, a """ között """. Például:

```python
essay = """
To begin with pollution and damage to the environment is the most serious and difficult problem for countries of all over the world. Scientists of different countries predict a global ecocatastrophe if people won’t change their attitude to our planet.

First of all a huge damage to the environment brings a transport. People can’t imagine their living without cars, buses, trains, ships and planes. But it’s an open secret that one of disadvantage of these accustomed things is harmful exhaust. Needless to say that use of environment friendly engines helps us to save atmosphere from pollution.

In addition to this our rivers and seas are in not less danger situation. It’s a fact of common knowledge that numerous factories and plants pour off their waste to ponds. Obviously that cleaning manufacturing water helps to avoid extinction of ocean residents.

Apart from this I’m inclined to believe that every person can and must contribute to solving this important problem. Doing a little steps for protection our environment every day we will be able to save our Earth. And it’s a task of each of us.
"""
```
3.) Futtatni a fő program kódját. Az eredmény a kód alatti kimenetben jelenik meg. Példákat a következő oldalon lehet találni: https://engxam.com/handbook/essays-sample-answers-comments-b2-first-fce/

```python
Checking Vocabulary...
Vocabulary Check Complete✔️
Vocab: 5

Checking Coherence...
Coherence Check Complete✔️
Coherence: 5

Checking Grammar...
Grammar Check Complete✔️
Grammar: 3


Overall essay grade: 4

⚠️ The essay contains grammar issues. Consider reviewing and correcting them. ⚠️
```
