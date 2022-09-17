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

#delete
mutation{
  removeAcronym(acronym: "hhh12"){
    acronym
    definition
  }
}

#example Answer
{
  "data": {
    "removeAcronym": {
      "acronym": null,
      "definition": null
    }
  }
}

API Endpoints
Request headers:
Content-Type: application/json
Authorization: Bearer<space>token

GET /acronym?from=50&limit=10&search=:search   List acronyms
POST /acronym   Create an acronym
PUT /acronym/:id   Edit an acronym
DELETE /acronym   Delete an acronym