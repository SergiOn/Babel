<h1>Babel screencast</h1>

<a target="_blank" href="https://www.youtube.com/watch?v=XVDJxIpiDJw&list=PLqHlAwsJRxAOZCOfiukwZe4zJZIiVynvh&index=1&t=2s">Link to screencast</a>

<h3>#0 Introduction</h3>

<h3>#1 Installation</h3>
<pre>
babel es2015.js --out-file es5.js --presets es2015
babel es2015.js -o es5.js --presets es2015
</pre>

<h3>#2 Configuration</h3>

<h3>#3 Options</h3>
**watch**
<pre>
babel es2015.js --out-file es5.js --watch
babel es2015.js -o es5.js -w
</pre>

**src / out-dir**
<pre>
babel src --out-dir dist
babel src -d dist
</pre>