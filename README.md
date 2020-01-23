Chainyard Coding Test Challenge
=============

When completing this coding challenge, please organize your code as if it were going into production, then send us a link to the hosted repository (e.g. Github, Bitbucket...).

### Functional Spec
----------------------------

Create a simple mobile app using React Native that allows a user to **browse blockchain block & transaction data** from the Blockchain.org public API. The user should be able to:

- View a single block
- View a single transaction on a block
- View the latest block

#### UI/UX Design
------------------------

The UI/UX is completely up to you. Be as creative as you want while considering the user's experience, but be prepared to explain your design decisions. You may add additional features if you think the users will find it useful!

### Technical Spec
---------------------------

The architecture for this service will feature only the mobile app front end. Instructions on how to access the Blockchain.org REST API for obtaining data can be found below under the Back-end heading.


#### App

The mobile app should ideally be a Main Screen with navigation to respective block transactions Screen. Take this opportunity to demonstrate your React Native knowledge. App should work in both Android and iOS.


#### Back-end

The Blockchain.org REST API is open to developers and accessible without registering for an account. You can read the API documentation here: https://blockchain.info/api/blockchain_api.

For example: Retrieving data on the latest block can be achieved by hitting the following endpoint: ```https://blockchain.info/latestblock```
This will return a result similar to the example below:

```
{
    "hash":"0000000000000538200a48202ca6340e983646ca088c7618ae82d68e0c76ef5a",
    "time":1325794737,
    "block_index":841841,
    "height":160778,
    "txIndexes":[13950369,13950510,13951472]
 }
```

#### Hosting

When you’re done, publish it somewhere (e.g. expo) and provide us with the link to your hosted application when you submit.


### How We Review
-------------------------

We value quality over feature-completeness. It is fine to leave things aside provided you explain your reasoning. You should consider this code ready for final review with your colleague, i.e. this would be the last step before deploying to production.

The aspects of your code we will assess include:

- **Architecture**: how clean is the separation between the front-end and the back-end?
- **Correctness**: does the application do what was asked?
- **Code quality**: is the code simple, easy to understand, and maintainable? Are there any code smells or other red flags? Is the coding style consistent with the language's guidelines? Is it consistent throughout the codebase?
- **UX**: is the mobile interface / navigation understandable and pleasing to use?

