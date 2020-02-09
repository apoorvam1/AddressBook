**AddressBook**

Maven based REST API for creating phone book using SpringBoot and Protobuf

This project creates REST API using Spring Boot to perform below operations:
- Create a new contact
- Update an existing contact
- Delete a contact
- View a contact
- View list of contact names


Uses protobuf to generate POJOs for the addressbook.

*Build management - Maven*

Run `mvn compile` to comile the code base. 

The compiled classes will be generated at the `target` folder. You can also see that the compiled classes for proto files will be generated at `target/generated-sources/protobuf/java/com/project/addressbook/proto`

