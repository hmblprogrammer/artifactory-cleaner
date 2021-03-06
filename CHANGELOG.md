Artifactory Cleaner CHANGELOG
=============================
This file describes the changes made in each release of `artifactory-cleaner`

## v1.0.5 (May 29, 2020)

 - Check size of archived artifacts to ensure they downloaded properly
 - Depend on `artifactory` gem v3.0.15 which properly follows HTTP redirects
 - Gemspec cleanup
 
## v1.0.4 (May 29, 2020)

 - Fix bug with accepting YAML filter files on the CLI

## v1.0.3 (May 15, 2020)

 - Fix thread deadlocks which occured if exceptions were raised in the discovery worker threads
 - Update to `artifactory-client` 3.0.13 to avoid verbose warnings about deprecated `URI` methods
 
 
## v1.0.2 (February 25, 2020)

 - Fix circular dependency between bundler and gem install
 

## v1.0.1 (February 09, 2020)

 - Initial Public Release