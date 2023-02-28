# init TS Config
Initiate a tsconfig file
```bash
tsc --init
```
# Ts config setup
```js
{
"compilerOptions":{
"rootDir":"./src"
"outDir":"./build/js"
"target":"es2016"
},
"include":["src" ] //ts will ignore any ts file that is not inside src directory
}

```
# Watch ts file
```bash
tsc -w
```