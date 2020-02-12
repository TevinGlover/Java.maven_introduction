# Download maven

[Download](https://maven.apache.org/download.cgi)


# Unpack

```
tar xvzf apache-maven-3.6.3-bin.tar.gz
sudo mv apache-maven-3.6.3 /usr/local/
```


# Add to PATH

Using your editor of choice update .bash_profile.
```
vim ~/.bash_profile
```

Edit the bash profile so that the location of the apache bin folder is included in the the path variable.
```
export PATH="/usr/local/apache-maven-3.6.3/bin:$PATH"
```

Re-load bash profile.
```
source ~/.bash_profile
```


# Validate 

```
mvn --version
```


# Complete the Maven in 5 Minutes tutorial

[Maven in 5 minutes](https://maven.apache.org/guides/getting-started/maven-in-five-minutes.html)