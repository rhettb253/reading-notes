# class-11.md

## Video and Audio Content

- Explain how the ability to use video and audio on the web has evolved since the early 2000s.

Originally it was available through 3rd party sources and there were security and accessibility issues but now we have the ability to use video and audio with native capabilities within HTML.

- Describe the use of the src and controls attributes in the <video> element.
  
The source creates a path to the video you want to use and the controls attribute allows us to stop and start the video and adjust the volume.
  
- Why is it important to have fallback content inside the <video> element?
  
Fallback content will be displayed if the browser accessing the page doesn't support the <video> element. It allows the user to understand or view the content in another way.
  
- Write a very short story where <audio> and <video> are characters.
  
One upon a time there were two friends who wanted to be the same but never coud be. One of them, Audio, was only two dimensional and the other, Video was three dimensional. When they were kids they were kept in the dark and the world could not see them for who they really were. Now that they are older the world they live in accepts them more and so they find themselves playing to gether in their World Wide Web.
  
## A Complete Guide To Grid

- How does Grid layout differ from Flex?
  
Flexbox is considered a one dimensional layout while grid is a two dimensional layout.
  
- Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

The grid container is element on which display: grid is applied. It’s the direct parent of all the grid items. The grid items are the children (i.e. direct descendants) of the grid container. The grid lines are the dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column.
  
## Responsive Images

- Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
  
Because we want to display identical image content on any screen size.
  
- Define the following <img> attributes srcset and sizes. Write an example of how they are used.
  
The 'srcset' defines the set of images we will allow the browser to choose between. The 'sizes' defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true. They are used to aid screen size changes, they choose differnet pictures that would work better with the new viewport.
  
- How is srcset more helpful for responsive images than CSS or JavaScript?

Srcset is more helpful because instead of the same picture expanding or shifting dimensions to fit its space on the screen it will invoke the use of a new image to better fit the new layout so resolution is not distorted as much or at all.
  
