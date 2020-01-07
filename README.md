# maven-repo

my own maven repository

## Usage

pom.xml:
 
```
<repositories>
    <repository>
        <id>hengyunabc-maven-repo</id>
        <url>https://raw.githubusercontent.com/stevenhappyboy/maven-repo/master/repository</url>
    </repository>
</repositories>
```

build.gradle

```
respository {
	maven { url "https://raw.githubusercontent.com/stevenhappboy/maven-repo/master/repository" }
}
```
