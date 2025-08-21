Follow these steps to setup ```urplans```:

### 1. Install dependencies

Make sure the following are installed on your system:

- Java Development Kit (JDK) 21 or later (includes the JRE)  
- Apache Maven 3.6+  
- Git (for cloning the repository)

### 2. Clone the repository

Use one of these commands to clone URPlans:

- via HTTPS:
   ```
   git clone https://github.com/MaiFOSS/urplans.git
    ```
- via SSH:
   ```
   git@github.com:MaiFOSS/urplans.git
    ```
- via Github CLI:
   ```
   gh repo clone MaiFOSS/urplans
    ```

Alternatively, you can clone via your IDE’s Git integration.

### 3. Build the project

3.1. Move to the project's directory

```
cd urplans
```

3.2 Secondly, build the file:

```
mvn -DskipTests clean package
```

The output should be similar to this:

```
[INFO] Scanning for projects...
[INFO] 
[INFO] --------------------< org.maifoss.urplans:urplans >---------------------
...
[INFO] BUILD SUCCESS
...
```

The built JAR will be at ```target/urplans-1.0-SNAPSHOT.jar```

You’re all set! Run URPlans with:

```
java -jar target/urplans-1.0-SNAPSHOT.jar
```

[Usage →](./usage.md){.md-button .md-button--primary .md-button--raised}
