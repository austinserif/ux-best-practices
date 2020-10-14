# UX Design Resources and Best Practices:
1. [Introduction](#introduction)
2. [Color](#color)
    1. [Best Practices](#color-bestPractices)
    2. [Resources & Examples](#color-resources)
3. [Typeface](#typeface)
    1. [Font Types](#typeface-fontTypes)
    2. [How To Use Them](#typeface-howToUseThem)
4. [Components](#compontents)
    1. [Navigation](#components-navigation)
    2. [Forms](#components-forms)
    3. [Buttons](#compontents-buttons)
    4. [Landing Pages](#components-landingPages)
4. [Footnotes](#footnotes)

## Introduction <a name="introduction"></a>
Design is not always a disciplined discipline. 

## Color <a name="color"></a>
The first paragraph text

### Best Practices <a name="color-bestPractices"></a>
1. COMING SOON!

### Resources & Examples <a name="color-resources"></a>

1. [Found Color Archive](https://foundcolor.co/)
    "Color schemes for web, UI and app sourced from minimal photography of everyday objects and encounters." 

## Typeface <a name="typeface"></a>
1. Font Types <a name="typeface-fontTypes"></a>
2. How To Use Them <a name="typeface-howToUseThem"></a>
3. Font Size
    There are two types of font-sizes: absolute, and relative. Pixels (px) are absolute units. 16px text wrapped in a paragraph block (`<p style="font-size: 16px">Text here!</p>`) will be the same size on an iPhone as an iMac. However, 4vw text on a 320px wide iPhone screen is (.04 * 320) 12.8px, which is quite a bit smaller than 4vw text on a 1440px wide screen (.04vw * 1440 = 57.6px).



    Simple Example: 
    ```css
    html {
        font-size: 100%;
    }

    @media (min-width: 700px) {
        h1 {
            font-size: 2rem; /* 2rem is the same as saying two times the default root element font-size, which in most cases is 16px. So we can say with a high degree of confidence that our h1 font-size for screens over 700px (unless there is another media query bound) will be around 32px. */
        }
    }

    @media (min-width: 1000px) {
        h1 {
            font-size: 1.5rem;
        }
    }
    ```

## Components <a name="components"></a>
1. Navigation <a name="components-navigation"></a>
2. Forms <a name="components-forms"></a>
    1. Real-Time Input Validation
        This tip from Toptal Design-lead Lubos Volkov should be clear and obvious. He notes, "[w]henever possible give give user real-time validation. This will help prevent any issues prior to clicking on the submit button."<sup id="a1">[1](#f1)</sup>

        https://www.instagram.com/p/CB2-T64FuDr/
3. Buttons <a name="components-buttons"></a>
4. Landing Pages <a name="components-landingPages"></a>

## Footnotes <a name="footnotes"></a>
<b id="f1">1</b> Quote by Lubos Volkov, lead designer at [Toptal](https://www.toptal.com). See the original post on his [instagram page](https://www.instagram.com/p/CB2-T64FuDr/)  [↩](#a1)
