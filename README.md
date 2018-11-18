# Noto-Sans-Sinhala
![Sri Lanka Represent](http://www.animatedimages.org/data/media/882/animated-sri-lanka-flag-image-0008.gif)
Replicate Repository of Googles noto sans for sinhala unicode with cdn.
Web fonts generated with -  [Transfonter](https://transfonter.org/)
Original TTF fonts - [Google get noto](https://www.google.com/get/noto/#sans-sinh)

# Usage
- Get CDN Link
1- Open repository, locate webfonts folder
2- Right click on the font you want to use and copy it's link
3- Visit [RAW Git](https://raw.githack.com/) a *free cdn provider* for Github raw files.
4- Paste the link you copied in Raw Git's first URL tab.
5- Locate "Use this URL in  **production**" and copy the CDN link.

- CSS
1- Open your main style sheet or html
2- Add the following code to it. In this example we use the font *"Noto Sans Sinhala Extra Light"* You may use the name of the font you choose.
*(Each font may contain two web fonts of type "woff" and "woff2". you will have to get links for each to be used in the CSS for better browser compatibility)*
>     @font-face {
>          font-family: 'Noto Sans Sinhala ExtLt'; /* the font name */
>          font-style: normal;
>          font-weight: 200;
>          src: url('https://rawcdn.githack.com/Super-Chama/Noto-Sans-Sinhala/ac4ea0c396c66aedd8dcb9a60a846ee36da6c7f3/Webfont/subset-NotoSansSinhala-CondensedExtraLight.woff') format('woff'), 
>          url('https://rawcdn.githack.com/Super-Chama/Noto-Sans-Sinhala/ac4ea0c396c66aedd8dcb9a60a846ee36da6c7f3/Webfont/subset-NotoSansSinhala-CondensedExtraLight.woff2') format('woff2'); 
>          }
	> 	3 - You can use the added font in your styles as follows.
	> 
>     .your-style {
>     font-family: 'Noto Sans Sinhala ExtLt';
>      }



