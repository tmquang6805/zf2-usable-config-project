## Configuration in ZF2

application.config.php <!-- .element class="left fragment" data-fragment-index="1" -->

<blockquote class="fragment" data-fragment-index="2">
    <ul>
        <li class="fragment roll-in" data-fragment-index="3">
            <p>Enable/Disable ZF2 modules </p>
        </li>
        <li class="fragment roll-in" data-fragment-index="4">
            <p>Specify autoload config files</p>
        </li>
        <li class="fragment roll-in" data-fragment-index="5">
            <p>Cache merged config</p>
        </li>
    </ul>
</blockquote>

<br />
module.config.php - config/autoload/{,*.}{global,local}.php <!-- .element class="left fragment" data-fragment-index="6" -->

<blockquote class="fragment" data-fragment-index="7">
    <ul>
        <li class="fragment roll-in" data-fragment-index="8">
            <p>Merge configs runtime (if not cached) </p>
        </li>
        <li class="fragment roll-in" data-fragment-index="9">
            <p>**Right Application** Config</p>
        </li>
    </ul>
</blockquote>