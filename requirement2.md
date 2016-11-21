# Requirement 2: AT compatibility

This is a draft document.

Your service must meet [Requirement 2: AT compatibility](requirements.md).

## Meeting Requirement 2

Your service must be compatible with common Assistive Technologies (AT), including screen magnifiers, screen readers and speech recognition tools.

Note: your service must also be tested with disabled people who use AT, as part of [Requirement 3: Usable accessibility](requirement3.md).

## How to meet Requirement 2

Test your service with the following AT and browser combinations. Research conducted in 2016 identified these combinations as the most commonly used across Gov.UK.

Note: if no version numbers are indicated for the AT or browser, the latest version should be used.

Internet Explorer 11 with:
* Jaws 15, 16 or 17.
* ZoomText.
* Read and Write.
* Dragon Naturally Speaking 11.

Firefox with:
* NVDA.

Safari with:
* VoiceOver (iOS9).
* VoiceOver (MacOS Sierra).

To be confident that your service meets this requirement, we recommend that all features of your website are tested for AT compatibility before being considered complete.

### Triaging issues

If you discover an issue with a particular AT and browser combination, you should first check that the issue is not caused by features in your service that do not follow accessibility best practice. Has the feature passed accessibility checks carried out as part of [Requirement 1: Technical accessibility](requirement1.md) for example?

Next you should check that the issue is not a known issue with either the AT or the browser. All browsers and AT behave differently, and they all have quirks of their own, so sometimes an issue can be caused by things that are outside of your control.

Then consider the severity of the issue. Does it prevent someone using that AT and browser combination from completing a task? Does it affect one AT and browser combination or more than one?

If you are not sure how to resolve an issue, we recommend joining the [Cross-Government Accessibility community](https://www.gov.uk/service-manual/communities/accessibility-community), and asking for help.
