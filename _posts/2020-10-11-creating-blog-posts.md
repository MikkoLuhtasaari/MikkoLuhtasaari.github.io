---
layout: post
title: Creating blog posts
categories: Reverie
---

## Meta info

Every post starts with some meta information about it.
*Layout* is usually *post*.
*Title* is the title of the post.
*Categories* is either a string or an array of categories.
You can see a few examples below:

```md
---
layout: post
title: Creating blog posts
categories: Reverie
---
```

```md
---
layout: post
title: Setting up Reverie based blog on GitHub Pages
categories: [GitHub, GitHub Pages, Reverie]
---
```

You can also check out the examples from my [GitHub](https://raw.githubusercontent.com/MikkoLuhtasaari/MikkoLuhtasaari.github.io/master/_posts/2020-10-04-setting-up-blog.md).

## Writing the posts

The posts are written by using [MarkDown](https://www.markdownguide.org/).
Markdown is really simple and easy to read markup language.
A good cheatsheet can be found from [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

Let's take a quick look at the most common things you are going to do with markdown.

### Headers

There are six different levels of headers similar to H1-H6.
Lower number equals bigger header.

```md
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

produces an output like

# H1
## H2
### H3
#### H4
##### H5
###### H6

### Lists

There are two kinds of lists; ordered and unordered.

```md
1. first item
2. second item

* Unordered item
* More unordered items
  * A list inside list
```

produces an output like

1. first item
2. second item

* Unordered item
* More unordered items
  * A list inside list

### Links and images

```md
[This is a link!](https://github.com/MikkoLuhtasaari/)
[This link has a title!](https://github.com/MikkoLuhtasaari/ "I'm the title!")
![I'm alt text for the image](https://via.placeholder.com/150)
![Images can also be uploaded to the repository](/images/2020-10-04/01.PNG)
```

produces an output like

[This is a link!](https://github.com/MikkoLuhtasaari/)
[This link has a title!](https://github.com/MikkoLuhtasaari/ "I'm the title!")
![I'm alt text for the image](https://via.placeholder.com/150)
![Images can also be uploaded to the repository](/images/2020-10-04/01.PNG)

### Code highlighting

You can highlight various different languages

```javascript
const greet = (name) => console.log(`Hello ${name}!`);
```

```python
print("Hello world!")
```

```html
<h1>Hello world!</h1>
```

```css
.heading {
    background-color: "black";
}
```
