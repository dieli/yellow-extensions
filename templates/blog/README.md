Blog template
=============

Blog with latest articles.

How do I install this?
----------------------
1. Download and install [Yellow](https://github.com/markseu/yellowcms/).  
2. Download [blog.php](blog.php?raw=true) and [blogarticle.php](blogarticle.php?raw=true), copy both files into your system/templates folder.  
3. Download [pagination.php](https://github.com/markseu/yellowcms-extensions/blob/master/snippets/pagination/pagination.php?raw=true) from the pagination snippet, copy into your system/snippets folder. 
4. Add these [text lines](blog.txt?raw=true) to your system/config/text_english.ini file.
5. Create a new folder 'blog' in your content folder.
6. Download [page.txt](page.txt?raw=true) and [2013-04-07-blog-article-example](2013-04-07-blog-article-example?raw=true), copy both files into your content/blog folder.

To uninstall delete the blog templates and folder.

How to write a blog?
--------------------
The blog is available on your website as `http://website/blog/`. To create a new blog article, add a new file to your blog folder. Name your articles according to the format `YYYY-MM-DD-title.txt`, then they are automatically sorted by date. Prefix and suffix are removed from the location. For example the file `content/blog/2013-04-07-blog-article-example.txt` is available on your website as `http://website/blog/blog-article-example`.

This should get you started, you can improve your blog with more extensions.

Example
-------
Content file for a new blog article:

    ---
    Title: New blog article
    Template: blogarticle
    Published: YYYY-MM-DD
    Tag: Blog
    ---
    Write text here