<p align="center">
<img src="https://i.imgur.com/GiUmQLl.png" style="align-items: center; width: 350px"><br>
<img src="https://img.shields.io/badge/Release-0.0.0-blue">
</p>

# About
<b>myJDB is a simple JSON Database that works with keys and values storage.<b>

# Installiation 
Use latest version of node. Package MUST be installed global.
```
npm i myjdb
```

# Example Usage
```js
const myJDB = require('myJDB');
const jdb = new myJDB('/jdb.json');

jdb.create('key', 'key value')

jdb.import('key');

jdb.remove('key');
```

# Docs


## .create() 
`Creates a key and a key value`
## .import() 
`Grabs the value from a key`
## .hasKey() 
`Checks key`
## .remove() 
`Deletes the key`
## .removeAll()
`Clears keys`
## .JSON() 
`JSON Storage`
## .JSON({data})
`Replaces JSON`
## .sync() 
`Sync to disk`

# Links
[NPM](https://www.npmjs.com/package/myJDB)<br>
[Developer Profile @Discord](https://discord.com/users/852766506756210688)<br>

# Help
If you need any help with this package, you can contact [author](https://discord.com/users/852766506756210688)
