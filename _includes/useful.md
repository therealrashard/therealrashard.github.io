# Useful

[Relative links in markup files](https://github.blog/2013-01-31-relative-links-in-markup-files/) [Relative links for GitHub pages](https://github.blog/2016-12-05-relative-links-for-github-pages/)
`[a link](https://github.com/user/repo/blob/branch/other_file.md)`
`[a relative link](other_file.md)`

[Markdownify includes #1303](https://github.com/jekyll/jekyll/issues/1303)
```
{% capture my_include %}{% include a_markdown_file.md %}{% endcapture %}
{{ my_include | markdownify }}
```
What we usually do is a capture block - [ParkeR Moore](https://github.com/parkr) [@parkr]