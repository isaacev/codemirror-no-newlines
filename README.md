# No Newline CodeMirror addon

Add a configuration option to CodeMirror called "noNewline" that when set as `true` will prevent any newline characters from being typed into the CodeMirror editor and any newline character pasted into the editor will be replaced by a single space.

## Usage

```javascript
var myCodeMirror = CodeMirror(document.body, {
  value:     "function myScript(){return 100;}\n",
  mode:      "javascript",
  noNewline: true
});
```
