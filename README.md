# MDLCode extension for PHPStorm and Intellij IDEA (issue tracker)

<p>Provides support for <a href="https://moodle.org">Moodle</a> development for PHPStorm and IntelliJ IDEA.</p>

<p>This plugin is currently in <strong>active development</strong> and does not have many features yet. We will
be working on adding all the features from the respective <strong>VSCode</strong> extension.</p>

## Lookup and inspections

<p>MDLCode for PHPStorm highlights references to <strong>strings</strong>, <strong>capabilities</strong>
and <strong>database tables</strong>,
reporting incorrect values and allows to navigate to the definition</p>

## Plugin navigation

<p>MDLCode adds a "Moodle" panel that only shows code of the plugins. It can be filtered to
hide the standard plugins and show only add-ons.</p>

## Type resolution

<p>MDLCode resolves types of the "magic" functions and global variables, for example:</p>

<pre><code lang="php">
$renderer = $PAGE->get_renderer('mod_quiz'); // Instance of \mod_quiz\output\renderer
$ADMIN; // Instance of \admin_root (when used in settings.php files)
$settings; // Instance of \admin_settingpage (when used in settings.php files)
</code></pre>

## Availability

<p>MDLCode for PHPStorm will be free of charge until all functionality is complete and after that will
become a paid plugin. Plugin homepage is <a href="https://mdlcode.dev">mdlcode.dev</a>.</p>

<p>Matrix group for discussions: <code>&#x21;yERsyuEZvnhLzhFMaL:matrix.org</code> </p>

<p>Issue tracker: <a href="https://github.com/lmscloud-io/mdlcode-jetbrains/issues">https://github.com/lmscloud-io/mdlcode-jetbrains/issues</a></p>