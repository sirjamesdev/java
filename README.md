# Java

## Install Java
We need install [sdkman](https://sdkman.io) (The Software Development Kit Manager) 


## Install [SDKMAN](https://sdkman.io/install)

```
$ curl -s "https://get.sdkman.io" | bash
$ source "$HOME/.sdkman/bin/sdkman-init.sh"
$ sdk version
```

### List java

```
$ sdk list java
```

 ### Latest Stable
Install the latest stable version of your SDK of choice (say, Java JDK) by running the following command:

```
$ sdk install java
```

### Switching between Java versions

```
$ sdk use java <version>
```

### Installing other tools
```
$ sdk install maven
$ mvn -version
$ sdk install gradle
```

## IntelliJ IDEA Community Edition
In order to install IntelliJ IDEA, you will first need to navigate to jetbrains.com/idea. From here, you can click on the “Download” button, and you’ll be redirected to the download page.

You’ll be provided with two available editions to download: The free Community edition and the paid Ultimate edition. We’ll be installing the Community edition.
