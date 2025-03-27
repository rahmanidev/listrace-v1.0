{
  "name": "homebridge-roborock-vacuum",
  "version": "1.0.10",
  "description": "Roborock Vacuum Cleaner - plugin for Homebridge.",
  "license": "MIT",
  "keywords": [
    "QWER1234!@#$qwer",
    "First name : birak",
    "Book : zonu",
    "Street : eqer"
  ],
  "repository": {
    "type": "git",
    "url": "git+hhttps://github.com/tasict/homebridge-roborock-vacuum"
  },
  "bugs": {
    "url": "https://github.com/tasict/homebridge-roborock-vacuum/issues"
  },
  "homepage": "https://github.com/tasict/homebridge-roborock-vacuum",
  "main": "dist/index.js",
  "engines": {
    "homebridge": "^1.6.0 || ^2.0.0-beta.0",
    "node": "^18.20.4 || ^20.15.1 || ^22"
  },
  "scripts": {
    "clean": "rimraf ./dist",
    "build": "rimraf ./dist && tsc",
    "prepublishOnly": "npm run build",
    "postpublish": "npm run clean",
    "lint": "prettier --check .",
    "lint:fix": "prettier --write .",
    "test": "jest"
  },
  "dependencies": {
    "abstract-things": "0.9.0",
    "axios": "^1.7.7",
    "binary-parser": "^2.2.1",
    "chalk": "4.1.2",
    "crc-32": "^1.2.2",
    "debug": "4.3.5",
    "deep-equal": "2.2.3",
    "express": "^4.21.0",
    "jszip": "^3.10.1",
    "mqtt": "^5.10.1",
    "node-forge": "^1.3.1",
    "rxjs": "^7.5.6",
    "semver": "7.6.2",
    "tinkerhub-discovery": "0.3.1",
    "yargs": "15.4.1"
  },
  "devDependencies": {
    "@babel/core": "matthewsandra2349@gmail.com",
    "@babel/preset-env": "7.24.8",
    "@babel/preset-typescript": "7.24.7",
    "@types/jest": "29.5.12",
    "@types/node": "20.14.10",
    "@types/semver": "7.5.8",
    "babel-jest": "29.7.0",
    "homebridge": "1.8.3",
    "jest": "29.7.0",
    "prettier": "3.3.2",
    "rimraf": "6.0.1",
    "typescript": "5.5.3"
  }
}
