# getMongoData-parser
Parses MongoDB getMongoData.js output and produces an HTML report and/or inserts a summary into MongoDB, exports to Excel


Quickstart
----------
1. Download the jar file:
```
wget -O mongo-util.jar https://github.com/mhelmstetter/getMongoData-parser/blob/master/bin/getMongoDataParser.jar?raw=true
```
2. Create an alias, run the following and/or add it to your `.zprofile` or `.bashprofile` (update the path to the correct location!)
```
alias getmongodata="java -jar ${HOME}/git/getMongoData-parser/bin/getMongoDataParser.jar"
```
3. Run it!
```
getmongodata -f getMongoData.log
```
or
```
java -jar getMongoDataParser.jar -f getMongoData.log
```
the ouptput will be written to a file of the same name with a `html` extenstion, e.g. getMongoData.html for the above example.
