# DBPsMath CDN


# How to use
This CDN uses githack, so all you need to do is change the folder/file path.

The bare CDN path is ```https://raw.githack.com/dbpsmath/cdn/main/``` You have to add in the path, so for 2048 it would be

```
https://raw.githack.com/dbpsmath/cdn/main/assets/gxmes/2048/index.html
```
So, if you want to make a page on your website using the thing from our CDN, then just take that URL, and put it in this code
```
<html>
    <head>
    </head>
    <body>
        <script>
                var iframe = window.document.createElement('iframe')
                iframe.style.border = 'none';
                iframe.style.width = '100%';
                iframe.style.height - '100%';
                iframe.style.margin = '0';
                iframe.src = 'PUT IN THE URL';
                window.document.body.appendChild(iframe)
                window.document.body.style.margin = '0'
            }
        </script>
    </body>
</html>
```
Pretty simple. If you use the CDN please star this repository.
Don't give me credit, give 3kh0 credit (this is mostly games from his game ripping adventures). His CDN with more games is [here](https://github.com/3kh0/3kh0-Assets)
