Install MongoDB

https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/

- Download mongodb-osx-ssl-x86_64-3.4.3.tgz
  Download the binaries from https://www.mongodb.com/download-center.

- tar -zxvf mongodb-osx-x86_64-3.4.3.tgz

- mkdir -p mongodb
  Jeremys-MacBook-Pro:mongodb Jeremy$ pwd
  /Users/Jeremy/Documents/richard/mongodb

- cp -R -n mongodb-osx-x86_64-3.4.3/ mongodb

- Ensure the location of the binaries is in the PATH variable.
  vi .bash_profile
  :export PATH="/usr/local/mysql/bin:/Users/Jeremy/Document/richard/mongodb/bin:$PATH"

Run MongoDB

- mkdir -p /data/db
  cd /
  sudo chmod 777 data
  cd data
  sudo chmod 777 db

- cd /Users/Jeremy/Documents/richard/mongodb/bin
  ./mongod

MongoDB Quick Start 

http://mongodb.github.io/node-mongodb-native/2.2/quick-start/quick-start/

- mkdir myproject
  cd myproject

- npm init

- npm install mongodb --save

- Start MongoDB as above in "Run MongoDB"

- node app.js 

