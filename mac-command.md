### SSH

Forward (tunneling) all traffic to a spesific port through ssh:
- `ssh -N -L localhost:8080:localhost:8080 username@remote.example.com`

If you also want to forward all traffic through ssh:
- `ssh -N -D 9001 username@remote.example.com`
