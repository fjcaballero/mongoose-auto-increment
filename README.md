# mongoose-auto-increment Fixed for mongoose v7.x

> Mongoose plugin that auto-increments any ID field on your schema every time a document is saved.

---

> Forked from [mongoose-auto-increment](https://github.com/chevtek/mongoose-auto-increment) to fix the callback deprecation introduced in mongoose.7.x  
> Just changed the callbacks into the then/catch form  
> You can use this project instead of the old one by changing your package.json like follows:  
```
"dependencies": {
    "mongoose": "^7.0.4",
    "mongoose-auto-increment": "fjcaballero/mongoose-auto-increment"
}
```
