# Pre-built themes for HireHive iframe integration
This repository contains documentation and pre-built themes for the HireHive iframe integration. 
This integration allows you to host the full candidate application experience on your own website.
Candidates can browse your open positions and apply on your website without.

If you need any features which are missing or if you find any issues, please email us at support@hirehive.com or file an issue.

## FAQ
**Question:** How do I use one of the pre-built themes?

**Answer:** Browse the theme folders available and choose the style that works best for your website.
Copy the `CSS` file of the theme you want to use and paste those styles into the iframe playground editor and save.

##
**Question:** How can I use another font?

**Answer:** You can use CSS `@import` rule

```css
@import url("https://fonts.googleapis.com/css?family=Assistant:300,400&display=swap");

body {
  font-family: "Assistant"
}
```

##
**Question:** How do I know what CSS selector to use?

**Answer:** In the iframe playground you can mouseover the elements in the panel and a tooltip will show you what css class to target

![css selector tip](https://user-images.githubusercontent.com/966495/73077172-8fc1c700-3eb7-11ea-9028-a78d62b6219d.PNG)

##
**Question:** How do I remove the default link hover effect?

**Answer:**
```css
a::after {
  display:none;
}
```

##
**Question:** How do I make the job location appear under the job title?

**Answer:**

```css
.job-opening {
   display:flex;
   flex-direction: column;
}
```

##
**Question:** How do I make sure the styles are responsive?

**Answer:** The iframe playground has responsive toggle buttons so you can view the iframe at different size breakpoints

![breakpoint buttons](https://user-images.githubusercontent.com/966495/73077749-b6ccc880-3eb8-11ea-8a1d-127a6691852f.PNG)

##
**Question:** How do I view each step of the application process?

**Answer:** The iframe playground has breadcrumb links so you can see the 3 different pages a candidate will see in the iframe.

![iframe links](https://user-images.githubusercontent.com/966495/73077852-ed0a4800-3eb8-11ea-8841-30775dbc8548.png)
