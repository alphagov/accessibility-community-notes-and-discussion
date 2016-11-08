# Understanding WCAG 2.0

This is a draft document.

The [Web Content Accessibility Guidelines (WCAG) 2.0](https://www.w3.org/TR/WCAG20/) explain how to make websites accessible to disabled and older people. The guidelines are written by accessibility specialists and disabled people at the [W3C](https://w3.org/).

WCAG 2.0 helps make services accessible to people with:
* Visual impairments, including people who are blind, partially sighted, and people with conditions like being colour blind
* Hearing impairments, including Deaf people who use sign language, and people who are hard of hearing
* Mobility impairments, including people with restricted movement that stops them using a mouse or keyboard, and people wwho find it difficult to control a mouse
* Cognitive impairments, including people who are Dyslexic, on the Autistic Spectrum, and people who have learning difficulties

WCAG 2.0 also helps us think about the different ways people use the web:
* By changing the way a website looks in their browser
* By using a keyboard instead of a mouse
* By using a screen reader to present the website in synthetic speech or electronic Braille
* By using a screen magnifier to increase the size of everything on-screen
* By using speech recognition to use the web with voice commands and dictation

## WCAG architecture

WCAG 2.0 has twelve guidelines, grouped into four principles. Content must be:
* Perceivable
* Operable
* Understandable
* Robust

The twelve guidelines cover areas like alternative formats, keyboard accessibility, content readability, and functionality across different devices. 

Each guideline has a number of Success Criteria (SC). Each SC has a conformance level: Level A, Level AA or Level AAA.

According to [Requirement 1: Technical accessibility](requirement1.md) your service must conform to WCAG 2.0 Level AA as a minimum. Here is a short description of the principles, guidelines and SC your service must test for.

### Perceivable

Make sure people can recognise all information and content.
* Provide text alternatives for images
* Provide transcripts for audio and video
* Provide realtime captions for video
* Make sure content is structured in a way that makes sense when it is read.
* Use the proper mark-up for every feature
* Use text colours that show up clearly against the background colour
* Make sure every feature can be used when text size is increased by 200%
* Do not use images of text

### Operable

Make sure people can use every feature of a service.
* Make sure everything works with a keyboard
* Let people play/pause/stop moving content
* Do not use blinking or flashing content
* Provide a "skip to content" link
* Provide helpful titles for pages and frames
* Make sure keyboard users can move through content in a way that makes sense
* Use link text that makes it easy to tell where the link goes (check the [style guide](https://www.gov.uk/guidance/style-guide/a-to-z-of-gov-uk-style) for further guidance)
* Make headings and labels helpful
* Make it easy for keyboard users to see where they are in the content

### Understandable

Make sure people can understand the content, and how the service works.
* Use plain and simple language
* Keep sentences short
* Do not use words and phrases that people will not recognise, or provide an explanation if you cannot avoid it
* Explain abbreviations and acronyms, unless you are very sure people will recognise them
* Identify the language used for written content, and indicate when the written language changes
* Make sure features look and behave in the same way every time they are used
* Do not make big changes to content without people being aware of it
* Provide instructions to help people use unfamiliar features
* Make sure all form fields have visible and helpful labels
* Make it easy for people to correct errors in forms

### Robust

Make sure services can be used on different platforms and with different technologies.
* Use proper code and make sure it is valid
* Make sure that the purpose of every feature can be identified, and that features are uniquely labelled
