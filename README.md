# OpenSDS Blog

This is the source repo for the [blog.opensds.io](http://blog.opensds.io)
site. It uses [GitHub Pages](https://pages.github.com/) to power the site with
the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme.

## Contributing Blog Posts

We welcome posts from anyone in the community!

Posts can be submitted as a pull request against this repo. Repo owners have
the option of pushing a commit to add content directly.

### Writing Posts

Posts can be added by adding a file to the `_posts` directory named with  the
format `YEAR-MONTH-DAY.md`. Post content uses [Markdown
formatting](https://guides.github.com/features/mastering-markdown/).

The publishing system uses some metadata along with the markdown content in
what is called **front matter**. An example can be seen at the [top of this
post](https://raw.githubusercontent.com/opensds/opensds.github.io/master/_posts/2018-07-02-aruba-releases.md).
The key pieces of information are `title`, `author`, `header`, and `tags`.

#### Header Images

Adding header images adds visual appeal to the post. The value set for the
`header` front matter should be the `image` path to a png or jpg to use. As
part of proposing your post, new images should be added in the `assets/images`
directory.

#### Author Info

The `author` front matter tag references which author wrote the post. If this
is your first post, please edit the `_data/authors.yml` file to add your
information to the file. The first line is what is used to match with the value
used for the post's `author` tag.

Refer to [the
documentation](https://mmistakes.github.io/minimal-mistakes/docs/authors/) for
the possible author information to add. Please add at least `name` and
`twitter` or `email` so readers can contact you. It is also recommended you add
a photo in the `assets/images` directory to use for the `avatar` value.

### References

Full documentation on
[posts](https://mmistakes.github.io/minimal-mistakes/docs/posts/)
and other options can be found in the [Minimal
Mistakes](https://mmistakes.github.io/minimal-mistakes/docs/)
documentation.
