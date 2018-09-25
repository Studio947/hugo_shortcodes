# Hugo Shortcodes

Shortcodes for Hugo. This repository contains shortcodes below.

- github.html: This shortcode embeds a sourcecode on GitHub repository into Hugo's markdown page. This shortcode uses <http://gist-it.appspot.com> service.

## How To Use

Download files and copy them into your Hugo's `/layouts/shortcodes/` folder.  

### github.html

If you want to embed a source code on a GitHub repository, just add a shortcode below on your content.

- user name is the repository's user name.
- repository-name is the repository name.
- file-path is a file path.

~~~go
{{< github user="username" repo="repository-name" path="file-path">}}
~~~

