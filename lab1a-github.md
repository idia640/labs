# GitHub for IDIA640

Our objectives are modest! But by the end of the class you should not only have your own account on GitHub, but also be comfortable as a collaborator on projects, whether contributing to documentation, submitting an issue, or committing files. Since we are never leaving the browser, you will not need to learn any additional tools.

## What is GitHub

GitHub is one of the most traffic-ed sites on the Internet with a user base of over 31 million  (@2019). Ostensibly, it's a collaborative repository for sharing code. But it's also a site where you can host websites and blogs for free and without any embedded ads.

## GitHub Classroom

The IDIA640 class is inside a GitHub classroom. For this reason, class repositories are private, except for materials that I've created and made public. While in previous years, each student has had his/her own repository for coursework, starting in Spring 2019, we're sharing a repository for journals and case study templates so that you all can learn from each other better.

## GitHub Basics

If you are new to GitHub, you may feel over-whelmed by strange terminology and an unfamiliar user interface.

We're going to walk through GitHub basics (in the browser) during class, but since we won't have time to do into any depth, this lab will give you a more extensive overview.

This video below from GitHub shares a flavor of the power of distributive, collaborative versioning of documents and code.

https://www.youtube.com/embed/w3jLJU7DT5E

And for a brief introduction to Git, which is the version control system underlying the GitHub platform, this video provides a high-level introduction.

https://www.youtube.com/embed/tTF1xih1RIM

## GitHub Repositories

Anyone can create a repository in GitHub. Every repository has its own settings, policies for sharing, wiki, etc. You can use an external client to add documents and make changes to repositories, or edit directly in the browser.

## Editing Files in a GitHub Repository

From the browser, you can upload or create a new file, and you can also save a file by scrolling down to the bottom and clicking "commit". Since this is a collaborative site, it's good practice to note what change you've made in the optional description field. Since we're not going to use branches, you will not ever need to change to anything but the master branch.

When you edit a file in the browser and want to preview your changes, you will see how your file renders using markdown (more on markdown below). If you see green and red text, these are the changes you've added and deleted from a previous version.

> Play around with this on your practice file in [Dark Patterns](https://github.com/idia640/Journals-Spring-19/tree/master/Practice-Dark-Patterns).

## What are GitHub Issues?

No doubt, GitHub Issues was originally as a bug tracker. But it turns out that it's a great place to hold conversations on particular topics... much like a discussion board.

Look at this issue tracker for requesting recipes:
<https://github.com/newmerator/recipes/issues>

Note that there are both open and close discussion items; you can comment on either. Play around in here and maybe offer a comment.

One other very important facet of 'issues' is the ability to @mention a person or team in side your issue and comments.

> Do you have any questions or having any problems in [Dark Patterns practice](https://github.com/idia640/Journals-Spring-19/tree/master/Practice-Dark-Patterns)?

For more information, [check this GitHub guide on Issues](https://guides.github.com/features/issues/).

## Tracking Changes

In the upper right corner of repositories is a "**watch**" button and "**star**" button. Watch will automatically inform you of changes, while a star is like a bookmark that help you find this repository from your own profile page when you login to GitHub.

## What the Heck is a Pull Request?

A pull request is simply a *request* to a repository owner to make a change. If you own a repository, you can make changes yourself without asking anyone for permission. But if you don't have write access to a repository, then you will need to request a change. So, for example, if you spot a typo in this document, or would like to make a suggestion, you can go into edit mode, make the change, and a pull request is done automagically back to me!

> Give it a try and let's see if we can't improve on this lab write-up!

## GitHub Markdown

Hopefully, by the end of the class you will be proficient in markdown! Markdown is an easy way to format text on GitHub. GitHub recognizes any document with the suffix of '.md' as a markdown document.

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to labs](../labs) on this site. This is a relative link. The ".." is a shortcut that means, "go up one directory level". You can link multiple together as in '../../' to mean two levels higher. A link is further composed by adding "/" plus a directory or file.

You can also simply refer to the location of a page by it's absolute location. For example, you can embed this image of a squirrel ![](images/squirrel.jpg)

Separate paragraphs with a new line.

# [](#header-1)Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## [](#header-2)Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### [](#header-3)Header 3

### Inline attributes

You can embed HTML directly in markdown. It's even possible to add inline CSS. This is *red*{: style="color: red"}.

### emoji

 :smile:

### Escape Markdown
Let's rename \*this-page\* to \*that-page\*.

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### [](#header-4)Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### [](#header-5)Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### [](#header-6)Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

### Footnotes
This is some text.[^1]. Other text.[^footnote].

[^1]: Some *crazy* footnote definition.

[^footnote]:
    > Blockquotes can be in a footnote.

        as well as code blocks

    or, naturally, simple paragraphs.

### Small image from URL

![](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![](https://guides.github.com/activities/hello-world/branching.png)

### Embed YouTube video (plain old HTML)

It used to be that you could embed videos easily in GitHub by simply using HTML -- iframes worked well. Now the only way to do this is to add an image and link the video to it.

<iframe width="560" height="315" src="https://www.youtube.com/embed/mpjEyBKSfJQ?ecver=1" frameborder="0" allowfullscreen></iframe>
```
But you can wrap a link around an image as a workaround.

[![](images/chaplin.jpg)](https://www.youtube.com/embed/mpjEyBKSfJQ)

### More Information on Markdown

Here are a few more things you can do with Markdown on GitHub to make working in GitHub easier. <https://help.github.com/articles/about-writing-and-formatting-on-github/>.

### Blogs on GitHub

Did you know you could set up a blog for free on GitHub? It's not hard and an easy way to host your own blog for free! https://pages.github.com

To do this, you will need to use an external editor such as [GitHub Atom](https://atom.io) and a Desktop client such as [GitHub Desktop](https://desktop.github.com) to sync your changes.

But by the end of this class, I hope you will have the confidence to learn using these tools without much difficulty.
