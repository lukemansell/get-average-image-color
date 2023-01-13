# Get Average Image Color

## Summary
This NuGet package contains methods allowing you to get the average color of an image by either passing through the bytes of the image, or passing through the URL of an image.

The rgba hex value is then returned (eg: #ff000088).

This is a work in progress and I'm open to ideas on how to increase the speed of this and also how well it calculates the average color.

## How to use

Once installing this package, there are two methods you can use:

`GetAverageColourFromUrl(string url, string defaultColor = DefaultColor)`

`GetAverageColourFromBytes(byte[] imageBytes, string defaultColor = DefaultColor)`

An example might be:

`var averageColor = GetAverageColorFromUrl("https://www.google.com/images/branding/googlelogo/2x/googlelogo_color_92x30dp.png")`

