

## Findpets server


Server-side repo for the Findpets adoption app. Findpets is a first come first serve pet adoption app. Users create an account, and will be placed in a line. Adoption listings are populated one at a time, when users are at the front of the line, they will only able to select either the next cat or dog. 

The server was built using express, node, and Queue data structure. The queue is generated with test-users and when users enter their name. The tests users are re-enqueued to prevent "empty lines". Animals are also re-enqueued after adoption to prevent an "empty shelter". 

## Details

* The live app can be found at: [https://findpets.now.sh/](https://findpets.now.sh/)

* Heroku deployment: [https://shrouded-cove-70604.herokuapp.com/api](https://shrouded-cove-70604.herokuapp.com/api)

* Client Repo: [https://github.com/nphiukhao/findpets-client.git](https://github.com/nphiukhao/petful-client.git)

* Server Repo: [https://github.com/nphiukhao/findpets-server.git](https://github.com/nphiukhao/findpets-server.git)

* Pair: Preet Singh and Nancy Phiukhao

## Technology

* React
* Node
* Express
* HTML5
* CSS3```
