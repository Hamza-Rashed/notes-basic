# HTML Images :
> Web page images are stored in a separate image file, not in the HTML file. Images files may be included in HTML by the img tag.

> The img tag is self-terminating, so it doesn’t take an end tag. A simple example would look like


``` <img src="sailboat.gif" alt="a drawing of a sailboat" ```
	``` width="128" height="125"/>```

The src attribute is a URL indicating the location of the image file, either as a file relative to the present HTML file, or a remote file on a different web server. So the above code is rendered by the web browser as a picture:
a drawing of a sailboat

The alt attribute isn’t strictly required, but it is strongly recommended for any image that contributes to the information in the web page. The text may be simply a description of the image, or a textual replacement of the image. Consider how you want the page to appear in a web browser that doesn’t support images, or if the image is lost somehow. Also, web browsers for the sight-impaired can read aloud the alt text in place of the image.

The width and height attributes aren’t required either. Their function is to let the browser how much space to reserve for a picture before the picture is loaded.

# Video and audio on the web

Web developers have wanted to use video and audio on the Web for a long time, ever since the early 2000s
when we started to have bandwidth fast enough to support any kind of video (video files are much larger than
text or even images.) In the early days, native web technologies such as HTML didn't have the ability to
embed video and audio on the Web, so proprietary (or plugin-based) technologies like Flash (and later, Silverlight)
became popular for handling such content. This kind of technology worked ok, but it had a number of problems, 
including not working well with HTML/CSS features, security issues, and accessibility issues.

A native solution would solve much of this if implemented correctly. Fortunately, a few years later the HTML5 
specification had such features added, with the ```<video>``` and ```<audio>``` elements, and some shiny new JavaScript APIs
for controlling them. We'll not be looking at JavaScript here — just the basic foundations that can be achieved with HTML.

We won't be teaching you how to produce audio and video files — that requires a completely different skillset. 
We have provided you with sample audio and video files and example code for your own experimentation, in case
you are unable to get hold of your own.

![](https://i.ytimg.com/vi/mW3ZTjamJvg/maxresdefault.jpg)
