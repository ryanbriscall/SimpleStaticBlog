# A simple static-based blog system

[View Demo](https://ryanbriscall.github.io/SimpleStaticBlog)

Create your articles (as `.md` (Markdown) files) in the `content/` folder.  Then add them to the flat-file database `posts.js`

Lightweight, compatible, single-page web app (<abbr title="Single-page Application">SPA</abbr>) with no dependencies and near-zero additional HTTP requests.

Use this for starting your own static blog on GitHub Pages!

If you want, you can run this from a folder of your website.  E.g. `/blog`

Check out our sister project, [SimpleStaticDocs](https://github.com/ryanbriscall/SimpleStaticDocs), to run your own `/docs` too!


## Usage

1. JavaScript (`posts.js`):
   ```js
   var posts = [
      '2020-06-06-Another-Blog-Post',
      '2020-05-24-Test-Demo-Second-Post-For-Blog',
      '2020-05-02-My-First-Blog-Post',
   ];
   ```

2. Files:

   ```
   ./content/2020-05-02-My-First-Blog-Post.md
   ./content/2020-05-24-Test-Demo-Second-Post-For-Blog.md
   ./content/2020-06-06-Another-Blog-Post.md
   ```

## Changelog

### 1.0.0

 - Initial release.

## License

Licensed under the MIT, see the `LICENSE` file for more details.
