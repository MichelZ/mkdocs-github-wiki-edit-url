# MKDocs GitHub Wiki Edit Url Support

This plugin is to enable mkdocs to produce output that uses the GitHub Wiki-style edit URL's, e.g. https://github.com/project/repo/wiki/some/path/_edit  
You will need to set repo_url to your wiki URL, e.g. https://github.com/project/repo/wiki. The plugin will use repo_url/<path>/_edit as the URL style.

# Install

- Use `pip install mkdocs-github-wiki-edit-url`
- Add the plugin to your `mkdocs.yml`, e.g.:
``` 
plugins:
  - search
  - ezlinks
  - github-wiki-edit-url
```