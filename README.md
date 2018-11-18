run `npm start` or `docker-compose up` to start application in development mode.

run `npm run stop` or `docker-compose down` to stop application.

run `npm run swarm:init` or `docker swarm init` to create a swarm in development mode. run `docker swarm init --advertise-addr <MANAGER-IP>` to create a swarm on a remote host.

run `npm run stack:deploy` or `docker stack deploy -c docker-compose.stack.yml jira` to deploy the stack onto the swarm.

run `npm run stack:remove` or `docker stack rm jira` to remove the stack from the swarm.

run `npm run swarm:leave` or `docker swarm leave --force` to leave the swarm.