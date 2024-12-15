## Gliederung

1. Allg über Scikit-learn
   1. Von Wem 
   2. Für was
   3. Funktionen
2. Used by xyz
3. Codebeispiel
   1. Preprocessing
      1. one hot encoding
   2. Feature extraction
      1. DictVectorizer
      2. CountVectorizer
      3. HashVectorizer
      4. TfidfVectorizer/Transformer
   3. Classification
   4. Regression
      1. Linear
      2. Logisitc


## Über scikit Learn

- Open source Machine learning library für Python (BSD Lizenz)
- Beinhaltet Classifikations, Regressions & Clustering Algorithmen
- Nutzt NumPy und Scipy für lineare Algebra & Array Operationen
- 
### Ursprung:
- Projekt wurde 2007 als Teil des Google Summer of Code Project vom Franzosen David Cournapeau gestartet & Matthieu Brucher als Teil seiner Thesis bearbeitet (https://scikit-learn.org/stable/about.html https://www.researchgate.net/publication/51969319_Scikit-learn_Machine_Learning_in_Python)
- 2010 Übernahme von National Institute for Research in Digital Science and Technology (Inria, Westliches Paris) & erster öffentlicher Release 
- 19 Core Contributors (zum Teil auch gesponsort z.B. Tim Head Gesposort von NVIDIA https://scikit-learn.org/stable/about.html)
- Entwicklung von Contributors & Coding Sprints

Zitat Paper: 
Python etabliert sich zunehmend als eine der beliebtesten Sprachen für scientific compution.
Scikit-learn konzentriert sich darauf, das maschinelle Lernen mit Hilfe einer universellen Hochsprache auch Nicht-Spezialisten zugänglich zu machen. Der Schwerpunkt liegt dabei auf Benutzerfreundlichkeit, Leistung, Dokumentation und API-Konsistenz.

Sponsored by:
Microsoft
NVIDIA
Chan-Zuckerberg Initiative
Scikit-learn Consortium at Inria Foundation (Inkl Chanel, AXA, NVIDIA, BNP Paribas)
Donations
Kostenlose CPU von Microsoft für CI Servers & Speicherplatz für builds 
...

Used By Spotify, Booking, JP Morgan

Descision Making Process (Durch Diskussionen mit allen Members der Community):
Minor Documentation changes:  +1 von einem Maintainer & keine -1 beim Pull Request
Code changes and major documentation changes: +1 by two Maintiners, keine -1 von einem
Changes to the API principles: Vorschlag mit einem SLEP Template

Implementationen von Themen aus der Vorlesung
1. Preprocessing
   1. one hot encoding
2. Feature extraction
   1. DictVectorizer
   2. CountVectorizer
   4. TfidfVectorizer/Transformer
3. Classification
   1. Nearest Neigbors
   2. Bayes Klassifikator
4. Regression
   1. Linear
   2. Logisitc# nlp-scikit
