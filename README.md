# mduc
A markdown to html compiler.

https://user-images.githubusercontent.com/81730792/205475592-8f6758b0-424d-467e-99f7-6a662676c7b8.mp4

## Install:
x86_64-linux-gnu
```
curl -L https://raw.githubusercontent.com/xTeKc/mduc/main/scripts/local/install-x86_64-linux-gnu.sh | bash
```
x86_64-apple-darwin
```
curl -L https://raw.githubusercontent.com/xTeKc/mduc/main/scripts/local/install-x86_64-apple-darwin.sh | bash
``` 

## Usage:
Within the directory of the markdown file, run: `mduc md_file.md` <br>
This will output an equivalent `.html` file.
```
A markdown to html compiler

Usage: mduc <MDFILE>

Arguments:
  <MDFILE>  Markdown file to compile

Options:
  -h, --help     Print help information
  -V, --version  Print version information
```

<br>

## Capabilities :
- converts `#` to `<h1></h1>` tags
- converts `plain text` into `<p></p>` tags

<br>

## Future Additions :
- `<html>` html
- `<head>` head
- `<body>` body
- `<title>` title
- `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>` headers
- `<em>` emphasis
- `<b>` bold
- `<i>` italic
- `<small>` small text
- `<u>` underline
- `<strike>` strike through (deleted text)
- `<a href="">` anchor
- `<li>` list
- `<ol>` ordered list
- `<ul>` unordered list
- `<!-->` comment
- `<marquee>` scrolling text
- `<center>` center
- `<font>` font
- `<br>` line break
- `<img>` image
- `<link>` link
- `<hr/>` horizontal rule (display horizontal line)
- `<meta>` meta (page description)
- `<table>` table
- `<tr>` table row
- `<th>` table header
- `<td>` standard table cell
- `<form>` form
- `<input type="submit">` submit input
- `<option>` dropdown option
- `<input type="radio">` radio input
