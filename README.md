# World Texting Foundation
# World Texting Foundation messaging acronyms Restful API.
## list

```javascript
query {
  acronyms{
    acronym
    definition
  }
}
}
```

## add

```javascript
mutation {
  addAcronym(acronym: "hhhh", definition: "hahaha"){
    acronym
    definition
  }
}

```

## update

```javascript
mutation{
  updateAcronym(acronym: "hhhh", updateAcronym:"h1h1h1", updateDefinition:"haahaahaa"){
    acronym
    definition
  }
}
```
## delete
```javascript
mutation{
  removeAcronym(acronym: "hhh12"){
    acronym
    definition
  }
}

```

https://heroku0916wtfapollo.herokuapp.com/
