# Site header

The site header puts your site’s name at the top of your site, under the statewide header. This allows people to readily identify the site they’re visiting. If they select the site’s name, it returns them to the site’s homepage.

The site header includes “State of California” above the site name to identify its association with the state.

There are two optional elements you can add to the site header:

- A logo on the left that, if selected, takes visitors to the homepage
- A search box on the right that allows visitors to search the site

On mobile, the search box becomes a search button that opens a search box. It displays to the right of the site name.

The search connects with whatever site search you set up on your site.

## When and how to use it

The site header goes on all pages of your website.

If you use a logo in your site header, make sure that any text in it is legible. Look at how much and where any white space is.

### How not to use it

Do not modify the site header beyond adding the site name and a logo.

## Demo and sample markup

<html-preview>

```html preview
<!--site-header with logo-->
<div class="site-header">
  <!-- Note the `with-logo` class next to `container`. Add this when you're including a logo. -->
  <div class="container with-logo">
    <a href="/" class="grid-logo" aria-label="DCC logo">
      <svg
        version="1.1"
        alt="DCC logo"
        style="height: 75px;"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
        x="0px"
        y="0px"
        viewBox="0 0 108 108"
        style="enable-background:new 0 0 108 108;"
        xml:space="preserve"
      >
        <style type="text/css">
          .st0 {
            fill: #3d6937;
          }
        </style>
        <g>
          <path
            class="st0"
            d="M54,2.5C25.6,2.5,2.5,25.6,2.5,54c0,28.4,23.1,51.5,51.5,51.5s51.5-23.1,51.5-51.5C105.5,25.6,82.4,2.5,54,2.5
            z M54,102.5C27.3,102.5,5.5,80.7,5.5,54C5.5,27.3,27.3,5.5,54,5.5s48.5,21.7,48.5,48.5C102.5,80.7,80.7,102.5,54,102.5z"
          />
          <path
            class="st0"
            d="M93.7,61.5l-1.4-0.1c-0.4,0-11-0.7-22.1,1.1c-5.2,0.9-9.4,2.6-12.6,4.2c1.8-3.6,4.9-8.4,9.6-13
            c5.8-5.6,12.1-10.4,16-13.3c-1.6,5-5,12.9-10.9,18.6c0,0,0,0,0,0c1.9-0.2,3.7-0.4,5.4-0.5c7.8-9.4,10.2-21.6,10.4-22.1l0.1-0.3
            l-2.4-1.9l-0.4,0.3c-0.4,0.3-10.9,7.2-20.6,16.5c-5.6,5.4-9,11-10.9,15c-0.1-0.1-0.1-0.3-0.2-0.4C52,61.7,49.5,54,49.5,44.3
            c0-9.6,2.5-19,4.3-24.3c1.8,5.3,4.3,14.7,4.3,24.3c0,3.8-0.4,7.3-1,10.4c1.3-1.6,2.7-3.2,4.3-4.8c0.2-1.8,0.3-3.6,0.3-5.5
            c0-15.4-5.8-29.5-6.2-30.3h-3.3c-0.4,0.8-6.2,15-6.2,30.3c0,12.1,3.6,21.2,5.4,24.8c-3.8-1.5-9.7-4.5-15.5-10
            c-5.9-5.7-9.2-13.6-10.9-18.6c3.9,2.9,10.2,7.7,16,13.3c1.1,1,2.1,2.1,3,3.2c-0.4-2-0.8-4.1-1-6.3c-9.6-9.1-19.6-15.7-20-16
            l-0.5-0.3L20,36.2l0.1,0.4c0.1,0.6,3.2,15.6,13.2,25.2c5.5,5.3,11.3,8.4,15.3,10.2c-3.3,0.6-7.8,1-13,0.1c-6.3-1-12.1-4.6-15.6-7.2
            c3,0,7.1,0.1,11.5,0.5c-0.6-0.5-1.1-1-1.7-1.6c-0.8-0.8-1.5-1.6-2.3-2.4c-6.9-0.4-12.1-0.1-12.5-0.1l-0.8,0.1l-0.7,2.8l0.3,0.3
            c0.4,0.4,9.6,9.3,21.1,11.2c2.4,0.4,4.6,0.5,6.7,0.5c3.9,0,7.1-0.5,9.5-1.1c-0.8,2.1-2.4,4.9-5.1,7c-3.2,2.5-7.5,3.7-10.3,4.1
            c0.9-2,2.5-4.9,4.7-7.3c-1.4-0.1-2.8-0.2-4.3-0.5c-3.3,4.4-4.8,9.1-4.8,9.4l0,0.1l2,2.2c1.1-0.1,9.2-0.7,15.1-5.3
            c4.6-3.6,6.4-8.5,7-11c0.1,0,0.3,0,0.4,0c1.8-0.1,6,0.8,9.3,3.4c3.2,2.5,5.4,6.4,6.5,9c-2.8-0.5-7-1.6-10.3-4.1
            c-1.4-1.1-2.5-2.4-3.4-3.7c-0.5,1.1-1,2.4-1.8,3.6c0.8,1,1.8,2,3,2.9c6.1,4.8,14.8,5.3,15.2,5.3l0.5,0l1.5-1.7L76.1,88
            c-0.1-0.4-2.6-8.6-8.8-13.4c-3.1-2.4-6.4-3.4-9.1-3.9c2.9-1.7,7.2-3.6,12.6-4.5c6.3-1,12.5-1.2,16.6-1.2c-3.5,2.6-9.2,6.2-15.6,7.2
            c-0.4,0.1-0.8,0.1-1.2,0.2c1.2,0.9,2.3,2,3.2,3.1c10.8-2.3,19.3-10.5,19.7-10.9l0.8-0.8L93.7,61.5z"
          />
        </g>
      </svg>
    </a>

    <a class="grid-org-name" href="/">
      <span class="org-name-dept"> Department of <br />Cannabis Control </span>

      <span class="org-name-state"> California </span>
    </a>

    <div class="cagov-nav mobile-icons grid-mobile-icons">
      <div class="cagov-nav mobile-search">
        <button class="search-btn" aria-expanded="true">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            x="0px"
            y="0px"
            width="17px"
            height="17px"
            viewBox="0 0 17 17"
            style="enable-background:new 0 0 17 17;"
            xml:space="preserve"
          >
            <path
              class="blue"
              d="M16.4,15.2l-4-4c2-2.6,1.8-6.5-0.6-8.9c-1.3-1.3-3-2-4.8-2S3.5,1,2.2,2.3c-2.6,2.6-2.6,6.9,0,9.6
      c1.3,1.3,3,2,4.8,2c1.4,0,2.9-0.5,4.1-1.4l4.1,4c0.2,0.2,0.4,0.3,0.7,0.3c0.2,0,0.5-0.1,0.7-0.3C16.7,16.2,16.7,15.6,16.4,15.2
      L16.4,15.2z M7,12c-1.3,0-2.6-0.5-3.5-1.4c-1.9-1.9-1.9-5.1,0-7C4.4,2.7,5.6,2.1,7,2.1s2.6,0.5,3.5,1.4c0.9,0.9,1.4,2.2,1.4,3.5
      c0,1.3-0.5,2.6-1.4,3.5C9.5,11.5,8.3,12,7,12z"
            ></path>
          </svg>
          <span>Search</span>
        </button>
      </div>
      <button
        class="menu-trigger cagov-nav open-menu"
        aria-label="Navigation menu"
        aria-haspopup="true"
        aria-expanded="false"
        aria-owns="mainMenu"
        aria-controls="mainMenu"
      >
        <div class="cagov-nav hamburger">
          <div class="hamburger-box">
            <div class="hamburger-inner"></div>
          </div>
        </div>
        <div
          class="cagov-nav menu-trigger-label menu-label"
          data-openlabel="Menu"
          data-closelabel="Close"
        >
          Menu
        </div>
      </button>
    </div>

    <div class="search-container grid-search">
      <form class="site-search">
        <span class="sr-only" id="SearchInput">Custom Google Search</span>
        <input
          type="text"
          id="q"
          name="q"
          aria-labelledby="SearchInput"
          placeholder="Search this website"
          class="search-textfield"
        />
        <button type="submit" class="search-submit">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            x="0px"
            y="0px"
            width="17px"
            height="17px"
            viewBox="0 0 17 17"
            style="enable-background:new 0 0 17 17;"
            xml:space="preserve"
          >
            <path
              class="blue"
              d="M16.4,15.2l-4-4c2-2.6,1.8-6.5-0.6-8.9c-1.3-1.3-3-2-4.8-2S3.5,1,2.2,2.3c-2.6,2.6-2.6,6.9,0,9.6
        c1.3,1.3,3,2,4.8,2c1.4,0,2.9-0.5,4.1-1.4l4.1,4c0.2,0.2,0.4,0.3,0.7,0.3c0.2,0,0.5-0.1,0.7-0.3C16.7,16.2,16.7,15.6,16.4,15.2
        L16.4,15.2z M7,12c-1.3,0-2.6-0.5-3.5-1.4c-1.9-1.9-1.9-5.1,0-7C4.4,2.7,5.6,2.1,7,2.1s2.6,0.5,3.5,1.4c0.9,0.9,1.4,2.2,1.4,3.5
        c0,1.3-0.5,2.6-1.4,3.5C9.5,11.5,8.3,12,7,12z"
            />
          </svg>
          <span class="sr-only">Submit</span>
        </button>
        <button class="search-close">Close</button>
      </form>
    </div>
  </div>
</div>
<!--end site-header-->
```

