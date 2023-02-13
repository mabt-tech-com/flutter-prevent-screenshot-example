# Flutter - Prevent Screenshots and Screen Recordings on mobile & web [2021]



## 🎬 Tuto Video :  [https://.../yil6EE2Fivo](yil6EE2Fivo)

https://youtu.be
https://youtu.be/

### ✌&ensp;Preview

![yjIziFU](https://i.imgur.com/XFTT6ba.gif)

![yjIziFU](https://i.imgur.com/qdDHNOs.jpg)


---

<br/><br/><br/> 

---

# How can I block screenshots on flutter web application ?

## How can I block screenshots on flutter web application ?

Blocking screenshots on a Flutter web application can be a bit tricky, as there is no built-in way to do this in the framework.
However, here are a few approaches you can try:

1. Use a library like html2canvas to take screenshots of the web page and then use JavaScript to detect and block them.
2. Use CSS to prevent the user from selecting and copying text or images on the page.
3. Use the **`preventDefault()`** method on the **`contextmenu`** event to prevent the right-click menu from appearing, which blocks the option to take a screenshot.

Please note that these solutions may not be foolproof and determined users may still be able to take screenshots. Also, as with any security measures, it's always best to stay up-to-date with the latest techniques and best practices.

---
 

## On a flutter web application how to Use CSS to prevent the user from selecting and copying text or images on the page ?

You can use CSS to prevent the user from selecting and copying text or images on a Flutter web application by adding the following CSS styles to the **`head`** of your HTML document:

```

-webkit-user-select: none; /* Safari */
-moz-user-select: none; /* Firefox */
-ms-user-select: none; /* IE10+/Edge */
user-select: none; /* Standard */
```

This will disable text selection and copying for the entire page.

Alternatively, you can add the **`unselectable`** attribute to specific elements to prevent them from being selected:

```
<div unselectable="on"> This text cannot be selected </div>
```

You can also use **`pointer-events: none`** CSS property on the element that you want to prevent the user from copying or selecting it.

Please note that disabling text selection and copying may have negative effects on accessibility, it's best to consider this when implementing this feature.





