##  making changes

Now that Git is tracking our file. We can make changes to it and Git will notice.

<br>

In your text editor, change `helloWorld.js` then save:

<br>

<p class='terminal'><code>helloWorld.js</code></p>
```javascript
var name = 'Jimmy';

console.log('Hello ' + name);
```

Then add and commit <!-- .element: class="fragment" data-fragment-index="1" -->

```bash
$ git status
$ git add helloWorld.js
$ git commit -m "I made some changes!"
```
<!-- .element: class="fragment" data-fragment-index="1" -->