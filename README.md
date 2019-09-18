# Accessible-Web-101

Did you know that at least [every fourth American is a person with a disability](https://www.cdc.gov/media/releases/2018/p0816-disability.html)? Or, that globally, there are at least [a billion people with disabilities](https://www.worldbank.org/en/topic/disability)? And that the estimates show that [one in every 200 developers is blind](https://www.freecodecamp.org/news/73-of-programmers-are-web-developers-and-other-insights-from-stack-overflows-massive-2017-survey-89a13b11e370/)?

Accessibility of information was one of the foundational values of the Internet. Let's make sure everyone can participate.

## Read more:
- [Janet Mendez: Web Accessibility — an introduction for all developers](https://medium.com/@janetmndz/web-accessibility-an-introduction-for-all-developers-c4f632a0506e)
- [Google's guide to inclusive documentation](https://developers.google.com/style/inclusive-documentation)
- [Web Content Accessibility Guidelines (WCAG) 2.0](https://www.w3.org/TR/WCAG20/)
- [WCAG 2.0 checklist](https://webaim.org/standards/wcag/checklist)
- [Color contrast explanation](https://a11yproject.com/posts/what-is-color-contrast/)
- [About :focus](https://a11yproject.com/posts/never-remove-css-outlines/)

## Useful tools
- [Contrast checker](https://colorable.jxnblk.com/ff0000/fdfdfd)
- [Contrast generator](https://learnui.design/tools/accessible-color-generator.html)
- [Deque: accessible CSS library](https://pattern-library.dequelabs.com/)

## Check your web app!

Here is a checklist of what to do when desiging for accessibility:

### Perceivable
Information and user interface components must be presentable to users in ways they can perceive (it can't be invisible to all of their senses), for instance:
- Did you check whether colors on your website are the right contrast?
- Did you make sure links are easily visible?
- Are you using accessible font or enable users to switch fonts?
- Is it possible to increase the size of the text? Does your app still look the same?
- Did you include :focus attribute in your CSS for links?
- Did you remove invisible focusable elements? (If you click through the page, can you clearly follow the focused element?)

### Operable
User interface components and navigation must be operable (the interface cannot require interaction that a user cannot perform), for instance:
- Did you try to activate buttons and links on the mobile version of your app? Was it easy?
- If you are using hover attribute, are you ensuring that people who don’t operate a mouse can use it as well?
- Did you make sure to enable keyboard navigation?
- Is a “skip to main content” link present before the navigation when tabbing?
- Is your button element only for actual buttons (and not for styling)?
- Did you enable autocomplete in your forms?
- Do all your fields have a descriptive labels?

### Understandable
Information and the operation of user interface must be understandable (the content or operation cannot be beyond their understanding), for instance:
- Did you scan your text through [Hemingway Project](http://www.hemingwayapp.com/)?
If not, read on:
- Did you write in [plain English](https://en.wikipedia.org/wiki/Plain_English)?
- Did you have more short sentences than long ones?
- Do you avoid passive voice and favor active voice?
- Do you avoid jargon and culture-specific references?
- Do you avoid figurative language, idioms or specific terminology?
- Is your text left-aligned for left-to-right languages?
- Did you ensure linear content flow?

### Robust 
Content must be robust enough that it can be interpreted reliably by a wide variety of user agents, including assistive technologies (as technologies and user agents evolve, the content should remain accessible), for instance:
- Did you [validate your HTML](https://validator.w3.org/nu/)?
- Are you using [semantic HTML](https://www.lifewire.com/why-use-semantic-html-3468271) to clearly mark headers, articles, footers, etc.?
- Did you make sure to use maximum one h1 per page/view?
- Did you use the [lang attribute](https://www.w3.org/TR/UNDERSTANDING-WCAG20/meaning-doc-lang-id.html) on the html page?
- Did you make sure to have a different `<title>` on each page/view?
- Did you make sure you did not skip header levels? (e.g. h1, h3, h4)
- When using lists, are you using ol, ul or dl (and not just new line and -)?
- Are your links and buttons descriptive (e.g. “assistive technology” and not “click here”)?
- Did you make sure your app does not include any text in all caps?
- Have you checked how your page looks with text increased to 200%?
- Did you remove horizontal scrolling on mobile devices?
- Can your mobile app be rotated in any direction?
- Did you enable viewport zoom?
- Did you remove session timeouts?
- Do you give your users advance warning if a link will open in a new window?
- Did you test your page with a screen reader?

#### videos, pictures and gifs:
- Do you pictures have alt text?
- Can all videos and animations be paused?
- Do you have transcripts for audio?
- Is it easy to switch off gif animation on your website?
- Did you disable autoplay?
- Do videos on your page have subtitles?
- Did you ensure that images have a descriptive alt tag?
- Did you ensure that decorative elements have empty alt tag?

### Codebase
- Does your app include a readme? Does the readme include headers?
- Does your code include comments that make it easy to understand what blocks do from the get-go?
- Do your variables have names that make it clear what they do?
- Did you sacrifice code readability for fewer lines?
- Is your app open source? Did you include instructions on contributions?
- Is your [documentation inclusive](https://developers.google.com/style/inclusive-documentation)?

### Varia
- Who cannot afford your app? How can you increase their access?
- Are you using gender-neutral words?
- Is language you are using albleist or discriminatory in any way?
- Does your page require high-speed internet or a lot of data transfer?
- Did you test your app on a non-Apple computer?

## Contributing 
See something, say something! 
I totally welcome feedback, pull requests, tips and ideas. This is a stub of a bigger project so feel welcome to chip in! My main priorities:
- index.html does not yet have media queries option! 
- index.html has not been thoroughly tested on different screen readers;
- index.js is still empty :D

Don't be scared to contact me, even if you've never submitted a pull request! 

Contact me at:
[@sylwiavargas](https://twitter.com/sylwiavargas)
or Flatiron's slack! 