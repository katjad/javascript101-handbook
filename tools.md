# Debugging

## Think First
Use your intuition before you dive down any rabbit holes.  What do you think the cause might be?  Have you made any recent changes that might have caused the bug? Can you roll back to a previous commit that works? 

## Browser Dev Tools
You can view error messages in the browser console.  We recommend using Chrome as your browser but the others have very similar dev tools too.

[Chrome DevTools Overview
](https://developer.chrome.com/devtools)


## console.log is your friend

You can debug your code by logging to the browser/terminal console:
```
const foobar = 'orly!?'
console.log('debug something: ', foobar)
```

## Search
Learn how to search properly, both your code and google.  

## Stack OverFlow
If you have a bug search [Stack Overflow](http://stackoverflow.com/) first, it's probably been experienced before!

## Minimal Test Case
When something is really bugging you, go back to basics and make a minimal test case.  If that works as expected then you know the problem lies else where.