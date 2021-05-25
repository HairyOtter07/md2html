# md2html
Note: not yet available on npm

This tool allows you to convert a Markdown file to an HTML file.  
Example usage:
```sh
$ md2html --help
usage: md2html <filename> [options]

options:
--help			show this message
-o, --out		specify output filename (defaults to {filename no extension}.html)
$ cat testing.md
# Test
This is a test
$ md2html testing.md
$ cat testing.html
<h1>Test</h1>
<p>This is a test</p>
```
