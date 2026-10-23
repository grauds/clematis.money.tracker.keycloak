# Clematis Keycloak Theme

[![Release](https://github.com/grauds/clematis.money.tracker.keycloak/actions/workflows/release.yml/badge.svg)](https://github.com/grauds/clematis.money.tracker.keycloak/actions/workflows/release.yml)


Simple customization of the [Keycloakify](https://github.com/keycloakify/keycloakify) 
[starter theme](https://github.com/keycloakify/keycloakify-starter)
used for [Clematis Money Tracker](https://github.com/grauds/money.tracker.ui) 
application branding.

The original [documentation](https://docs.keycloakify.dev/css-customization) for the theme template.

## Building the theme

You need to have [Maven](https://maven.apache.org/) installed to build the theme (Maven >= 3.1.1, Java >= 7).  
The `mvn` command must be in the $PATH.

-   On macOS: `brew install maven`
-   On Debian/Ubuntu: `sudo apt-get install maven`
-   On Windows: `choco install openjdk` and `choco install maven` (Or download from [here](https://maven.apache.org/download.cgi))

```bash
npm run build-keycloak-theme
```

Note that by default, Keycloakify generates multiple .jar files for different versions of Keycloak.  
You can customize this behavior, see documentation [here](https://docs.keycloakify.dev/features/compiler-options/keycloakversiontargets).

## Updating the template

The repository is updated from the [Keycloakify Starter](https://github.com/keycloakify/keycloakify-starter).