</html-preview>

```html preview


<!--site-header without logo-->
<div class="site-header">
  <div class="container">
    <a class="grid-org-name" href="/">
      <span class="org-name-state"> State of California </span>

      <span class="org-name-dept"> California Drought Action </span>
    </a>

    <div class="cagov-nav mobile-icons grid-mobile-icons">
      <div class="cagov-nav mobile-search">
        <button class="search-btn" aria-expanded="true">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            x="0px"
            y="0px"
            width="17px"
            height="17px"
            viewBox="0 0 17 17"
            style="enable-background:new 0 0 17 17;"
            xml:space="preserve"
          >
            <path
              class="blue"
              d="M16.4,15.2l-4-4c2-2.6,1.8-6.5-0.6-8.9c-1.3-1.3-3-2-4.8-2S3.5,1,2.2,2.3c-2.6,2.6-2.6,6.9,0,9.6
      c1.3,1.3,3,2,4.8,2c1.4,0,2.9-0.5,4.1-1.4l4.1,4c0.2,0.2,0.4,0.3,0.7,0.3c0.2,0,0.5-0.1,0.7-0.3C16.7,16.2,16.7,15.6,16.4,15.2
      L16.4,15.2z M7,12c-1.3,0-2.6-0.5-3.5-1.4c-1.9-1.9-1.9-5.1,0-7C4.4,2.7,5.6,2.1,7,2.1s2.6,0.5,3.5,1.4c0.9,0.9,1.4,2.2,1.4,3.5
      c0,1.3-0.5,2.6-1.4,3.5C9.5,11.5,8.3,12,7,12z"
            ></path>
          </svg>
          <span>Search</span>
        </button>
      </div>
      <button
        class="menu-trigger cagov-nav open-menu"
        aria-label="Navigation menu"
        aria-haspopup="true"
        aria-expanded="false"
        aria-owns="mainMenu"
        aria-controls="mainMenu"
      >
        <div class="cagov-nav hamburger">
          <div class="hamburger-box">
            <div class="hamburger-inner"></div>
          </div>
        </div>
        <div
          class="cagov-nav menu-trigger-label menu-label"
          data-openlabel="Menu"
          data-closelabel="Close"
        >
          Menu
        </div>
      </button>
    </div>

    <div class="search-container grid-search">
      <form class="site-search">
        <span class="sr-only" id="SearchInput">Custom Google Search</span>
        <input
          type="text"
          id="q"
          name="q"
          aria-labelledby="SearchInput"
          placeholder="Search this website"
          class="search-textfield"
        />
        <button type="submit" class="search-submit">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            x="0px"
            y="0px"
            width="17px"
            height="17px"
            viewBox="0 0 17 17"
            style="enable-background:new 0 0 17 17;"
            xml:space="preserve"
          >
            <path
              class="blue"
              d="M16.4,15.2l-4-4c2-2.6,1.8-6.5-0.6-8.9c-1.3-1.3-3-2-4.8-2S3.5,1,2.2,2.3c-2.6,2.6-2.6,6.9,0,9.6
        c1.3,1.3,3,2,4.8,2c1.4,0,2.9-0.5,4.1-1.4l4.1,4c0.2,0.2,0.4,0.3,0.7,0.3c0.2,0,0.5-0.1,0.7-0.3C16.7,16.2,16.7,15.6,16.4,15.2
        L16.4,15.2z M7,12c-1.3,0-2.6-0.5-3.5-1.4c-1.9-1.9-1.9-5.1,0-7C4.4,2.7,5.6,2.1,7,2.1s2.6,0.5,3.5,1.4c0.9,0.9,1.4,2.2,1.4,3.5
        c0,1.3-0.5,2.6-1.4,3.5C9.5,11.5,8.3,12,7,12z"
            />
          </svg>
          <span class="sr-only">Submit</span>
        </button>
        <button class="search-close">Close</button>
      </form>
    </div>
  </div>
</div>
<!--end site-header-->
```

