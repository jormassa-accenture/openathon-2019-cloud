<p align="center">
    <img src="../../resources/header.png">
</p>

# Lab 03.A - Hello World in Spring Boot

<br/>

<p align="center">
<img src="./resources/spring-boot-logo.png" width="500">
<br/>
Welcome Spring!
</p>
<br/>

## Goals and results
The goal of this laboratory is create a microservice in Java using [Spring Boot](https://spring.io/projects/spring-boot). Finally, we will have an API with a endpoint **Get /hello?name={name}**  

<br/>

## Prerequisites

Before start to coding, we need install some tools:

1. [**Java 8** or mayor](#how-to-install-java-8)

2. [**Maven 3**]()

3. [**Eclipse Java Enterprise**]()
   1. [**Spring Tools 4 - for Spring Boot**]()

<br/>

### How to install Java 8

You can use Oracle JDK, in that case, you have register in Oracle, or use OpenJDK, the open version of JDK (that we will use).


#### Check if we already have Java

We can check if we have installed java with the next command:

```sh
java -version
```

If you see a message similar to *version "1.x"*, where *x* is mayor or equal to 8, skip this section and go to [Install maven 3](#how-to-install-maven-3).

If we see a message similar to *Command not found*, we need install java, so go to [Install Java 8](#install-java-8).


<p align="center">
    <img src="./resources/java-version-out.png">
    In my case, I use OpenJDK 1.8.0_222
</p>

#### Install Java 8

#### Windows

1. Download OpenJDK 8 from next link: https://adoptopenjdk.net/
2. Extract the zip in the folder you want.
3. Set the value for **JAVA_HOME**. For that, open cmd and execute next command:

    ```cmd
    setx /m JAVA_HOME "<full_path_your_folder>"
    ```

4. Execute *java -version* to verify the installation.

### Mac

1. Download OpenJDK 8 from next link: https://adoptopenjdk.net/
2. Extract the zip in the folder you want.
3. Set the value for **JAVA_HOME**. For that, open terminal and execute next command:

    ```sh
     export JAVA_HOME="<full_path_your_folder>"
    ```

4. Execute *java -version* to verify the installation.

### Linux

1. Open a terminal.
2. Execute the next command:

   ```sh
    sudo apt-get install openjdk-8-jdk
   ```

3. Execute *java -version* to verify the installation.

<br/>

### How to install maven 3

You can check if you have already maven 3 installed:

```sh
mvn --version
```

<p align="center">
    <img src="./resources/mvn-version-out.png">
    In my case, I have Maven 3.6.1
</p>

#### Windows

1. Download maven from next link: https://maven.apache.org/download.cgi
2. Extract the file downloaded.
3. Add *<your_maven_directory\bin>* to PATH:
   1. Press *WinKey + Pause*
   2. Select the *Advanced tab*
   3. Click on *Environment Variables* button
   4. Adding or selecting the *PATH variable* in the user variables with the value **<your_maven_directory\bin>**.

#### Mac and Linux

1. Download maven from next link: https://maven.apache.org/download.cgi
2. Extract the file downloaded.
3. Add pache-maven-3.6.2\bin to PATH. Open a terminal and execute:

   ```sh
   export PATH=<your_maven_directory\bin>:$PATH
   ```

More info in https://maven.apache.org/install.html.

### How to install Eclipse Enterprise

The process is very similar in Windows, Mac and Linux.

#### Install Eclipse

1. Download Eclipse from https://www.eclipse.org/downloads/
   
   <p align="center">
    <img src="./resources/download_eclipse.png">
</p>

2. Execute the installer and select **Eclipse IDE for Java EE developers**

<p align="center">
    <img src="./resources/eclipse_installer.png">
</p>

#### Install Spring Boot Plugin

1. Open Eclipse
2. Click in *Help > Eclipse Marketplace...*
   
   <p align="center">
    <img src="./resources/eclipse_marketplace.png">
    </p>

   1. In the search bar, we type *spring boot*
   2. Click *Install* in *Spring Tools 4*

    <p align="center">
    <img src="./resources/spring_tools.png">
    </p>


<br/>

## Create a new Spring Boot Application

For creating a basic Spring Boot Application, we will use https://start.spring.io/ through the eclipse Wizard:

1. Open Eclipse.
2. Click in *File > New > Other...*
   
   <p align="center">
    <img src="./resources/new_project.png">
</p>

3. In the search bar, type *Spring*.
4. Click in *Spring Starter Project* and *Next*.
   
   <p align="center">
    <img src="./resources/spring_wizard.png">
</p>

5. In *Name*, the name of your project and *Click in Next*.

<p align="center">
    <img src="./resources/name_project.png">
</p>

6. In the search bar, we type *Spring Web* and select it. This is the basic dependency for any Spring boot project.
7. Click in Finish.

<p align="center">
    <img src="./resources/dependencies.png">
</p>

## Struct the project
## Add a new Controller
## Add a new Service
## Hello Jos!

<br/>

[< Lab 03 - Creando un HelloWorld ](../../lab-03)>

<p align="center">
    <img src="../../resources/header.png">
</p>

