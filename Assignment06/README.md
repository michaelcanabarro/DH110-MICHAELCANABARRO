# Government Support for Accessibility to Higher Education Among High School Students in Massachusetts
## Assignment 06: Interface Design
### Michael Canabarro | DH 110 | Fall 2021

---

## Introduction

In [Assignment 5](https://github.com/michaelcanabarro/DH110-MICHAELCANABARRO/blob/main/Assignment05/README.md), I built the basic structure of my website based on the findings from Assignments 1-4. For this assignment, I will be elaborating on that structure and exploring the more cosmetic features of my website, from button shapes and layouts to font selection. I will also be conducting an impression test with a user to help determine which variation is the most desirable for the people who will be using the website and test it to ensure adherence to accessibility standards. In completing these tasks, I hope to gain an even clearer vision of what the final product will look like thanks to valuable information from user feedback.

---

## Screen Designs

Below are screenshots of the various screens of my website, according to the wireflows and tasks outlined in [Assignment 5](https://github.com/michaelcanabarro/DH110-MICHAELCANABARRO/blob/main/Assignment05/README.md). Click [here](https://www.figma.com/file/5E9fUXyux4GbmlvOCSaLfL/A06_Digitized_Wireflows?node-id=0%3A1) to access the Figma file I used, which includes a clickable prototype (click "Prototype" on the right, then press the Play button next to Flow 1 on the first screen). Saved graphic design system information, including fonts and sizes, colors, and grid layouts, can be found there as well.

<img width="543" alt="A06_screens_1" src="https://user-images.githubusercontent.com/91518358/140865188-3b7c7a64-7a76-4910-9f5a-2ed05ff88d2f.png">
<img width="540" alt="A06_Screens_2" src="https://user-images.githubusercontent.com/91518358/140865194-e1eef56c-a657-4fb3-9682-be17636bfcfe.png">
<img width="547" alt="A06_Screens_3" src="https://user-images.githubusercontent.com/91518358/140865195-3e64286e-bbdf-4c64-92e7-4d8d397796ff.png">
<img width="542" alt="A06_Screens_4" src="https://user-images.githubusercontent.com/91518358/140865197-c48e7f09-67c0-4ecf-b368-c5d5d6f3bb5f.png">
<img width="546" alt="A06_Screens_5" src="https://user-images.githubusercontent.com/91518358/140865198-0e43bf79-b336-4821-9393-1014f23d1c53.png">

### Layout Test

Here is a screenshot capturing the homepage's adherence to the grid system referred to in class. For this website, I used a 6x11 grid to allow for versatility in the design while retaining a visible structure.

<img width="199" alt="A06_Grid" src="https://user-images.githubusercontent.com/91518358/140866341-55e80932-fda7-4e74-bd9c-cce343a8f571.png">

### Typographic Variations (3)

As for typographic variation, I explored the fonts Roboto, Rubik, and Quicksand because they had a good amount of variation in roundness, angulature, and thickness. Here are those variations:

<img width="557" alt="A06_Font" src="https://user-images.githubusercontent.com/91518358/140870233-d4d0b42b-75b2-47e4-8361-67e26e1f86bc.png">

### Shape Variation (3)

I tested a rounded rectangle shape, as well as an extreme sharp-cornered rectangular shape and a combination of the two to get a good variety of options.

<img width="555" alt="A06_Shape" src="https://user-images.githubusercontent.com/91518358/140870249-1250502a-2d0f-45ec-972c-31e174233537.png">

### Color Variation (2)

For colors, I created a light mode and dark mode for my website. I used a cream base on the light mode version to avoid a bright white background, which can cause eye strain and waste screen power. On that variation, I also focused on making the buttons and text pop to make users aware of their options. For the dark mode, I more or less inverted the color scheme of the light mode, with a notable exception being the button colors, which remained dark blue. This was mainly to preserve the darkness of the screen; instead, I made the buttons more noticeable by making the border color white, which has a greater contrast with the background color.

<img width="373" alt="A06_Color" src="https://user-images.githubusercontent.com/91518358/140870545-ced2f5b9-d671-4086-a056-5aae4f035796.png">

---

## Impression Test

I conducted the impression test of my design variations over Zoom. I didn't record it for the sake of privacy, but I took notes, which I will summarize and elaborate on below. To make the test as realistic as possible, I shared a window just containing one variation at a time, so as to allow the participant to view each option independently and for an equal amount of time:

<img width="1440" alt="A06_TestWindow" src="https://user-images.githubusercontent.com/91518358/140879986-533a8a73-a2fa-4db6-abf5-8ec664d6be29.png">

Similarly, font names were removed from the Figma screenshots and frame titles anonymized to help reduce any external bias. I broke up the test into three tests: type, shape, and color. Before each round, I primed the participant by telling her what the category of the test was so that she would know what to pay attention to in terms of design elements. She was given uninterrupted 5-second rounds to look at each variation, and at the end of each category I asked her what stood out or what she preferred.

### Font

With regards to the font, the participant preferred the first option (Roboto). She mentioned that it stood out to her because it felt "serious," which she believed was appropriate for a government website that deals with financial aid. Of the other two fonts, Rubik and Quicksand, she noted that they appeared to be "aimed at a younger audience," which ultimately is true to an extent, but probably wouldn't accommodate older parents and guardians very well.

### Shape

As for the button shapes, the participant strongly disliked the third option, the combination of corners and curves. During the test, she said that "something just feels off" about it, and continued to say that it felt like she didn't know what to click on. Needless to say, I won't be considering that option very strongly. She liked both the rounded and sharp rectangles, and was indifferent between them.

### Color

The participant preferred the light mode version of the website, stating that there was a good contrast between the buttons and the background, as well as in the overall color scheme. On the other hand, she mentioned that dark mode screens are "always" harder for her to read because of the light text on a dark background. As a result, she did not prefer the dark mode option. This might be due to mainly personal preference, but I will continue to test the dark mode variant to gauge the severity of this potential issue.

### Results and Decisions

Thanks to the three rounds of testing, I was able to compile a combination of elements that I will move forward with based on user feedback. I will be sticking with Roboto for the font (size 28 for titles and 18 for body and buttons), as well as the rounded rectangle shape option. As for the colors, I will continue with my light mode scheme consisting of a cream base and navy blue accents, but continue to develop the dark mode version as well to accommodate to more users.

---

## Accessibility Test

To ensure the accessibility of the website, I tested both the light and dark mode variations with the [Stark](https://www.figma.com/community/plugin/732603254453395948/Stark) plugin on Figma. As seen in the screenshots below, both color schemes meet both WCAG2.0 AA and AAA standards by a good margin:

<img width="598" alt="A06_Contrast_Light" src="https://user-images.githubusercontent.com/91518358/140871410-d72067cf-c268-4e24-bab6-53ae23de706d.png">
<img width="597" alt="A06_Contrast_Dark" src="https://user-images.githubusercontent.com/91518358/140871425-8493b4de-1561-4abe-b4e1-45769560af7f.png">

## Reflection

As with the past assignments, the interface design process was very enlightening for me. I learned a lot about the great degree of planning and intention that goes into every element in a design, from laying out a grid to making subtle tweaks to shapes, fonts, and more. The impression test was yet another testament to the importance of user feedback in the design process; it was interesting to see the preferences my participant had and how strongly she felt about some of the elements, especially the button shape. In hindsight, I could have tested more different variations in each category; for example, I could have changed the size of the fonts or the layout of the buttons on the page. My designs were admittedly similar in overall composition, so further testing will be needed to determine if the actual layout is something that users will like. But, this round of testing gave me useful insights into which elements I would feel more comfortable continuing with as opposed to others. I enjoyed the process a lot, and I will be sure to incorporate my findings into future iterations and conduct more testing where necessary so that the final product can be the best it can be.