## Specs

| Property     | Value            |
| ------------ | ---------------- |
| Machine name | ds-site-header   |
| JavaScript   | no               |
| SCSS         | ./src/index.scss |

## Project installation

The instructions assume familiarity with [npm](https://npmjs.com) package management tool and [Sass](https://sass-lang.com/).

1. Include **SCSS** in your compiler.
2. Add the **sample markup** from the component to your HTML.
3. Edit the “logo”, “logo-state”, and “logo-department” elements to meet your own department’s branding needs.
4. Connect the search form to your own system.

Note: There are two versions of the markup, one with and one without a logo.

## CSS variables

The following [CSS variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties) are used in this component:

- `--org-name-state-font`
- `--org-name-state-font-size`
- `--org-name-state-font-weight`
- `--org-name-state-line-height`
- `--org-name-state-text-transform`
- `--primary-color`
- `--primary-dark-color`
- `--secondary-color`
- `--small-text`
- `--standout-color`
- `--w-lg`
- `--white`
- `--gray-100`
- `--gray-300`

All CSS variables define their own fallback value so you do not have to use additional CSS unless you want to change them. You may define your own value for the variable by adding your own style rules. Here is an example defining the global hex value for a CSS variable named “--primary-color”:

```css
:root {
  --primary-color: #064e66;
}
```

## Accessibility

### Component-specific accessibility review

- If you are using search component make sure it has span label saying that is “google custom search”, make sure that span  has `sr-only` class and `id` attribute  that is referenced in search input box `aria-labelledby` attribute. Also, make sure that google search submit button has span with class `sr-only` and the word “submit” in it.
- If you are using search and menu components make sure that mobile buttons that activate those components have no focus in the desktop view. Also, make sure that they have correct `area-expanded` attributes  whenever the sections that they are controlling are either expanded or collapsed.
- If you are using site logo image make sure it has proper alt text.
- Make sure that all links and buttons have solid, 2px outline that uses `--highlight-color` variable on focused state.

### Standard accessibility review

As a component in Alpha status, this component must pass the following accessibility reviews every time a new version is published:

- Tested with the [axe](https://www.deque.com/axe/) accessibility tool and passes all automated [WCAG](https://www.w3.org/TR/WCAG21/) Level AA checks
- Reviewed with the [VoiceOver](https://www.apple.com/voiceover/info/guide/_1121.html) screen reader on desktop
- Verified keyboard navigation and that all actionable elements of the component are reachable via keyboard commands only
- Reviewed component layout on a variety of screen sizes

## Progressive enhancement

This is an HTML- and CSS-only component. JavaScript is not required. It uses [CSS variables](<https://developer.mozilla.org/en-US/docs/Web/CSS/var()#syntax>) to inherit design token values. Token definitions are not required because these style rules provide fallback values.

## Content model

This component requires the following content assets and configuration variables.

- Organization or project name `string`, `plain text`
- Try to match the height of your logo to the website's title (including the State of California heading). This is roughly 88px. Do not make your logo less tall than this.
- Since the name of the website in part of the header, your logo does not need to include your name. You can use just the visual symbol, if you have one.
- If the site title appears too close to the search bar, then your logo may be too wide.
- Search feature will require a CX Google search id. Part of sitewide config settings, see `odi-publishing` examples.

## Contributor/developer documentation

- [Component information](https://github.com/cagov/design-system/blob/main/components/README.md)

- [Component README template](https://www.notion.so/odi-engineering/Component-documentation-template-2da3975cc0954174ace43004d151451c)

- [Unit tests](https://github.com/cagov/design-system/blob/main/components/UNIT-TESTS.md)
