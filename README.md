## commands

```s
# Create a new lerna repo or upgrade an existing repo to the current version of Lerna.
lerna init

# Bootstrap the packages in the current Lerna repo. Installing all their dependencies and linking any cross-dependencies.
lerna bootstrap

# Create a new release of the packages that have been updated. Prompts for a new version and updates all the packages on git and npm.
lerna publish

#Check which packages have changed since the last release.
lerna changed

#Diff all packages or a single package since the last release
lerna diff [package?]

#Run an npm script in each package that contains that script.
lerna run [script]

```
