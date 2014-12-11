## Other config files

module.config.php <!-- .element class="left fragment" -->

<blockquote class="fragment">
    <p class="fragment left">Effective only for module</p>
</blockquote>

<br />
{,*.}{global,local}.php <!-- .element class="left fragment" -->

<div class="half fragment">
    <p>global.config.php</p>

    <blockquote class="fragment">
        <p class="left">
            environment and **not sensitive to security**
        </p>
    </blockquote>
</div>

<div class="half fragment">
    <p>local.config.php</p>

    <blockquote class="fragment">
        <p class="left">
            environment and **sensitive to security**
        </p>
    </blockquote>
</div>