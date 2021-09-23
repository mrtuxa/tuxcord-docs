# Setup Server

## [Download](https://github.com/fosscord/fosscord-server/releases)

This is the stable fosscord-server release.

Download the server release from [GitHub](https://github.com/fosscord/fosscord-server/releases) for your operating system. (Size ~60mb)

Double click the file to start the server. (The first time it takes longer as it needs to setup the server)

You can now access it on [http://localhost:3001](http://localhost:3001).

## With terminal/shell

This is the latest bleeding edge version of fosscord-server, which may have bugs.

You need to install git from [git-scm.com](https://git-scm.com/downloads) or your package manager.

You need to install nodejs from [nodejs.org](https://nodejs.org/) or your package manager.

Now you can clone and start the server by executing this in the terminal/shell:

```
git clone https://github.com/fosscord/fosscord-server
cd fosscord-server
cd bundle
npm run setup
```

You can now access it on [http://localhost:3001](http://localhost:3001)

To increase startup time you can just execute ``npm run start:bundle`` which skips the build process.

## Docker

Optionally if you want to use Docker:

```
git clone https://github.com/fosscord/fosscord-server
cd fosscord-server
docker-compose up
```

You can now access it on [http://localhost:3001](http://localhost:3001)