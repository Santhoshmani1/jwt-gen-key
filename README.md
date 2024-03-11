# JWT-GEN-KEY

| Zero dependency, lightweight, and fast Node js library for JWT public & private key generation.

## Installation

```bash
npm install jwt-gen-key
```

## Usage
```javascript
import generateKey from "jwt-gen-key";
```

## Example

```javascript
import generateKey from "jwt-gen-key";

const publicKey = generateKey(16);
const privateKey = generateKey(20);

console.log(publicKey); //32 bit string -> 8da266c9804430539c8840d940e58c7a
console.log(privateKey); //40 bit string ->  e3db2c6c9b97f5c4bb9a63745abe33535e04899a

```

## LICENSE

jwt-gen-key is licensed under MIT LICENSE. see [LICENSE](LICENSE) for more details.
