# digilib-frontend-template
Template for a customized digilib frontend.

## How to build and run digilib (using Java)

Requirements:
* [git](https://git-scm.com/)
* [Java JDK](http://www.oracle.com/technetwork/java/javase/downloads/index.html) version 8 or later
* [Maven](https://maven.apache.org/) version 3 or later

```
git clone https://github.com/robcast/digilib-frontend-template.git
cd digilib-frontend-template
mvn jetty:run-exploded
```
Then open http://localhost:8080/digilib/digilib.html in your browser.

Please see the [configuration instructions](https://robcast.github.io/digilib/digilib-config.html)
and the full [build and install documentation](https://robcast.github.io/digilib/build-maven.html).

## Customize digilib

`static.html` and `embedded.html` are simple examples and `jquery/digilib-dev.html` is a sample version of the 
digilib standard viewer.

Please check https://github.com/robcast/digilib for code, documentation, and help.
