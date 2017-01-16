# Getting an audit

This is a draft document.

An accessibility audit is an assessment of a website or product against a recognised set of criteria. We use the Web Content Accessibility Guidelines (WCAG) 2.0 to audit our services.

* [Understanding WCAG 2.0](wcag.md)
* [Understanding WCAG 2.0 (alternate)](wcag-alt.md)

An accessibility audit does two things:

1. First it identifies accessibility issues with your service;
2. Then it confirms that you have resolved those issues that were identified.

Use a third party agency that specialises in accessibility to audit your service. This will ensure that the accessibility audit is comprehensive and independent.

If you have an accessibility specialist within your department, you can carry out an accessibility audit of your own service. An accessibility specialist must have:

* Good general accessibility knowledge;
* Thorough understanding of WCAG 2.0;
* Experience of conducting formal accessibility audits;
* Detailed understanding of browser accessibility and Assistive Technologies (AT).

## When to get an audit

You should have accessibility audits and/or retests  carried out at different points in the lifecycle of your service. This will help you identify and resolve issues in a timely and cost effective way, and give you greater confidence that your service meets [Requirement 1: Technical accessibility](requirement1.md).

Accessibility auditing is an iterative process. The accessibility audit itself will identify the WCAG 2.0 Success Criteria (SC) that your service fails. Subsequent retests (there may be more than one) will confirm that your service no longer fails those SC.

It is often easier and cheaper to fix accessibility issues early in the development process. it also helps you learn about common accessibility challenges, so you can avoid them as your service develops.

### Early audit

If you use a design pattern library you should get it audited for accessibility before you begin deploying the patterns throughout your service. Identifying and resolving accessibility issues in your design pattern library will make sure that the building blocks of your service have good accessibility.

If you do not use a design pattern library, an accessibility audit of your service prototype will help identify accessibility issues that will need resolving as the service moves into proper development.

### Later audit

You should get your service audited for accessibility again before it reaches public beta (or before it is made available to its intended audience). This will help make sure that your service has good technical accessibility by the time people start to use it for the first time.

## What to ask for

An accessibility audit can include different components.

### Conformance testing

Conformance testing is the basic component of every audit. It is the assessment of your service against WCAG 2.0, specifically against all Level A and Level AA Success Criteria (SC).

### AT compatibility testing

Assistive Technology (AT) testing assesses your service for compatibility with screen magnifiers, speech recognition tools and screen readers. This directly relates to [Requirement 2: AT compatibility testing](requirement2.md).

### Expert review

An expert review is carried out by a panel of experienced testers who have disabilities. It assesses the experience of using your service, but should not be confused with usability testing with people from your target audience.

Usability testing is essential because it ensures your service can be used by older and disabled people from your actual audience. An expert review complements usability testing by providing a broader perspective on potential issues, and recommending solutions that solve issues for one group of people without comprimising accessibility for another group.

### Retest

A retest is a subsequent round of conformance testing. It is intended to confirm that the issues identified during the initial conformance test (and other types of testing), have been successfully resolved. You may need more than one retest to confirm that all the issues identified during the accessibility audit hae been successfully resolved.

### Ongoing support

Ongoing support in the form of a helpdesk or other system, is a way for you to ask questions and further your understanding of the issues identified during an accessibility audit.

## What to audit

When you have your design pattern library audited for accessibility, it is a good idea to include all the paterns in the library. The patterns will be the building blocks of your entire service, so having the whole library assessed is a good investment.

It is not practical (or even necessary) to assess every page (or step) across an entire service though. Instead the approach is to identify a sample that is a reasonably diverse representation of the different types of page and content.

One of the things to look out for in the agency you choose, is whether they can confidently help you identify the test sample.

## Getting an audit

You should use the Digital Marketplace to find an agency to carry out your accessibility audits.

Editor's note: does anyone know how the Digital marketplace works? Would be good to include some umore useful info here.

### Writing a brief

You will need to write a project brief. The brief should include the following details:

* The name of your service and a brief description of its purpose;
* The approximate number of design patterns, unique page types or unique types of content you want tested for conformance and AT compatibility;
* The user journeys (including number of steps) you want put through an expert review;
* The Guidelines you want your service audited against (WCAG 2.0 Level A and Level AA);
* The types of deliverables you want to receive.

### Picking a supplier

Cost is an important factor, but the cheapest accessibility audit is not necessarily the right one to choose. When choosing the third party agency you want to work with, look for the following things:

* Independent verification of their accessibility credentials;
* Involvement in accessibility standards activities;
* Public contributions to the accessibility community (conferences, magazine articles etc.);
* Experience and/or familiarity with UK Government services;
* Ability to help you prioritise and fix accessibility issues.

## What to expect

An accessibility audit can result in different deliverables. It is a good idea to ask prospective agencies for examples of their deliverables, so you can make an informed decision about which will be most useful to your team.

### Results

This is the set of results from the conformance testing part of an audit. Often presented in spreadsheet form, the results give you a high level overview of the pass/fail status for each SC across the test sample.

### Report

This is a written (often very long) document. It describes different issues, explains why they are important, and provides solutions (including code examples) for resolving them.

### Tickets

This Is when the agency creates individual issue tracking tickets, either in your preferred issue tracker or via one of their own. Tickets describe individual issues and provide solutions (including code examples).

Whether you receive a report or a set of tickets, issues should be prioritised to help you resolve them.

An accessibility audit may provide one or more of these deliverables. They are not mutually exclusive, and often compliment each other.

## Using the audit results

When you receive a report or set of tickets, they should be prioritised to help you tackle those that have the greatest impact on users. Issues that prevent users from using your service or which place serious barriers in their way should be resolved as the highest priority.

Your supplier will be able to provide further advice on prioritisation, but as a general plan you should tackle all Level A issues and then all Level AA issues that have been identified. WCAG 2.0 Level A SC are intended to cover the most basic aspects of accessibility, and Level AA SC build from this foundation.
