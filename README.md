# Welcome to my blogs
## [How to add new blogs][1]
- The post is not placed in the _posts directory.
When you change the collections_dir in your config from . (default) to my_col_folder all your posts have to move as well below my_col_folder/_posts jekyll defaults
- The post has incorrect title. Posts should be named YEAR-MONTH-DAY-title.MARKUP (Note the MARKUP extension, which is usually .md or .markdown)
- The post's date is in the future. You can make the post visible by setting future: true in _config.yml (documentation)
- The post has published: false in its front matter. Set it to true.

## How to install

Make sure you install `ruby` and `bundle` 

```
bundle install
```
To fix the error, try running bundle add `webrick`, then re-running `bundle exec jekyll serve`.

Local Development

``` bash
bundle exec jekyll serve 
```


[1]: <https://stackoverflow.com/questions/30625044jekyll-post-not-generated> "Jekyll post generated"