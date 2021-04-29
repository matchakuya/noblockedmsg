# noblockedmsg
Gets rid of the blocked message placeholder
made by @matcha98qx

```css
/** ------- BLOCKED PLACEHOLDER REMOVER -------- **/

/* taken from 「div.wrapper-2a6GCs」 */
div[class *= 'wrapper'] 
{
    min-height: 0;
}

/* taken from 「div.blockedSystemMessage-2Rk1ek」 */
div[class *= 'blockedSystemMessage']
{
    display: none;
}

/** -------------------------------------------- **/
```

To use this you need a way to attach Custom CSS to your Discord client
