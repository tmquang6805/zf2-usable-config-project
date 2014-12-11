## application.config.php

Enable/Disable ZF2 modules <!-- .element class="left fragment" -->

<pre class="fragment roll-in">
<code class="php">
'modules' => array(
    'Application',
    'ZendDeveloperTools',
    'Backend',
),
</code>
</pre>

Specify autoload config files <!-- .element class="left fragment" -->

<pre class="fragment roll-in">
<code class="php">
'config_glob_paths' => array(
    'config/autoload/{,*.}{global,local}.php',
),
</code>
</pre>

Cache merged config <!-- .element class="left fragment" -->

<div class="fragment half">
    <ul>
        <li class="fragment roll-in">
            <p class="small">'config_cache_enabled' => $booleanValue</p>
        </li>
        <li class="fragment roll-in">
            <p class="small">'config_cache_key' => $stringKey</p>
        </li>
        <li class="fragment roll-in">
            <p class="small">'module_map_cache_enabled' => $booleanValue</p>
        </li>
    </ul>
</div>

<div class="half">
    <ul>
        <li class="fragment roll-in">
            <p class="small">'module_map_cache_key' => $stringKey</p>
        </li>
        <li class="fragment roll-in">
            <p class="small">'cache_dir' => $stringPath</p>
        </li>
    </ul>
</div>