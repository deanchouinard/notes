Had some trouble getting node going, but these instructions from
[nodesource] worked:(https://github.com/nodesource/distributions#installation-instructions)

As root

    curl -sL https://deb.nodesource.com/setup_6.x | bash -
    apt-get install -y nodejs

Was getting error about backend port not found: inotifywait, so installed:

    apt-get install inotify-tools


