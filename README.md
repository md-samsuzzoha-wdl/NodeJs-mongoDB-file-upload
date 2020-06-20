# [*Files upload to MongoDB and Display those file*](https://www.youtube.com/watch?v=3f5Q9wDePzY&list=PLjrjtggw2EDxwzgTWdfxwbEKW_Cu43srx&index=4)

### gridfs-stream

*Easily stream files to and from MongoDB GridFS.*

```npm install gridfs-stream```

[*official docs*](https://www.npmjs.com/package/gridfs-stream)

### method-override

*Lets you use HTTP verbs such as PUT or DELETE in places *
*where the client doesn't support it.*

[*official docs*](https://www.npmjs.com/package/method-override)

### Multer's GridFS storage engine

*GridFS storage engine for Multer to store uploaded files directly to MongoDb.*
*This module is intended to be used with the v1.x branch of Multer.*

```npm i multer-gridfs-storage```

[*official docs*](https://www.npmjs.com/package/multer-gridfs-storage)

### crypto

[*node.js prebuild module*](https://nodejs.org/api/crypto.html)

*The crypto module provides cryptographic functionality that includes a set of *
*wrappers for OpenSSL's hash, HMAC, cipher, decipher, sign, and verify functions.*

## Overview of project

 - mongodb setup 
 - create disk storage with **Multer's GridFS storage engine**
 - create routes for
   1. **loads form(get)** : Rendering page with uploaded previous image
   2. **uploads file to db(post)** : upload a single file and redirect
   3. **display all file in json format(get)** : returning json object from db
   4. **display single file object(get)** : displaying json format
   5. **Display image(get)** : displaying orginal image
   6. **delete files(delete)** : delete by using params