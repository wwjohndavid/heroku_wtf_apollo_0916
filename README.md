World Texting Foundation
World Texting Foundation messaging acronyms Restful API.
# list
query {
  acronyms{
    acronym
    definition
  }
}
# add
mutation {
  addAcronym(acronym: "hhhh", definition: "hahaha"){
    acronym
    definition
  }
}
# update
mutation{
  updateAcronym(acronym: "hhhh", updateAcronym:"h1h1h1", updateDefinition:"haahaahaa"){
    acronym
    definition
  }
}

# delete
mutation{
  removeAcronym(acronym: "hhh12"){
    acronym
    definition
  }
}

