# Apeperia

## What is this "Apeperia"?

This is the result of an exercise I made after attending a course on Responsive Layouts at <a href="https://www.alura.com.br/">Alura</a>. While doing this project I also attended a course on web accessibility, so I made some adjustments to make it more accessible.

## Responsive Layout

The layout was based on this <a href="https://www.figma.com/file/FidBn9f7BoBCoEs19EzbUD/Apeperia-Mobile-First"> figma </a>. It has a different layout for smartphones, tablets and desktop computers.

### Mobile first

The first layout implemented was mobile, for the following reasons:

* Simpler layout, resulting in less css that would need to be fixed in other layouts.
* Mostly vertical layout, just like the HTML structure.
* <a href="https://gs.statcounter.com/platform-market-share/desktop-mobile-tablet">Most of the use of the internet today is done by smartphones.</a>

### Relative units

Most of the measurement units used were relative (mostly rem, or %), some absolute measurements were used to restrict maximum size.

## Accessibility

The site was tested using NVDA. The HTML was adjusted for a better screen reading.
