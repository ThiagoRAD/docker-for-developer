# Multiple networks

- Let's pretend we have two different docker networks, and a local application running at my machine
- The simpler way for them to communication would be from using a host.docker.internal (a common address)
- at windows for example, we would have to edit /etc/hosts

### Add to hosts file
``127.0.0.1 host.docker.internal``
