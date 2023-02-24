# voting-app-deployment
Introductory full-stack kubernetes deployment based upon KodeKloud's online learning material
Architecture is based upon a front-to-back end voting application which receives user input within the voting-app. Voting results are then transferred within redis and processed through the worker-app until they are eventually stored inside the postgres db and displayed through the result-app. Both the voting-app and result-app frontend containers are distributed amongst a three unit replicaset for availability purposes.
