# jekyll-navigtion
Jekyll include file for navbar.

# Usage
Copy file navigation.md to your site's \_includes/ directory.
You must have defined those variables in \_config.yml:
```yaml
navigation:
  - your pages you want to add to navbar here in list; Example:
  - absolute/path/to/my-page1.md # Please specify absoulte path or with domain name
```
If your domain isn't served at GitHub Pages, specify such mapping in \_config.yml too:
```yaml
domain_name: https://example.com
```
You can simply type `{% include navigation.html current=page.url %}`
Vóila!
