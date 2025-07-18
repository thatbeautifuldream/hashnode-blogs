---
title: "Master CSS Flexbox in 6 steps!"
datePublished: Sat Jun 28 2025 18:17:55 GMT+0000 (Coordinated Universal Time)
cuid: cmcgkdf3h000u02l77odl0ckx
slug: master-css-flexbox-in-6-steps
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1751133523232/8c76d6ab-6b74-4d40-803e-95f446f5e535.png
tags: flexbox, flex-css

---

**Responsive layouts made easy! Step-by-step tutorial to create beautiful designs quickly, with live codepen examples.**

## 1\. Flexbox Basics

> ***💡 Tip:  
> Want to try these live? Edit “CodePen Section” below each code block to play along and see your changes in real-time!***

Let’s start by making a flex container!  
Add `display: flex` and see how the items line up in a row.

**Try it out:**

<iframe height="300" style="width:100%" src="https://codepen.io/milindmishra/embed/raVRvwW?default-tab=html%2Cresult&editable=true&theme-id=dark">
  See the Pen <a href="https://codepen.io/milindmishra/pen/raVRvwW">
  Basic display: flex</a> by Milind Mishra (<a href="https://codepen.io/milindmishra">@milindmishra</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

**What’s happening?**

* The container now puts its children in a row, side by side.
    
* The color scheme matches throughout the series for a beautiful feed!
    

## 2\. Main Axis Alignment: `justify-content`

The `justify-content` property aligns items horizontally (the main axis). Try these CodePens showing the different options!

<iframe height="300" style="width:100%" src="https://codepen.io/milindmishra/embed/RNPdyje?default-tab=html%2Cresult&amp;editable=true&amp;theme-id=dark">
  See the Pen <a href="https://codepen.io/milindmishra/pen/RNPdyje">
  Main Axis Alignment - justify-content</a> by Milind Mishra (<a href="https://codepen.io/milindmishra">@milindmishra</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

**Variations:**

* `justify-content: flex-start` (default)
    
* `justify-content: center`
    
* `justify-content: space-between`
    
* `justify-content: space-around`
    
* `justify-content: space-evenly`
    

**What’s happening?**

* Try replacing `center` with any value above to see different alignments!
    

## 3\. Cross Axis Alignment: `align-items`

This properly controls how items are aligned vertically (the cross axis).

<iframe height="300" style="width:100%" src="https://codepen.io/milindmishra/embed/KwpERZd?default-tab=html%2Cresult&editable=true&theme-id=dark">
  See the Pen <a href="https://codepen.io/milindmishra/pen/KwpERZd">
  Cross Axis Alignment - align-items</a> by Milind Mishra (<a href="https://codepen.io/milindmishra">@milindmishra</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

**What’s happening?**

* See how items line up at the bottom? Change to `align-items: flex-start` or `center` to see what happens!
    

## 4\. Changing Direction & Wrapping

Use `flex-direction` to arrange items in a column or row. Add `flex-wrap` to wrap overflowing items.

<iframe height="300" style="width:100%" src="https://codepen.io/milindmishra/embed/azOMGrq?default-tab=html%2Cresult&editable=true&theme-id=dark">
  See the Pen <a href="https://codepen.io/milindmishra/pen/azOMGrq">
  Changing Direction & Wrapping</a> by Milind Mishra (<a href="https://codepen.io/milindmishra">@milindmishra</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

**What’s happening?**

* `flex-direction: column` stacks items vertically.
    
* Adding `flex-wrap: wrap` lets items flow into a new row if there isn’t enough space.
    

## 5\. Flex Grow & Flex Shrink

Use these properties to make items expand or shrink based on available space.

<iframe height="300" style="width:100%" src="https://codepen.io/milindmishra/embed/YPXgLbd?default-tab=html%2Cresult&editable=true&theme-id=dark">
  See the Pen <a href="https://codepen.io/milindmishra/pen/YPXgLbd">
  Flex Grow & Flex Shrink</a> by Milind Mishra (<a href="https://codepen.io/milindmishra">@milindmishra</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

**What’s happening?**

* Items with higher `flex-grow` expand more if there’s space.
    
* Items with lower `flex-shrink` resist shrinking if the container is too small.
    

## 6\. Individual Alignment: `align-self`

Want to override the alignment for just one item? Use `align-self`!

<iframe height="300" style="width:100%" src="https://codepen.io/milindmishra/embed/OPVqZeL?default-tab=html%2Cresult&editable=true&theme-id=dark">
  See the Pen <a href="https://codepen.io/milindmishra/pen/OPVqZeL">
  Individual Alignment: align-self</a> by Milind Mishra (<a href="https://codepen.io/milindmishra">@milindmishra</a>)
  on <a href="https://codepen.io">CodePen</a>.
</iframe>

**What’s happening?**

* `.align-self-start` bumps one item to the top, `.align-self-end` to the bottom (when items are centered by default).
    

## 7\. Conclusion

You’ve just learned all the key features of Flexbox with modern, consistent styling. Play with these examples, remix them, and you're well on your way to building responsive web layouts.

**Next step:**  
Got tricky layouts? Look into CSS Grid for more advanced two-dimensional structures!