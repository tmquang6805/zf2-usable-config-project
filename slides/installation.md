## Installation

#### if $wifi: <!-- .element: class="left" -->
```
curl -s https://getcomposer.org/installer | php --
php composer.phar create-project -sdev zendframework/skeleton-application .
```
<br />

#### else: <!-- .element: class="left fragment" -->

$pendrive <!-- .element: class="fragment roll-in" -->

<br />

#### run it: <!-- .element: class="left fragment" -->

Setup your vhost or php 5.4+ <!-- .element: class="fragment" -->
<br />
<pre class="fragment roll-in">
<code class="brainfuck">
php -S 127.0.0.1:8001 -t skeleton-application/public skeleton-application/public/index.php
</code>
</pre>