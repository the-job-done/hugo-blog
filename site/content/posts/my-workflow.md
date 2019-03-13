---
title: "My workflow"
date: 2019-01-28T23:05:54Z
draft: false
toc: false
images:
tags: 
  - scrathpad
---

Here's a short list: 

1. Start with a new file

    Let's call this new file "markdown-is-easy-here-is-all-you-need-to-know.md". Hugo has its own header that it looks for at, so next step:

2. Copy the header

    ```
title: "Markdown is easy - here is all you need to know about it!"
date: 2019-01-28T23:34:54Z
draft: false
toc: false
images:
tags:
    ```

3. Start writing the content

     I'll leave this all up to you.

4. Git magic

    Locally:
    ```
git add .
git commit -m "markdown-is-easy-here-is-all-you-need-to-know.md"
git push -u origin master
    ```
   
    For now I don't have any CI/CD pipeline setup so I just spend time the old ways:

    Remotely:
    ```
cd ~/blog/content/ && git pull && cd ~/blog/
hugo -v
    ```


That's it!
