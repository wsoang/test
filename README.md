## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/wsoang/test/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/wsoang/test/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

<script type='text/javascript' src='https://cdn.jsdelivr.net/npm/jquery@3.2/dist/jquery.min.js'></script>
<script type="text/javascript"> 
/* 鼠标特效 */
var a_idx = 0; 
jQuery(document).ready(function($) { 
    $("body").click(function(e) { 
        var a = new Array("萌萌", "聪明", "机智", "温柔", "活泼", "可爱", "伶俐", "宇宙", "超级", "无敌", "萌萌哒", "天才", "少女", "小柳柳"); 
        var $i = $("<span/>").text(a[a_idx]); 
        a_idx = (a_idx + 1) % a.length; 
        var x = e.pageX, 
        y = e.pageY; 
        $i.css({ 
            "z-index": 999999999999999999999999999999999999999999999999999999999999999999999, 
            "top": y - 20, 
            "left": x, 
            "position": "absolute", 
            "font-weight": "bold", 
            "color": "#ff6651" 
        }); 
        $("body").append($i); 
        $i.animate({ 
            "top": y - 180, 
            "opacity": 0 
        }, 
        1500, 
        function() { 
            $i.remove(); 
        }); 
    }); 
}); 
</script>
