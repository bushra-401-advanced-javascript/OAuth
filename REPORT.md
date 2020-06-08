# OAuth Comparative Analysis

## OAuth Provider Name 
Yahoo provider.

### Research Conducted By: Student Names

Raghad Al-Qaruan
Israa Othman
Bushra Bilal
Fatema Al-Zahraa Owedah

### Overall Score and Comments
#### Score (Out of 10): 10 please :)

#### General Comments
- The application requests authorization to access service resources from the user
- If the user authorized the request, the application receives an authorization grant
- The application requests an access token from the authorization server (API) by presenting authentication of its own identity, and the authorization grant
- If the application identity is authenticated and the authorization grant is valid, the authorization server (API) issues an access token to the application. Authorization is complete.
- The application requests the resource from the resource server (API) and presents the access token for authentication
- If the access token is valid, the resource server (API) serves the resource to the application

#### Pros
* It has ability to share data for users without having to release personal information.

* It is easier to implement and provides stronger authentication.

#### Cons
* If you are adding more extension at the ends in the specification, it will produce a wide range of non-interoperable implementations, which means you have to write separate pieces of code for Facebook, Google, etc.
* If your favorite sites are connected to the central hub and the central account is hacked, then it will lead to serious effects across several sites instead of just one.

### Ratings and Reviews
#### Documentation
Thoughts go here

#### Systems Requirements
Above and beyond 'node' and 'linux', what dependencies or core requirements exist for this framework?
superagent, base-64, bcrypt, cors,dotenv,eslint, express, jsonwebtoken, morgan.
Can it play at AWS/Heroku?
yes in Heroku.

#### Ramp-Up Projections
How long would/should it take a team of mid-junior developers to become productive?Three month.

#### Community Support and Adoption levels
How popular is this framework? What big companies are running on it? How is it "seen" in the general JS community?  Is there an active community of developers supporting and growing it?


### Links and Resources
* [framework](http://xyz.com)
* [docs](http://xyz.com)
* [examples/tutorials](http://xyz.com)

### Code Demos
* [live/running application](http://xyz.com)
* [code repository](http://xyz.com)

### Operating Instructions
If someone were to download your repo (above), what steps do they need to take to run the application
* `npm start`,`nodemon`
* Endpoint: `/oauth`
  * Returns a Token
