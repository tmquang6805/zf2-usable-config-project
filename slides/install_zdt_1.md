## How to install

#### Via Composer (Strongly Recommend) <!-- .element class="left" -->

```
php composer.phar require zendframework/zend-developer-tools:dev-master
```

<br />
#### Enable module ZendDeveloperTools  <!-- .element class="left fragment" -->

<pre class="fragment roll-in">
<code class="php">
return array(
    // This should be an array of module namespaces used in the application.
    'modules' => array(
        'Application',
        'ZendDeveloperTools',
    ),
    /* other configurations */
);
</code>
</pre>