# Highlight section component

## Description:

Highlight section is a great way to showcase small bits of important information, and can be used to display services or features. 

## When and how to use it:

Use this to catch attention and highlight the top tasks or business priorities. 

## Structure:

Highlight section component consist of three parts: header with the main title, the body, and the footer. The body consists of two halves. First half contains concise a secondary title, and a subtitle, The second one has text description. The footer contains a call-to-action link. 

## Features:

Component is also incorporates full bleed background. 


## Screenshot
<img src="img/highlight-section.png">

## HTML

```
        <cagov-highlight-section>
          <article role="article" class="full-bleed bg-highlight-lightest">
            <div class="container">
              <header class="highlight-header">
                <h2>Principles for people-centered digital services</h2>
              </header>
              <section class="highlight-body">
                <div class="highlight-image bg-primary-lightest">
                  <img src="https://california.azureedge.net/cdt/statetemplate/5.6.0/images/color.png" alt="highlight section demo"/>
                </div>
                <div class="highlight-text">
                  <h3>Prioritize accessibility</h3>
                  <h4 class="mt-0">Principle 3</h4>
                  <p>Make your services accessible for all Californians. Think about people who have been traditionally excluded, like people who use screen readers or reside in low bandwidth regions.</p>
                  <div class="wp-button">
                    <a class="btn-primary-outline">See all the principles</a>
                  </div>
                </div>
              </section>
            </div>
          </article>
        </cagov-highlight-section>
```

### Expected variables

There are some colors that should be defined by the containing page.

Expected definition is:

```
:root {
  --primary-color: #004ABC;
  --primary-dark-color: #003484;
  --highlight-color: #FEC02F;
  --highlight-lightest-color: #FFECC1;
  --primary-lightest-color: #B3C9EB;
  --primary-color: #33705B;
  --gray-200: #ededef;
  --body-text: 1.125rem;
  --font-weight-regular: 400;
  --spacing-base: 8px;
  --w-lg: 1176px;

}
```

## Contributor/developer documentation

- [Component information](https://github.com/cagov/design-system/blob/main/components/README.md)

- [Component README template](https://www.notion.so/odi-engineering/Component-documentation-template-2da3975cc0954174ace43004d151451c)

- [Unit tests](https://github.com/cagov/design-system/blob/main/components/UNIT-TESTS.md)
