# Accessible-Web-101

Did you know that at least [every fourth American is a person with a disability](https://www.cdc.gov/media/releases/2018/p0816-disability.html)? Or, that globally, there are at least [a billion people with disabilities](https://www.worldbank.org/en/topic/disability)? And that the estimates show that [one in every 200 developers is blind](https://www.freecodecamp.org/news/73-of-programmers-are-web-developers-and-other-insights-from-stack-overflows-massive-2017-survey-89a13b11e370/)?

Accessibility of information was one of the foundational values of the Internet. Let's make sure everyone can participate.

## Checklist

Here is a checklist of what to do when desiging for accessibility:


### Perceivable
Information and user interface components must be presentable to users in ways they can perceive (it can't be invisible to all of their senses), for instance:
- 

### Operable
User interface components and navigation must be operable (the interface cannot require interaction that a user cannot perform), for instance:
- Did you try to activate buttons and links on your mobile app? Was it easy?
- If you are using hover attribute, are you ensuring that people who don’t operate a mouse can use it as well?
- Did you make sure to enable keyboard navigation?
- Did you include :focus attribute in your CSS for links?


### Understandable
Information and the operation of user interface must be understandable (the content or operation cannot be beyond their understanding), for instance:
- Did you scan your text through [Hemingway Project](http://www.hemingwayapp.com/)?
If not, read on:
- Did you write in [plain English](https://en.wikipedia.org/wiki/Plain_English)?
- Did you have more short sentences than long ones?
- Do you avoid passive voice and favor active voice?
- Do you avoid jargon and culture-specific references?
- Do you avoid figurative language, idioms or specific terminology?

### Robust 
Content must be robust enough that it can be interpreted reliably by a wide variety of user agents, including assistive technologies (as technologies and user agents evolve, the content should remain accessible), for instance:

- Can all videos and animations be paused?
- Do you have transcripts for audio?
- Have you checked how your page looks with text increased to 200%?
- Did you remove horizontal scrolling on mobile devices?
- Can your mobile app be rotated in any direction?
- Is a “skip to main content” link present before the navigation when tabbing?
- Did you make sure your app does not include any text in all caps?
- Is it easy to switch off gif animation on your website?
- Did you disable autoplay?
- Do videos on your page have subtitles?

### Codebase
- Does your app include a readme? Does the readme include headers?
- Does your code include comments that make it easy to understand what blocks do from the get-go?
- Do your variables have names that make it clear what they do?
- Did you sacrifice code readability for fewer lines?
- Is your app open source?


- Did you check whether colors on your website are the right contrast?
- Did you make sure links are easily visible?
- Are you using accessible font or enable users to switch fonts?
- Is it possible to increase the size of the text? Does your app still look the same?
- Are you using headers in cascading manner?
- Do you pictures have alt text?

- Does your page require high-speed internet or a lot of data transfer?
- Did you test your app on non-Mac?
- Who cannot afford your app?
- Are you using gender-neutral words?
- Is your language albleist in any way?
- Are your links and buttons descriptive (e.g. “assistive technology” and not “click here”)?
- Is your text left-aligned for left-to-right languages?
- Did you validate your HTML? https://validator.w3.org/nu/
- Did you use the lang attribute on the html page? https://github.com/FreedomScientific/VFO-standards-support/issues/188  This helps screen readers to pronounce content correctly https://www.w3.org/TR/UNDERSTANDING-WCAG20/meaning-doc-lang-id.html
- Did you care to change page/view title?
- Did you enable viewport zoom?
- Did you ensure linear content flow?
- Did you remove session timeouts?
- Did you remove invisible focusable elements? (If you click through the page, can you clearly follow the focused element?)
- Did you ensure that decorative elements have empty alt tag?
- Did you use only one h1?
- Did you skip header levels? (e.g. h1, h3, h4)
- When using lists, are you using ol, ul or dl?
- Are your links easily recognizable?
- Is your button element only for actual buttons?
- Do you give your users advance warning if a link will open in a new window?
- Did you test your page with a screen reader?
- Are you using autocomplete in your forms?
- Do all your fields have a descriptive labels?

https://medium.com/@janetmndz/web-accessibility-an-introduction-for-all-developers-c4f632a0506e