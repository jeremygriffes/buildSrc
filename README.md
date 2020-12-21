# buildSrc

This module provides a starting point for any JVM-based kotlin project by defining the
conventions and language-level dependencies for libraries and applications. 

It should be distributed as a git submodule.

## Setting up a new project

First add the buildSrc module to the project:
```
git submodule add https://github.com/jeremygriffes/buildSrc
```

Declaring application modules:
```
plugins {
    id 'net.slingspot.kotlin-application-conventions'
}
```

Declaring library modules:
```
plugins {
    id 'net.slingspot.kotlin-library-conventions'
}
```

