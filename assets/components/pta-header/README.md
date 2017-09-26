# Personal tax account header

<div class="alert alert--info">
  <p class="alert__message">This patterns is work in progress.</p>
  <p class="alert__message">View the to do list for this pattern on <a href="https://github.com/hmrc/design-patterns/issues/128">GitHub</a>.</p>
</div>

The Personal tax account header is used thorough the account to help users understand they are in an account.

<!-- TODO: Phil Sherry to provide an include for the example. -->
<div class="example">
  <div class="scale-wrapper">
    <div class="scale">{% include "header.html" %}</div>
  </div>
</div>

## When to use the Personal tax account header

The Personal tax account header should be used on all services that are part of the Personal tax account.

### When not to use the Personal tax account header

Do not use this header for stand-alone services you should use the [GOV.UK header](https://www.gov.uk/service-manual/design/add-the-govuk-header-and-footer) or the [HMRC header](http://hmrc.github.io/assets-frontend/section-header.html).
<!-- TODO: The URL for the HMRC header needs to be changed so that it meets GOV.UK URL guidelines -->

## How it works 

The header should contain:

- the cookie banner
- the GOV.UK 
- the account navigation bar

## Implementing the header

The header is provided by the template service and is configured by passing variables from your service to the template.

The following variables can be customised:

- service phase
- variable
- variable
<!-- TODO: get list of variables that can be passed to the herader -->

## Header elements

### The cookie banner

The cookie banner should be the same across all HMRC services reffer to the cookie component 

<!-- TODO: standardise cookies across HMRC and government -->

### GOV.UK header

The GOV.UK header should be used without changing anything.

### Account navigation bar

The account navigation bar contains:
- account home link
- messages link
- check your progress link
- your account dropdown
- sign out link

<!-- Use this section to explain how the pattern works. This should include:

- (if the pattern/component is too complex to have been fully described in the overview) a full description of how the pattern works (for users)
- rules/instructions on how to implement it
- steps to follow

It can also include

- coded examples
- things to avoid
- why it works -->

<!-- If this section is quite long, break it into smaller sections with H3s. -->

## Research on this pattern

Summarise and link to research relating to this pattern (ideally a blog post) and describe any gaps or questions you still need to answer.
