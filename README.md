# dot
DNS over TLS

This script requires Docker to operate.

# Installation
```
$ git clone https://github.com/geraldvillorente/dot.git
$ cd dot/
$ chmod +x dot
$ mv dot /usr/local/bin/
```

# Configuration
Update `/etc/resolv.conf` and add this line:
```
nameserver 127.0.0.1
```

# Usage
Run the command like this:
```
$ dot [DOMAIN]
```
Example:
```
$ dot google.com 
```
