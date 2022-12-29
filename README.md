# INSTALL crypto-js
Requirements:
<li> Node.js  </li>
<li> npm (Node.js package manager) </li>
<br>
Install by using Command Prompt:

<div style = "background: grey; padding: 0.25rem 1rem; margin: 0.25rem 0 1rem 0; border-radius: 0.25rem; font-family: monospace">npm install crypto-js</div>

# USAGE
### SHA256
 <li style = "list-style:circle"> Import Syntax
 </li>
 <div style = "background: grey; padding: 0.25rem 1rem; margin: 0.25rem 0 1rem 0; border-radius: 0.25rem; font-family: monospace">import sha256 from 'crypto-js/sha256';</div>
 <li style = "list-style:circle"> Usage Syntax
 </li>
 
  <div style = "background: grey; padding: 0.25rem 1rem; margin: 0.25rem 0 1rem 0; border-radius: 0.25rem; font-family: monospace">sha256.SHA256(string)</div>
  The method SHA256(string) of sha256 (see above) returns the hashed result of the input string.
  <br>
  For example, if the input string is "abc" then the hashed result is
  <br>
  "ba7816bf8f01cfea414140de5dae2223b00361a396177a9cb410ff61f20015ad"
  <br>
  The source code has been fully introduced in SHA-256.ts file.