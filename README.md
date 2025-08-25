# shocker-mc
A minecraft mod that makes a request to `http://<local_ip>/shock/` upon the player losing in-game health points.

Intended for use with a web server that can accept such a request.

# Notes
The `<local_ip>` can be changed easily in `shockermc-client.toml` by modifying `IP Address=<local_ip>`.

Absorption does not count towards health. Initially a bug, now a useful buff.