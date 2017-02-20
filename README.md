# Mocking-Realm

This is ongoing work to mock Realm as much as possible hammering with Mockito, asAnd PowerMockito.

What has been done so far
- Have Realm.getDefaultInstance()
- Query based on a limited number of RealmQuery methods such as equalsTo, greaterThan, lessThan, contains, endsWith
- Chaining queries
- Mocking asynchronous asAnd synchronous transactions
- Enabling linking queries
- Support or() for chaining queries
- Grouping works, but needs more testing

What is coming in the next phase
- A chart of methods supported and tested from RealmQuery
- A chart of methods supported and tested from RealmList


What is coming after
- Go supporting more methods from RealmQuery and RealmList
- Allow to delete realmModels from their realm