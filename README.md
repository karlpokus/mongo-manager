# mongo-manager
Shell scripts for managing replica sets, clusters. Clone to `home/` for filepaths to work.

# Ops

### rs-not-forked
- 3 mongod:s
- no auth
- run `bash init` to create data folders
- run `bash start[n]` to start each mongod
- logs to stdout
- replica set name is `rs0`
- end by sending interupt
- `rs.initiate` && `rs.add` in shell

### rs-forked
- same as above but forked
- logs to file
- use `stopAll` to end all

# License
MIT
