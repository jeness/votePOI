# A role voting app project by node.js, MongoDB and React

## Dependencies
1. Install homebrew and nodejs
```
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install node
```
2. Install mongodb
```
brew update
brew install mongodb
```
+ After downloading Mongo, create the “db” directory. This is where the Mongo data files will live. You can create the directory in the default location by running mkdir -p /data/db
+ Make sure that the /data/db directory has the right permissions by running 
```
sudo chown -R `id -un` /data/db
```
+ Run `mongod` in the terminal to start the the Mongo daemon, this step starts the Mongo serever.
3. Install gulp
```
npm install --global gulp-cli   //global install
npm install --save-dev gulp@next //run at the level of dir as same as package.json
```
4. Install bower
```
npm install -g bower
```

## Usage
+ terminal 1 - run mongodb
```
mongod
```
+ terminal 2 
```
gulp
```
+ terminal 3
```
npm run watch
```