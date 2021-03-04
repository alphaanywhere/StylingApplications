# StylingApplications

Examples of styling applications in Alpha Anywhere

[Register for the Alpha Anywhere Demo and Q&A](https://www.alphasoftware.com/weekly-alpha-anywhere-overview-webinar)

Send your questions to [guides@alphasoftware.com](mailto:guides@alphasoftware.com)


## Samples

The following examples are available in this repository. The files listed in each section below refer to component files (.a5wcmp).

### Sub-themes: Creating a Custom Sub-theme for a Window

A Window is a popup dialog used to display a wide range of information in applications from simple messages to whole components. These components demonstrate three different way of creating a custom Window sub-theme: as a style tweak, in an Inherited theme, and in a custom Web Theme. [Watch this Webinar on YouTube to learn more.](https://youtu.be/Udn-OTXaM0Y)

- windowDemo: example of defining a new window sub-theme in a Web Theme created by copying the Alpha theme locally.
- windowDemoInherited: example of defining a new window sub-theme in an Inherited Web Theme
- windowDemoTweak: example of defining a new window sub-theme as a style tweak

### Dynamically Setting Component Theme at Run-time

- dynamicStyle: example of setting a component's style at run-time using session variables.
- styleUploader: a "dummy" component used to publish the styles to the application server that you can pick from in dynamicStyle

### Exploring CSS
- panelFlipCSSDemo: example of modifying the 2 sided card with 3d animation ViewBox template to use an image as a background. Demonstrates background-image, background-size, background-repeat, background-position, background-color, padding, opactiy, and height. Example also includes additional information not presented during the webinar on how to change the template so that all cards will flip when their corresponding button is clicked.
- borderedButtons: example showing how to overwrite the .button class to add a border to all buttons in a component. Includes bonus example of how to use the max-width property to restrict how wide a control can grow.

## Webinars

<style>A series webinars on styling applications in Alpha Anywhere</style>


### <style> Part 1 - March 6, 2019

The first installment of a series of webinars on styling applications. In part 1, we start at the beginning. We discuss what an application _is_, define CSS, give a high-level overview of [Combinators](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Combinators) with a deep-ish dive into the [_.classname_ combinator](https://developer.mozilla.org/en-US/docs/Web/CSS/Descendant_combinator), breifly touch on Alpha Web Themes (what they are), and go through a demonstration of how to style buttons in a UX separately from the core web theme. 

[Watch the Webinar on YouTube!](https://youtu.be/TdIpjWX59AE)

### <style> Part 2 - March 27, 2019

In part 2, we take a look at using Style Tweaks to modify a system style - Alpha - and taking a look at how you might approach building up a set of Style Tweaks to modify the style for a project. We also talk about [Sass](https://sass-lang.com/) variables and nesting - a technique for grouping [descendent combinators](https://developer.mozilla.org/en-US/docs/Web/CSS/Descendant_combinator) with the same parent.

[Watch the Webinar on YouTube!](https://youtu.be/Udn-OTXaM0Y)

### Sub-Themes (and also JSON) - July 31, 2019

In this presentation, we discuss Sub-Themes and how to create your own Sub-Themes using the Web Theme Builder. During the webinar, we create a new Sub-Theme for a Window in the Alpha Web Theme. We also briefly talk about working with JSON data in Xbasic at the beginning of the webinar.

[Watch the Webinar on YouTube!](https://youtu.be/Zebxd8RDN_Q)

### Styling Apps - January 29, 2020

In this presentation, we take a look at the tools available in Alpha Anywhere for modifying the style of an application. This is a high-level overview of the various builders and settings in Alpha Anywhere used to style applications. The presentation for this webinar can be found in the 'presentations' directory of this repository.

[Watch the Webinar on YouTube!](https://youtu.be/7Y5CWBFHmYQ)

### Cascading Style Sheets - March 3, 2021

In this presentation, we highlight some CSS properties that are useful to know when styling your Alpha Anywhere apps. Alpha Anywhere uses CSS to customize the appearance of your applications. These customizations can be added as externally linked CSS files or as the value for a control's property. Familiarizing yourself with some of the more common CSS directives used throughout Alpha will help you create classy apps that stand out among the competition. 

The presentation for this webinar can be found in the 'presentations' directory of this repository.

[Watch the Webinar on YouTube!](https://www.youtube.com/watch?v=jcJs4_QBq_k)

The components created during this webinar can be found in this repository:
 - panelFlipCSSDemo.a5cmp (requires all images in products folder to work)
 - borderedButtons.a5wcmp

# Change Log
- Mar 4, 2021: Added UX components & resources for Mar 3 webinar.
- Mar 4, 2021: Added presentation for Mar 3 webinar (powerpoint & pdf)
- Feb  6, 2020: Added link to Jan 29 webinar.
- Feb  6, 2020: Added UX components & a5w page demonstrating how to dyamically set the style at run-time with a session variable.
- Jan 29, 2020: Uploaded presentation for Jan 29, 2020 webinar
- Aug  2, 2019: Added UX components & styles created as part of the July 31, 2019 Webinar
- Mar 28, 2019: Updated README
- Mar 28, 2019: Created Repository
