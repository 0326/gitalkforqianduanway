qianduanway.com 的评论专用 Repo, 文档：https://github.com/gitalk/gitalk

代码集成：
```html
<section class="post-full-comments">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css">
    <script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>
    <div id="gitalk-container"></div>
    <script>
        var gitalk = new Gitalk({
            clientID: '59151f054d28755a8353',
            clientSecret: '4e55c0a8ea4da7f356ed199f7d74dc77fc4e0022',
            repo: 'gitalkforqianduanway',
            owner: '0326',
            admin: ['0326'],
            id: '{{comment_id}}',
            distractionFreeMode: false
        });
        gitalk.render('gitalk-container');
    </script>
</section>
 ```
