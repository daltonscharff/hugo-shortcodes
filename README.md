# hugo-shortcodes
A collection of shortcodes created for the Hugo framework. 

## Contents
File | Description | Example
-|-|-
podcast.html | Generates an element containing the podcast cover art and details | {{< podcast feed="https://feeds.99percentinvisible.org/99percentinvisible" >}}
repos.html | Generates elements for each repository in a user's GitHub account | {{< repos user="daltonscharff" >}}

## Usage
Download the file of the shortcode you would like to use and place it within the *layouts > shortcodes* directory of your Hugo project.
```
my-hugo-site/
├─ archetypes/
├─ assets/
├─ content/
├─ data/
├─ layouts/
│  ├─ shortcodes/
│  |  ├─ *place shortcode file here*
├─ resources/
├─ static/
├─ themes/
├─ .gitignore
├─ config.yaml
├─ README.md
```