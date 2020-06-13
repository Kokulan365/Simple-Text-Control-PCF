# About Simple Text Control
A simple yet very flexible PCF control to display text with custom style using HTML tags or CSS styles on a Unified Interface Form on CDS.

Text could be displayed with custom formats using HTML tags / CSS styles. The control allows customizer to add longer text than out of the box label control or section label. A maximum of about 800 characters in total can be added. The number 800 includes any HTML tags added to the text. PCF configuration page only allows 160 characters. To get around that limit, this control has 5 text input properties (Text  Part 1-5), allowing you to add about 800 characters. Text entered in Part 1-5 are all combined into one long string. The text is rendered using a span tag and the span is added to a div container. And the text itself is set using innerHTML property of the span element, making it easy to add html tags with the text to format or set the style.

![Examples Screenhot](https://github.com/Kokulan365/Simple-Text-Control-PCF/blob/master/Documentation/Examples.png)


# Downloading and Installing the control

Both managed and unmanaged versions of the solution are released and they can be found on releases page of this repository. Please follow the link below to get to release page.
[Release Page](https://github.com/Kokulan365/Simple-Text-Control-PCF/releases)


# How to use the control
The control currently only binds to a "Single Line of Text"  and the control can be added to the form by going into Controls tab of the field property and clicking on Add Control button as shown below.
![Release Page](https://github.com/Kokulan365/Simple-Text-Control-PCF/blob/master/Documentation/howtoadd.png)

Once you added the control, you can set the text and style as shown in the screenshot below.
![Release Page](https://github.com/Kokulan365/Simple-Text-Control-PCF/blob/master/Documentation/howtouse.png)

