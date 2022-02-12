# Introduction to Web Development

For the code school intro course
@startuml component
actor client
node app
database db

db -> app
app -> client
@enduml
