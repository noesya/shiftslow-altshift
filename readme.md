# AltShift 

## Staging

https://shiftslow-altshift.netlify.app/

## Maquettes

https://www.figma.com/file/1eAUThzx9FhG2zkHaPBFoD/Alt-Shift?node-id=0%3A1

## Hugo
Pour installer Hugo
```
brew install hugo
```
Mise à jour avec
```
brew upgrade hugo
```


## Template hugo osuny
https://github.com/noesya/osuny-hugo-template

Pour faire la mise à jour :
```
git remote add template git@github.com:noesya/shiftslow-altshift.git
git fetch --all
git merge template/main --allow-unrelated-histories
```


## Install

Pour cloner avec le thème
```
git clone git@github.com:noesya/shiftslow-altshift.git --recurse-submodules
```
Pour récupérer le thème
```
git pull --recurse-submodules
```


## Commands

Pour lancer le site
```
yarn
yarn watch
```


## Netlify
Pour déployer le site avec Netlify, penser à ajouter la deploy key.


## Params

Les params principaux sont dans config.yaml du theme, pour en ajouter ou modifier il faut overider dans config/_defaults/config.yaml
```
cdnkey: https://osuny-1b4da.kxcdn.com
cookie_banner:
  enable: true
  blank: true
  page: https://gdpr.eu/cookies/
```
