# Demo on how to create a UI component in Blazor.

This project was created to show how to create your own UI component library and call it with in a Blazor application.  I used a web assembly project but everything would work the same for a Server Side project.

by [David Gallivan](http://twitter.com/CodingwithDavid)


## Why

I was reviewing some sample projects and I notice they had to add a css link for each style sheet file they used with in the UI components.  It got me wondering

## "If your UI components are in a different assembly and you used CSS isolation, do you need to include the link to the _content style sheet in the main program index file?"

## Getting Started

1. Clone this repository

   ```Command Line
   git clone https://github.com/CodingWithDavid/BlazorOwnComponetLib
   cd BlazorOwnComponetLib
   ```

1.	Open in Visual Studio or Visual Code
a.	With Visual Code you will need to install the C# extensions
2.	Press F5

## What's in the App

1. Basic web assembly template project
   a. The counter page was removed
2. A component library that contains a "Spinner" component
   a. This is a simple loader component used to demonstrate the idea of using CSS isolation in a component library



## Problems or Suggestions

[Open an issue here]( https://github.com/CodingWithDavid/BlazorOwnComponetLib/issues)

## Thank You


## Resources

- [VS Code](https://code.visualstudio.com)
- [Visual Studio]( https://visualstudio.microsoft.com/)



