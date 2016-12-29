# Understanding WCAG 2.0

This is a draft document.

The [Web Content Accessibility Guidelines (WCAG) 2.0](https://www.w3.org/TR/WCAG20/) explain how to make websites accessible to disabled and older people. The guidelines are written by accessibility specialists and disabled people at the [W3C](https://w3.org/).

WCAG 2.0 helps make services accessible to people with:
* Visual impairments, including people who are blind, partially sighted, and people with conditions like being colour blind
* Hearing impairments, including Deaf people who use sign language, and people who are hard of hearing
* Mobility impairments, including people with restricted movement that stops them using a mouse or [keyboard](https://pages.18f.gov/accessibility/keyboard/), and people who find it difficult to control a mouse
* Cognitive impairments, including people who are Dyslexic, on the Autistic Spectrum, and people who have learning difficulties

WCAG 2.0 also helps us think about the different ways people use the web:
* By changing the way a website looks in their browser
* By using a [keyboard](https://pages.18f.gov/accessibility/keyboard/) instead of a mouse
* By using a screen reader to present the website in synthetic speech or electronic Braille
* By using a screen magnifier to increase the size of everything on-screen
* By using speech recognition to use the web with voice commands and dictation

## WCAG architecture

WCAG 2.0 has twelve guidelines, grouped into four principles. Content must be:
* Perceivable
* Operable
* Understandable
* Robust

The twelve guidelines cover areas like alternative formats, [keyboard accessibility](https://pages.18f.gov/accessibility/keyboard/), content readability, and functionality across different devices. 

Each guideline has a number of Success Criteria (SC). Each SC has a conformance level: Level A, Level AA or Level AAA.

According to [Requirement 1: Technical accessibility](requirement1.md) your service must conform to WCAG 2.0 Level AA as a minimum. Here is a short description of the principles, guidelines and SC your service must test for.

## [Principle 1 Perceivable](https://www.w3.org/TR/WCAG20/#perceivable)

Your service must present information in ways people can recognise and use, no matter how they consume content (by touch, sound or sight for example)

#### [Guideline 1.1 Provide text alternatives](https://www.w3.org/TR/WCAG20/#text-equiv)
* 1.1.1 Provide a text description for images, and make sure the description serves the same purpose as the image

see also [images](https://pages.18f.gov/accessibility/images/)

#### [Guideline 1.2 Provide alternatives for time-based media](https://www.w3.org/TR/WCAG20/#media-equiv)
* 1.2.1 Provide a text description for video content that has no audio, or a transcript for audio content that has no video, and make sure the description and transcript serve the same purpose as the original content
* 1.2.2 Provide real-time captions for video content that has audio, and make sure the captions include all dialogue and important sound-effects
* 1.2.3 Provide a text description or a transcript for video content that has audio, and make sure the description or transcript serves the same purpose as the original content
* 1.2.4 Provide real-time captions for live video content that has audio, and make sure the captions include all dialogue and important sound-effects
* 1.2.5 Provide audio description for video content, and make sure the description includes all important activity that takes place on-screen

see also [multimedia](https://pages.18f.gov/accessibility/multimedia/)

#### [Guideline 1.3 Create content that can be presented in different ways](https://www.w3.org/TR/WCAG20/#content-structure-separation)
* 1.3.1 Use elements like headings, lists and tables to properly convey the structure of content
* 1.3.2 Make sure content can always be read in a logical order even when stylesheets are disabled
* 1.3.3 Do not use colour, size, shape, sound or location as the only way to convey instructions

see also [headings](https://pages.18f.gov/accessibility/headings/), [tables](https://pages.18f.gov/accessibility/tables/), [css dependence](https://pages.18f.gov/accessibility/css/) and [colour](https://pages.18f.gov/accessibility/color/)

### [Guideline 1.4 Make content easy for people to see and hear](https://www.w3.org/TR/WCAG20/#visual-audio-contrast)
* 1.4.1 Do not use colour as the only way to convey information of any kind
* 1.4.2 Give people a way to stop audio content if it plays automatically and lasts longer than three seconds, or give them a way to change the volume without changing their system settings
* 1.4.3 Make sure that the colour of text contrasts clearly against its background colour
* 1.4.4 Make sure it is possible to complete all tasks when text is resized up to 200% in the browser
* 1.4.5 Do not use images that contain text

see also [colour](https://pages.18f.gov/accessibility/color/)

## [Principle 2 Operable](https://www.w3.org/TR/WCAG20/#operable)

Your service must be navigable and usable no matter how someone uses it (without a mouse, with voice commands, or with a screen magnifier for example).

### [Guideline 2.1 Make functionality work with a keyboard](https://www.w3.org/TR/WCAG20/#keyboard-operation)
* 2.1.1 Make sure every task can be completed without a mouse
* 2.1.2 Make sure that keyboard users don't get stuck when navigating through content

see also [keyboard](https://pages.18f.gov/accessibility/keyboard/)

### [Guideline 2.2 Give people enough time to read and use content](https://www.w3.org/TR/WCAG20/#time-limits)
* 2.2.1 Give people a way to turn off or extend time limits
* 2.2.2 Give people a way to stop content that updates frequently, blinks or scrolls automatically

see also [timeouts](https://pages.18f.gov/accessibility/timeouts/)

### [Guideline 2.3 Do not cause seizures](https://www.w3.org/TR/WCAG20/#seizure)
* 2.3.1 Do not use content that flashes more than three times a second

see also [flashing](https://pages.18f.gov/accessibility/flashing/)

### [Guideline 2.4 Provide ways to help people navigate and find content](https://www.w3.org/TR/WCAG20/#navigation-mechanisms)
* 2.4.1 Give people who do not use a mouse a way to move to the start of the main content
* 2.4.2 Give every page a unique and helpful title that indicates the purpose of the page
* 2.4.3 Make sure that things receive focus in an order that makes sense
* 2.4.4 Make sure the purpose of a link is obvious from its link text, or its link text in association with nearby content (please check the [style guide](https://www.gov.uk/guidance/style-guide/a-to-z-of-gov-uk-style) for further guidance)
* 2.4.5 Unless a page is a step in a process, give people different ways of finding content (like searching or browsing links)
* 2.4.6 Provide headings and form labels that will help people find content and complete tasks
* 2.4.7 Make sure that people using a keyboard to navigate can always see where they are on a page

see also [page titles](https://pages.18f.gov/accessibility/pagetitles/), [links and repetitive content](https://pages.18f.gov/accessibility/links/) and [keyboard]((https://pages.18f.gov/accessibility/keyboard/)

## [Principle 3 Understandable](https://www.w3.org/TR/WCAG20/#understandable)

Your service must make information understandable, and make it easy for people to understand how to complete tasks.

### [Guideline 3.1 Make text readable and understandable](https://www.w3.org/TR/WCAG20/#meaning)
* 3.1.1 Identify the language that the content is written in
* 3.1.2 Identify any changes in the default written language of the content

### [Guideline 3.2 Make things appear and behave in consistent ways](https://www.w3.org/TR/WCAG20/#consistent-behavior)
* 3.2.1 Do not cause surprising things to happen (like opening a new page), when someone focuses on something
* 3.2.2 Do not cause surprising things to happen when someone interacts with content (like scrolling through a set of options)
* 3.3.3 Make sure that ways to find and navigate content (like search) look and behave the same way when they are used in multiple places
* 3.3.4 Make sure that features (like disclosure widgets) look and behave the same way when they are used in multiple places

### [Guideline 3.3 Help people avoid and correct mistakes](https://www.w3.org/TR/WCAG20/#minimize-error)
* 3.3.1 When someone makes a mistake, provide an error message and make it obvious where the mistake was made
* 3.3.2 Provide form labels to make it clear what information is expected, and optionally provide extra hints to help people avoid mistakes
* 3.3.3 When someone makes a mistake give them suggestions on how to correct it, but do not offer suggestions that will have a negative impact on security
* 3.4.4 Give people a way to review and check the information they have entered, and to correct any mistakes they have made

## [Principle 4 Robust](https://www.w3.org/TR/WCAG20/#robust)

Your service must work with different browsers and assistive technologies in use now, and use technologies in ways that will make your service usable with the browsers and assistive technologies of the future.

### [Guideline 4.1 Make content compatible with different browsers and assistive technologies](https://www.w3.org/TR/WCAG20/#ensure-compat)
* 4.1.1 Make sure the code of each page does not contain errors that will have a negative impact on the way browsers and assistive technologies work together
* 4.1.2 Make sure the code of each page enables assistive technologies to discover the purpose of every feature, the way that feature is identified, and the state it is currently in
