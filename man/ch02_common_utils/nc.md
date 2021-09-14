# NetCat

There are basically 3 different releases of command `nc`: gnu-netcat, openbsd-netcat and nmap-ncat. **Their sytanxes differ**.

The following chart compares those different sytanxes between them.

| gnu        | openbsd     | ncat        | meaning             |
|------------|-------------|-------------|---------------------|
| -lp PORT   |             | -l PORT     | Listen to PORT      |
| -w TIME    |             | -w TIME     | Wait time out       |
|            |             | -e CMD      | Exec command        |
|            |             | -c CMD      | Exec cmd w/ /bin/sh |
| -v         | -v          | -v          | Version             |
