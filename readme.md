
# Doczen

Documentation coming soon, ironic for a documentation tool, huh?

The gist is that it'll fetch documentation from your projects and help you bundle, validate, and export them to other systems, like Confluence.

### Help Output

```
$ doczen -h confluence -h current
Version: 0.0.3
Main: A tool designed to super-charge your code-base's documentation.
-i, --input <glob>       Glob of files to parse.
-p, --prefix <prefix>    Prefix to add to all titles.


Confluence: Exports a collection of markdown files to Confluence.
-s, --space <space>     The space key to export to
-u, --url <url>         The url of the confluence instance


Current: Validates that the documentation is up to date by checking the files that it references.
No command line options.
```
