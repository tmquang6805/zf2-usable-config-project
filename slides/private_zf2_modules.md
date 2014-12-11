## Private ZF2 Modules

<br />
#### Update composer file <!-- .element class="left" -->

```json
"repositories": [
    {
        "type": "vcs",
        "url": "private-repository"
    }
],

```

```json
"require": {
    "private-modulename": "dev-master"
}
```

<br />
#### Run composer update <!-- .element class="left fragment" -->

<pre class="fragment roll-in">
<code class="php">
php composer.phar update
</code>
</pre>