# marketing-website-refatoring

## Technology Used

| Technology Used         | Resource URL              |
| ------------- |:-------------:|
| HTML | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS  | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |
| Git | [https://git-scm.com/](https://git-scm.com/)     | 

## Description

This website has been a victim of "dirty code" things like having elements in places where its unreadable and hard to understand what the part of the code does. or even the website being unaccsesible to people with disabilities. im refactoring the code in order to make sure that its up to standards when it comes to website standards, and that elements are being used correctly and not confusing the program casuing it to load up the website slower.

## Code Refactoring Example


```html
<div class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </div>
```

Converting the (div) to the semantic element of header because the header element can hold sets of navigational links while division elements cant do it as well.

```html
<header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </header>
```

Changing divs in the header to (nav)

```html
<header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </header>
```