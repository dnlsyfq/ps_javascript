
### Start 

1. npm install -g expo-cli
2. expo init <project name> --npm
3. cd <project name>
4. npm start




### Android Emulator 



### expo 

expo login


expo client:install:android
expo client:install:ios
expo publish

expo build:android
expo build:ios
expo build:web

### expo api reference

* AsyncStorage
* SQLite

### expo cli

expo start 

### Deploy
* codepush - ota 
* fastlane

### Beta Deploy
* testflight
* crashlytics

### Testing
* Jest
* Detox

### Push notification
* One signal
* Firebase cloud messaging
* aws amplify

### Boilerplate
* ignite

### 3rd party
* react native camera
* react native fingerprint scanner
* react native touch id
* react native video
* react navigation

---

* ./
```
npm install
npm run start
```

```
<script src="./utils.js"></script> # function file 
<script src="./home.js"></script>   # execution file 

</body>
```

* variables

```
let name = <val>, name = <val> ;
```

* numbers
  * (float + float).toFixed(2) // to decimal places but return string
  *  +(float + float).toFixed(2) // to decimal places return float

* string
  * escape notation mozilla 
  * 
```
let name = `Hello ${variable}`;
```
  * var.toLowerCase()
  * var.toUpperCase()
  * var.substring(int);
  * var.length;
  
*converting string and no.
 * numvariable.toString()
 * Number.parseFloat("stringnumber")

*boolean
    * true / false
    * !true
    * !false

* undefined
```
let variable;
```

* null
```
let varialbe = null;
```

* object
```
let person = {
    firstName:'John',
    lastName : 'Doe'
}

person.firstName
```

* if 
```
if( <conditional operator> ){
}
```

* if ... else
```
if(){

} else {

}
```

* if(){} ... else if (){} else {}
* ternary operator
    ```
  let message = (price > 10)? 'expensive':'cheap'
  ```
  
* loop
```
for(let i = 0; condition; i++){

}

while(condition){
    
}

do {
} while()
```