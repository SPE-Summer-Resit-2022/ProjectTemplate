# SPE summer resit project template

## Overview

This template is the skeleton project that acts as the starting point for the SPE summer resit assignment.  
**Note:** that on MS Windows, you might need to replace `./mvnw` with `.\mvnw` in the following commands.

## Building the project

You can compile all of the source code in the project (which is located in `src/main/java`) using the following command:
```
./mvnw clean compile
```

## Running test cases

Run all of the test scripts (which are located in `src/test/java`) using the following command:
```
./mvnw test
```

## Manually running the Server and Client

You can start the server using the following command:
```
./mvnw exec:java@server
```

In a separate terminal, run the client using the following command:
```
./mvnw exec:java@client -Dexec.args="username"
```
Where `username` is the the name of the player
