## About Simple Text Control
A simple yet very flexible PCF control to display text with custom style using HTML tags or CSS styles on a Unified Interface Form in Model Driven Apps on Common Data Service (CDS) / Dynamics 365 / Power Platforms. The control could also be used for displaying lengthy text such as questions / instructions / information that cannot be displayed using out of the box label control or section / tab label.

Text could be displayed with custom formats using HTML tags / CSS styles. The control allows customizer to add longer text than out of the box label control or section label. A maximum of about 800 characters in total can be added. The number 800 includes any HTML tags added to the text. PCF configuration page only allows 160 characters. To get around that limit, this control has 5 text input properties (Text  Part 1-5), allowing you to add about 800 characters. Text entered in Part 1-5 are all combined into one long string. The text is rendered using a span tag and the span is added to a div container. And the text itself is set using innerHTML property of the span element, making it easy to add html tags with the text to format or set the style.

![Examples Screenhot](https://github.com/Kokulan365/Simple-Text-Control-PCF/blob/master/Documentation/Examples.png)


## Downloading and Installing the control

Both managed and unmanaged versions of the solution are released and they can be found on releases page of this repository. Please follow the link below to get to release page.

[Release Page](https://github.com/Kokulan365/Simple-Text-Control-PCF/releases)


## How to use the control
The control currently only binds to a "Single Line of Text"  and the control can be added to the form by going into Controls tab of the field property and clicking on Add Control button as shown below.

![How To Add](https://github.com/Kokulan365/Simple-Text-Control-PCF/blob/master/Documentation/howtoadd.png)

Once you added the control, you can set the text and style as shown in the screenshot below.

![How To Use](https://github.com/Kokulan365/Simple-Text-Control-PCF/blob/master/Documentation/howtouse.png)


## Sample Text 1 - Output and Configuration

![Sample Text 1](https://github.com/Kokulan365/Simple-Text-Control-PCF/blob/master/Documentation/TextSample1.png)

The above output was produced by the following configuration

__Text Part 1:__ `<span style="font-weight:bold"> Messages could be displayed with <span style="color:red">custom formats.</span></span>` to get user's attention,

__Text Part 2:__ The control allows you to add longer text than out of the box label control or section label.

__Text Part 3:__  A maximum of about 800 characters in total can be added. The 800 includes any HTML tags added to the text. PCF configuration page only allows 160 characters.

__Text Part 4:__  However, there are 5 properties - Text Part 1-5, allowing you to add about 800 characters.

__Text Part 5:__

__Text Style:__ color:black

__Div Container Style:__ background-color:#e6ffe6;


## Sample Text 2 - Output and Configuration

![Sampe Text 2](https://github.com/Kokulan365/Simple-Text-Control-PCF/blob/master/Documentation/TextSample2.png)


The above output was produced by the following configuration


__Text Part 1:__ Please make sure you `<strong>` talk to the customer `</strong>` before hand. Please `<span style="color:red">` remember `</span>` to send the documents 2 days

__Text Part 2:__  before the actual call. They can also be asked to send email to `<span style="color:blue">customerservice@testcompnay.com </span>`

__Text Part 3:__ And if they would like to call us on the phone, please give them `<span style="color:black">customer service number 011334444</span>`. Calls made with 

__Text Part 4:__  full preparation have most of the time ended in great `<strong><span style="color:green">success </span> </strong>`, so please make sure you prepare well.

__Text Part 5:__ if you would like to remind yourself of the terms and conditions, please go to the following link `<a href="https://www.google.co.uk/">Bing </a>`

__Text Style:__

__Div Container Style:__







