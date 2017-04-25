# nexus-stack
Nexus Swarm Stack

- Remember to set the secret admin password,

echo "AdminPassword" | docker secret create nexusadminpasswd -

Also for persistence create a directory on the node that nexus runs ...

sudo mkdir -p /opt/nexus
sudo chown -R 200 /opt/nexus     (This matches the docker user id)

to access https://nexus.outcome-hub.com/nexus/
