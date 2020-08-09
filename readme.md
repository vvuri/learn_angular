## Learn Angular

### Install
```bash
$ npm install -g @angular/cli
```
for windows:
```
$ Get-ExecutionPolicy -List
$ Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
$ ng help
```

### Create first app
```bash
$ ng new angular-first
```
without routing, with SCSS
```bash
$ cd .\learn_angular\
$ npm start
```
Browser: http://localhost:4200/

### CLI
- ng generate component xyz
- ng add @angular/material
- ng add @angular/pwa
- ng test
- ng build --prod
