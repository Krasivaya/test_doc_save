# SAVE

Save is a digital platform that financially empowers saving groups.

SOS

# Table of Contents 📑

- [Features](#features-rocket)
- [API Endpoints](#api-endpoints-droplet)
- [Technologies Used](#technologies-used-gear)
- [Accessibility](#accessibility-globe_with_meridians)
- [Bugs](#bugs-bug)
- [Contributors](#contributors-two_men_holding_hands)

# Features :rocket:

### User:

1. [x] User can create an acoount.
2. [x] User can sign in the account.
3. [x] User can make savings
4. [x] User can view savings balance
5. [x] User can make loans
6. [x] User can view loan balance
7. [x] User can make a group
8. [x] User can invite others to join group
9. [x] User can make a project
10. [x] User can become an agent
11. [x] User can create an organisation


### Group:

1. [x] A group belongs to an organisation
2. [x] A group belongs to a project
3. [x] A group has cycles
4. [x] A group can make savings
5. [x] A group can make loans
6. [x] A group can make funds
7. [x] A group can view its wallet balance
8. [x] A group can make withdrawals
9. [x] A group member takes saving fines
10. [x] A group member takes fund fines
11. [x] A group member takes attendance delays fines
12. [x] A group member takes meeting absence fines
13. [x] Group admin can update/delete a group


# API Endpoints :droplet:

### Auth

| Endpoint              | Method | Description                      |
| --------------------- | ------ | -------------------------------- |
| /auth/signup          | POST   | User can create an account       |
| /auth/login           | POST   | User can sign in the account     |
| /auth/logout          | POST   | User can sign out of the account |
| /auth/change_password | POST   | User can change the password     |

### User

| Endpoint    | Method | Description                            |
| ----------- | ------ | -------------------------------------- |
| /users      | POST   | User can be/create a group admin       |
| /users      | GET    | User can retrieve group admins         |
| /users/{id} | GET    | User can retrieve a single group admin |
| /users/{id} | PUT    | User can update group admin            |
| /users/{id} | DELETE | User can delete a group admin          |


### Group

| Endpoint                                 | Method |   Description                      |
| ---------------------------------------- | -------|  ----------------------------------|
| /groups                                  | POST   | Create a new group                 |
| /groups/{group_id}/invites               | POST   | Invite a member to the group       |
| /groups/{group_id}/invites/{invite_id}/  | PUT    | accept an invitation of a group    |
| /groups/{id}/balance                     | GET    | Get my group saving balances       |
| /groups/{id}/requests                    | GET    | Create Requests for a group        |
| /groups/{group_id}/leave                 | DELETE | Leave a group                      |


# Technologies Used :gear:

- Nodejs / Express
- Express
- Postgres Boiterplate

# Accessibility :globe_with_meridians:

| Nº  | Components                | Avatar |
| --- | ------------------------- | ------ |
| 1   | Mobile App(Android / IOS) | 📱     |
| 2   | Mobile USSD               | 📟     |
| 3   | Web App                   | 💻     |

# Bugs :bug:

No known bugs. If you find any, please reach out.

# Contributors :two_men_holding_hands:

Special thanks goes to these wonderful people

| Avatar                                                                                                         | Contributor Name                                        |
| -------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------- |
| <img src="https://gitlab.com/uploads/-/system/user/avatar/4040261/avatar.png?width=400" width="50px">          | [Olivier M. Esuka](https://gitlab.com/oesukam)          |
| <img src="https://gitlab.com/uploads/-/system/user/avatar/4968818/avatar.png?width=400" width="50px">          | [Joel Atiamutu](https://gitlab.com/joelatiam)           |
| <img src="https://gitlab.com/uploads/-/system/user/avatar/3209692/avatar.png?width=400" width="50px">          | [Elie Mugenzi](https://gitlab.com/eliemugenzi)          |
| <img src="https://secure.gravatar.com/avatar/a1abe9acceae536a76bc797bc974bf9f?s=800&d=identicon" width="50px"> | [Abraham Kamau](https://gitlab.com/a-braham)            |
| <img src="https://secure.gravatar.com/avatar/cf7594dc4e007e6163b450db38ce871b?s=800&d=identicon" width="50px"> | [chirchir](https://gitlab.com/Kibetchirchir)            |
| <img src="https://gitlab.com/uploads/-/system/user/avatar/4968817/avatar.png?width=400" width="50px">          | [Grace lungu](https://gitlab.com/gracelungu)            |
| <img src="https://gitlab.com/uploads/-/system/user/avatar/3351434/avatar.png?width=400" width="50px">          | [Benedicte MUSABIMANA](https://gitlab.com/BeneMusa)     |
| <img src="https://gitlab.com/uploads/-/system/user/avatar/3559509/avatar.png?width=400" width="50px">          | [crycetruly](https://gitlab.com/crycetruly)             |
| <img src="https://secure.gravatar.com/avatar/1933b67d72df8d90de80b52bdcd545c6?s=800&d=identicon" width="50px"> | [MutabaziAlleluia](https://gitlab.com/mutabazialleluia) |
| <img src="https://secure.gravatar.com/avatar/353a2aa4928797cf0bd10c20cd03cd29?s=800&d=identicon" width="50px"> | [Sharon_bosire](https://gitlab.com/sharonbosire4)       |
