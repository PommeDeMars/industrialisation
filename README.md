# TP2

## Questions

### Quelles étapes (steps) sont réalisées par cette action ?

- Set up Python 3.10
- Install dependencies
- Lint with flake8
- Test with pytest

### Une étape est définie au minimum par 2 éléments, lesquels sont-ils et à quoi servent-ils ?

- name : le nom de l'étape
- run : les commandes à effectuer

### La première étape contient le mot-clé ‘with’, a quoi sert-il ?

- Configurer la version de python

### Sur l’onglet Summary d’une analyse de code, SonarCloud fournit 4 indicateurs. Quels sont-ils et quelles sont leurs utilités ?

- New Issue : new issue in the new code
- Accepted Issue : Valid issue that were not fixed
- Coverage : Coverage of tests
- Duplications : Duplications of code line
- Security Hotspots : Security sensitiv piece of code

### À quoi sert l’indicateur Quality Gate ?

D'après sonarQube:  
A Quality Gate is a set of measure-based Boolean conditions. It helps you know immediately whether your project is **production-ready**. Ideally, all projects will use the same quality gate. Each project's Quality Gate status is displayed prominently on its homepage.

### Quelle est la différence entre les sections New code et Overall Code dans l’onglet Summary ?

- New code : données sur le code qui vient d'être push
- Overall code : le code de tout le projet

### Y a-t-il des Code Smells ? Si oui, combien et pour quelle(s) raisons(s) ?

3:

- Remove the unused function parameter "deferred".
- Update this function so that its implementation is not identical to spend_cash on line 16
- Remove the unused function parameter "deferred".

### Y a-t-il des Security Hotspots ? Si oui, combien et pour quelle(s) raison(s) ?

- Oui, l'image docker tourne en root par défaut
