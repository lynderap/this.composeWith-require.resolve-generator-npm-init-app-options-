# this.composeWith-require.resolve-generator-npm-init-app-options-
{   // skip prompts   'skip-name': false,   'skip-description': false,   'skip-version': false,   'skip-main': false,   'skip-test': false,   'skip-repo': false,   'skip-keywords': false,   'skip-author': false,   'skip-license': false,     // supply alternative defaults   name: '&lt;%= destFolderName %>',   version: '1.0.0',   description: '',   main: 'index.js',   test: 'echo "Error: no test specified" &amp;&amp; exit 1',   repo: '',   keywords: [],   author: '',   license: 'ISC',     // configure run script defaults   scripts: {     start: 'node dist/index.js',     build: 'webpack -p',     watch: 'webpack-dev-server'   } }
