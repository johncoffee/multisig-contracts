
### Programmel


Overordnet 

1. Vi skal have installeret NodeJS og package manageren NPM. NPM er en del af NodeJS, 
   og bliver installeret samtidig
2. package manageren npm bruger vi til at installere Truffle frameworket
3. Derefter skal vi hente kodebasen fra github og installere projektets egne dependencies,
   bl.a. Ganache, værktøjet til at starte en test-blockchain


##### Links til dokumentation

- [NodeJS](https://nodejs.org/)
- [Truffle](https://truffleframework.com/docs/truffle/overview)
- [Ganache](https://truffleframework.com/docs/ganache/quickstart)


# Windows

1. Hent og installer NodeJS version 10.x.x fra http://nodejs.org/
2. Åben en PowerShell og prøv `npm version` der vil indikere om npm fungerer korrekt
3. Kør kommandoen `npm install -g truffle` for at installere Truffle (-g for  'globalt' på maskinen).
4. Prøv kommandoen `truffle` for at teste at truffle er installeret
5. Hent kodebasen fra github, navigér hen til mappen i en PowerShell og kør
   `npm install` for at installere projektets egne dependencies. Bl.a. Ganache
6. Prøv kommandoen `node dist/cli.js`, for at teste at NodeJS er starter vores kommandoprompt værktøj


# Mac 

1. Hent og installer NodeJS version 10.x.x fra http://nodejs.org/
2. Åben en PowerShell og prøv `npm version` der vil indikere om npm fungerer korrekt
3. Kør `npm install -g truffle` for at installere Truffle (kræver muligvis administrator-rettigheder)
4. Hent kodebasen fra github, navigér hen til mappen i en PowerShell og kør
   `npm install` for at installere projektets egne dependencies. Bl.a. Ganache 
5. Prøv kommandoen `node dist/cli.js`, for at teste at NodeJS er starter vores kommandoprompt værktøj


### Linux(?)

Vi har ikke testet på Linux men det burde være samme fremgangsmåde som Mac OSX.
