# Installation unter Mac OS

Die Installation von GitBook auf einem Mac gestaltet sich einfach.

## Node.js installieren

Die Installation von NodeJS ist notwendig, da GitBook in JavaScript programmiert ist.

* [Homepage von Node.js](https://nodejs.org/en/). Die LTS-Version wird empfohlen.

## GitBook installieren

Mit Node.js wird der *Node Package Manager (npm)* installiert. Das folgende Kommando ist im Terminal einzugeben:

```bash
$ sudo npm install -g gitbook-cli
```

Dadurch wird GitBook global auf dem Mac installiert. Die genaue Dokumentation zu `gitbook-cli` findet sich bei [npmjs](https://www.npmjs.com/package/gitbook-cli).

Um den Erfolg der Aktion zu prüfen, kann das folgende Kommando eingegeben werden:

```bash
$ gitbook --version
CLI version: 2.3.0
GitBook version: 3.2.0
```
