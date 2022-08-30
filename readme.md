# Infinite Scroll App

## Icons :
https://loading.io/

## Fixing the CORS Error
https://medium.com/@dtkatz/3-ways-to-fix-the-cors-error-and-how-access-control-allow-origin-works-d97d55946d9

## Useful links :
https://htmldom.dev/

https://unsplash.com/documentation

_italic_

**Bold text**

~~Strikethrough text~~

![imagename](TargetUrl)

>Your quote looks like this.

---

```Javascript
async function getQuotes() {
    loading();
    const apiUrl = 'https://type.fit/api/quotes';
    try {
        const response = await fetch(apiUrl);
        apiQuotes = await response.json();
        // console.log(apiQuotes);
        newQuote();
    } catch (error) {
        alert(error)
    }
}
```
***

1. Item 1
2. Item 2
3. Item 3
   * Sub item 1
   * Sub item 3
* Unordered item
* Unordered item
* Unordered item

***

|Name|Email|Address| 
|-----------|-------|------------|
|John|john@example.com|Address1|
|Mary|mary@example.com|Address2|