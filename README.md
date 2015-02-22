### blog.codebar.io

Build with [Octopress](https://github.com/imathis/octopress) and styled with Ghost's [Casper](https://github.com/jkrmr/casper) theme.


### Updating the theme

```bash
   cd <your octopress directory>
   $ git submodule update
   $ rake install['casper']
   # regenerate, make changes, etc...
```

### Getting Started and Contributing

- [Fork](https://github.com/codebar/blog/fork) the repository

- Clone your fork `git clone git@github.com:[your-github-username]/blog.git`

- Create a new branch `git checkout -b my-blog-post`

- Install the project dependencies running `bundle`

- Create a new post `rake new_post[title]`

- Preview the site `rake preview`.

- Push to your branch

- Open a [pull request](https://github.com/codebar/blog/compare)

> If you are are using zshell and are having trouble executing `rake new_post[title]` switch to bash by typing `bash` in your terminal. Use `exit` to go back to zshell.

Use `rake -T` to see other available commands.
