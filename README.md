# INSTALL crypto-js
Requirements:
<li> Node.js  </li>
<li> npm (Node.js package manager) </li>
<br>
Install by using Command Prompt:

```
npm install crypto-js
```
# USAGE
## SHA256
 <li style = "list-style:circle"> Import Syntax
 </li>

  
```
import sha256 from "crypto-js/sha256";
```

 <li style = "list-style:circle"> Usage Syntax
 </li>

```
sha256(string)
```

  The method sha256(string) returns the hash result of the input string. To get the result as a string, just use the toString() method
    
```
sha256(string).toString()
```

  For example, if the input string is "abc" then the hashed string result is
  <br>
  "ba7816bf8f01cfea414140de5dae2223b00361a396177a9cb410ff61f20015ad"
  <br> <br>
  The source code has been fully introduced in SHA-256.ts file.
  ## SHA512
  SHA512 are quite similar to SHA256, you can follow the source code introduced in SHA-256.ts to get more details. 