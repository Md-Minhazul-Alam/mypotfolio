# Testing

[Return to README.md](README.md)


---

## Code Validation

All HTML and CSS files were validated using the official [W3C HTML Validator](https://validator.w3.org/) and [Jigsaw CSS Validator](https://jigsaw.w3.org/css-validator/).

### HTML Validation

| Page | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
| Home | [index.html](https://md-minhazul-alam.github.io/mypotfolio/index.html) | [W3C Validator](https://validator.w3.org/) | ![screenshot](/assets/testing/validation/html/home.png) | Passed – no major errors |
| About | [about.html](https://md-minhazul-alam.github.io/mypotfolio/about.html) | [W3C Validator](https://validator.w3.org/) | ![screenshot](/assets/testing/validation/html/about.png) | Passed – clean markup |
| Gallery | [gallery.html](https://md-minhazul-alam.github.io/mypotfolio/gallery.html) | [W3C Validator](https://validator.w3.org/) | ![screenshot](/assets/testing/validation/html/gallery.png) | Passed – valid structure |
| Contact | [contact.html](https://md-minhazul-alam.github.io/mypotfolio/contact.html) | [W3C Validator](https://validator.w3.org/) | ![screenshot](/assets/testing/validation/html/contact.png) | Passed – form validated correctly |
| 404 Page | [404.html](https://md-minhazul-alam.github.io/mypotfolio/404.html) | [W3C Validator](https://validator.w3.org/) | ![screenshot](/assets/testing/validation/html/404.png) | Passed – valid syntax |

---

### CSS Validation

| File | URL | Screenshot | Notes |
| --- | --- | --- | --- |
| style.css | [CSS Validator](https://jigsaw.w3.org/css-validator/) | ![screenshot](/assets/testing/validation/css/style.png) | Passed – no major issues detected |

---


## Responsiveness

Tested on desktop, tablet, and mobile devices.

| Page | Desktop | Mobile | Tablet |
| --- | --- | --- | --- |
| Home | ![screenshot](/assets/testing/responsive/home-desktop.png) | ![screenshot](/assets/testing/responsive/home-mobile.png) | ![screenshot](/assets/testing/responsive/home-tablet.png) |
| About | ![screenshot](/assets/testing/responsive/about-desktop.png) | ![screenshot](/assets/testing/responsive/about-mobile.png) | ![screenshot](/assets/testing/responsive/about-tablet.png) |
| Gallery | ![screenshot](/assets/testing/responsive/gallery-desktop.png) | ![screenshot](/assets/testing/responsive/gallery-mobile.png) | ![screenshot](/assets/testing/responsive/gallery-tablet.png) |
| Contact | ![screenshot](/assets/testing/responsive/contact-desktop.png) | ![screenshot](/assets/testing/responsive/contact-mobile.png) | ![screenshot](/assets/testing/responsive/contact-tablet.png) |
| 404 Page | ![screenshot](/assets/testing/responsive/404-desktop.png) | ![screenshot](/assets/testing/responsive/404-mobile.png) | ![screenshot](/assets/testing/responsive/404-tablet.png) |



## Browser Compatibility

The site was tested across multiple browsers for visual and functional consistency.

| Page | Chrome | Firefox | Edge | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](/assets/testing/browser/home-chrome.png) | ![screenshot](/assets/testing/browser/home-firefox.png) | ![screenshot](/assets/testing/browser/home-edge.png) | Works consistently |
| About | ![screenshot](/assets/testing/browser/about-chrome.png) | ![screenshot](/assets/testing/browser/about-firefox.png) | ![screenshot](/assets/testing/browser/about-edge.png) | Works as expected |
| Gallery | ![screenshot](/assets/testing/browser/gallery-chrome.png) | ![screenshot](/assets/testing/browser/gallery-firefox.png) | ![screenshot](/assets/testing/browser/gallery-edge.png) | No visual issues |
| Contact | ![screenshot](/assets/testing/browser/contact-chrome.png) | ![screenshot](/assets/testing/browser/contact-firefox.png) | ![screenshot](/assets/testing/browser/contact-edge.png) | Works as expected |
| 404 Page | ![screenshot](/assets/testing/browser/404-chrome.png) | ![screenshot](/assets/testing/browser/404-firefox.png) | ![screenshot](/assets/testing/browser/404-edge.png) | Consistent across browsers |

---


## Lighthouse Audit

The site was audited using **Google Chrome Lighthouse** for accessibility, SEO, and performance.

| Page | Mobile | Desktop |
| --- | --- | --- |
| Home | ![screenshot](/assets/testing/lighthouse/home-mobile.png) | ![screenshot](/assets/testing/lighthouse/home-desktop.png) |
| About | ![screenshot](/assets/testing/lighthouse/about-mobile.png) | ![screenshot](/assets/testing/lighthouse/about-desktop.png) |
| Gallery | ![screenshot](/assets/testing/lighthouse/gallery-mobile.png) | ![screenshot](/assets/testing/lighthouse/gallery-desktop.png) |
| Contact | ![screenshot](/assets/testing/lighthouse/contact-mobile.png) | ![screenshot](/assets/testing/lighthouse/contact-desktop.png) |
| 404 Page | ![screenshot](/assets/testing/lighthouse/404-mobile.png) | ![screenshot](/assets/testing/lighthouse/404-desktop.png) |

---


## Defensive Programming

Defensive programming was manually tested through various user interaction scenarios.

| Feature | Expectation | Test | Result | Screenshot |
| --- | --- | --- | --- | --- |
| Navigation | Menu links should work correctly on all pages | Clicked each navigation link | All links worked properly | ![screenshot](/assets/testing/features/header.png) |
| Buttons | Hero “About Me” button should redirect properly | Clicked “About Me” button on hero section | Redirected successfully | ![screenshot](/assets/testing/features/hero.png) |
| Contact Form | Should not submit empty or invalid data | Tested with empty and incorrect inputs | Proper validation and error prompts | ![screenshot](/assets/testing/features/contact.png) |
| Responsive Layout | Content should not overlap on resize | Tested across device sizes | Layout remained consistent | ![screenshot](/assets/testing/responsive/home-mobile.png) |
| 404 Page | Should display friendly error message | Entered wrong URL | Custom 404 page appeared with Home link | ![screenshot](/assets/testing/features/404.png) |

---

## User Story Testing

| Target | Expectation | Outcome | Screenshot |
| --- | --- | --- | --- |
| As a visitor | I want to learn who Jackie is | “About Me” section clearly describes identity and interests | ![screenshot](/assets/testing/features/about.png) |
| As a visitor | I want to view travel photos | Gallery displays organized and high-quality travel photos | ![screenshot](/assets/testing/features/gallery.png) |
| As a visitor | I want to contact Jackie easily | Contact form and info displayed cleanly | ![screenshot](/assets/testing/features/contact.png) |
| As a visitor | I want a clear 404 page if I reach a broken link | 404 page clearly guides back to Home | ![screenshot](/assets/testing/features/404.png) |
| As a visitor | I want the site to be mobile friendly | Layout adapts perfectly on all screen sizes | ![screenshot](/assets/testing/responsive/home-mobile.png) |

---

## Bugs

- **Navigation overlap on small screens**  
  **How found:** During responsive testing  
  **Fix:** Adjusted padding and added media queries  
  **Status:** Fixed  

- **Button alignment issue in hero section**  
  **How found:** Visual testing on mobile view  
  **Fix:** Adjusted flex alignment and spacing  
  **Status:** Fixed  

- **Contact form validation not blocking empty fields**  
  **How found:** Tested form submission without input  
  **Fix:** Added `required` attributes to input fields  
  **Status:** Fixed  

- **Broken link in footer**  
  **How found:** Manual link testing  
  **Fix:** Updated href to correct page path  
  **Status:** Fixed  

---

### Known Issues

- **Known Issue:** None  
- **Description:** All known bugs have been fixed.  
- **Possible Solution:** N/A  
- **Status:** None  

> [!IMPORTANT]
> The site functions as intended across all tested environments. While extensive testing was conducted, minor issues may still appear in rare cases.

