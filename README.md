# Frosted Glass - Codeblock Theme
A codeblock theme that changes the appearance of Discord's regular codeblocks using some of [Frosted Glass](https://github.com/DiscordStyles/FrostedGlass) colors and background image with extra colors. Check out my other codeblock theme - [Wildberry](https://github.com/DiscordAddons/Wildberry-Codeblock-Theme).

# Picture
![image](https://user-images.githubusercontent.com/72931279/112011210-6a9e0800-8afe-11eb-83b9-0cbddf8e1851.png)

# Code
```css
.markup-2BOw-j code {
    background: url(https://i.imgur.com/kYW2H5C.jpg);
    background-size: cover; 
    border: 1.5px solid #170027;
}
.hljs-name, .hljs-section, .hljs-selector-class, .hljs-selector-id, .hljs-title {
    background: linear-gradient(90deg, #ff5e94, #f28dca, #d98df2);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    filter: brightness(120%);
}
.hljs-doctag, .hljs-literal, .hljs-meta .hljs-meta-string, .hljs-number, .hljs-regexp, .hljs-string {
    background: linear-gradient(360deg, #673ab7, #ffef78);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    filter: brightness(120%);
}
.hljs-attr, .hljs-attribute, .hljs-class .hljs-title, .hljs-template-variable, .hljs-type, .hljs-variable {
    color: rgb(169, 212, 219);
    filter: brightness(110%);
}
.hljs-built_in, .hljs-deletion {
    color: rgb(63, 81, 181);
    filter: brightness(200%)
}
.hljs-addition, .hljs-keyword, .hljs-selector-tag {
    color: rgb(133, 226, 242);
}
.hljs-comment, .hljs-quote {
    background: linear-gradient(360deg, gray, white);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    filter: brightness(110%);
}
```
