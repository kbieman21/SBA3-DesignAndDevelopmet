## SBA3 DESIGN AND DEVELOPMENT

Responsive grid-based page with HTML and Tailwind CSS
This project is from Frontend Mentor Challenges Bento Grid



## Overview
The goal of this project was to design and build a responsive grid-based page to demonstrate lesson learned about Tailwind CSS.
Each card represent different features, such as AI content writing, multi-platform scheduling, or audience growth statistics etc.

The layout adapts across different screen sizes

## Approaches and Customizations
I used Tailwind CSS for syling
I implemented a responsive grid layout using Tailwind's grid-col -1, grid-col -2, grid-col -4
Each card used min-h-[400px] for consistent hight
Applied col-span-2 and row-span-2


## Design and Customization
I custmized colors for each card
Responsive text- classes
optimized image handling with oject-contain, full width, and responsive scaling


## Performance Enhancement
I added loading="lazy" to images
I used utility classes for spacing such as padding, margin, gap

## Challenges and solutions
Chanllenges - add span to some cards
Solution - add responsive col-span or row-span



## Summary
This project was a great learning experience in responsive layout design using Tailwind CSS. It demonstrates the importance of adaptable UI components and design patterns that scale gracefully across screen sizes.




## Reflection
Main challenges during the project was to come up with the right grid layout and make it responsive across all screen sizes. The col-span-2 and row-span-2 are tricky and not easy to keep the layout consistent. Also using large, fixed font sizes caused issues with text overflow and it took me some time to fix. 

To solve the problem i started over my projcet by trying to adopt a mobile-first approach, and utilizing Tailwind CSS's responsive utility classess was very helpful. In addition, I read something about better performance on my way, and added the loading='lazy" for the images.

If given more time, I would still work on the grid. Though I use the col-span-2 and row-span-2 still I am a bit off of the image given for the requirement.
In addition, if given more time, I would spend more time on accessibility working with ARIA roles, keyboard navigation etc. I would also add more hover styling to some of the links.