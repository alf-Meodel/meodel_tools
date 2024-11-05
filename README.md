# meodel_tools

# GIT HUB CLI

- Dans un premier temps nous allons vérifier que github cli est bien installé

```
gh --version
```

- Ensuite nous allons nous log à notre espace

```
gh auth login
```

## Creation de repo

Puis créer un depot avec la commande :

```
gh rep` create meodel_tools
```

- Nous pouvons ajouter des elements à cette creation

```
gh repo create meodel_tools --public --confirm
gh repo create meodel_tools --public --add-readme
```

##### Puis nous allons cloner le depot localement

```
gh repo clone meodel_tools
```

##### Création d'un repo local

Puis en supposant que j’ai appelé mon repo meodel_tools

```
gh repo clone meodel_tools
```

Puis nous allons poursuivre avec

```
cd meodel_tools
```
