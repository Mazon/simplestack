https://superuser.com/questions/230694/how-can-i-push-a-git-repository-to-a-folder-over-ssh or gitea

1. Develop in monorepo
2. Push to git
3. Deploy as canary



Arch

Nginx OR HAproxy 
Applications hosted in /opt/simplestack
Postgres hosted on 3 nodes per DC. 
2 Datacentres
Load Balancing by DNS round robin
create service run golang app. Simple wrapper that gives application a port number and ENV. `LISTEN_PORT`, possible HAproxy config.
sample service, write a simple hello world app.
