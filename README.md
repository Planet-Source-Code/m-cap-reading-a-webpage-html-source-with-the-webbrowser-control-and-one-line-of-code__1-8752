<div align="center">

## Reading a webpage HTML source with the WebBrowser control \(and one line of code\)\.


</div>

### Description

Downloads the HTML source of a webpage using the MS WebBrowser control.
 
### More Info
 
A reference to a MS WebBrowser control

I found many examples about how to download the HTML source of a webpage by means of the Winsock control or the Internet Transfer control, but not with the WebBrowser control. The Winsock control is too complex to me, and the Internet Transfer didn't work for me with pages larger than 5 Kb or so. I've found a one-line code that seems to work properly.

I'm a sort of a newbie about this topic, so please be patient. I'm posting it just to share something that I found useful.

A string containing the HTML source of the web page


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[m\.cap](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/m-cap.md)
**Level**          |Advanced
**User Rating**    |4.9 (78 globes from 16 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Internet/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-html__1-34.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/m-cap-reading-a-webpage-html-source-with-the-webbrowser-control-and-one-line-of-code__1-8752/archive/master.zip)





### Source Code

```
After navigating to the desired webpage, execute the following line:
myTextBox.Text = myWebBrowser.Document.documentElement.innerHTML
```

