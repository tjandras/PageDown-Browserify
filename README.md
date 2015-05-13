# PageDown-Browserify

Modified [PageDown](https://github.com/ujifgc/pagedown) so it can be used with Browserify.

## Sample Code

    var Markdown = require('./Markdown.Editor');
    var converter = new Markdown.Converter();
    var editor = new Markdown.Editor(converter);
    editor.run();
