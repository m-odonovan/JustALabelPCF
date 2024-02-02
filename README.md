# JustALabelPCF
Just a Label - PCF Control for Model Driven Power App Forms

## Background
Have you ever wanted to place instructions on a model driven form? That is, you simply want a label with text placed on a form. This sample PCF conrol does that. Simply add to the form, set the text you want to display, and optionally add html style attributes to it.

<img src="https://raw.githubusercontent.com/m-odonovan/JustALabelPCF/main/images/JustALabel.gif" title="Just a Label PCF Control" />

## How to use

- Managed and unmanaged solution files provided, download the one you need, and install into your environment
- Add any single line text field to a model driven form. Don't worry, this control doesn't read or write to this field/column. It's just a requirement on how PCF controls work.
- In properties windown, Add Component, and browse for "Just a Label" control
- The text parameter is required i.e. what you want the label to show. You can add HTML elements into this e.g. <br/>
- The style paramter is optional i.e. you want to change the style of the control e.g. font-size:20px;color:#000000
- That's it, save and publish the form

## Provided "As-Is"
This is a a starter / sample. It hasn't been well tested, and is missing some key features that I hope to add over time. It not officialy supported by myself or Microsoft. However, because the unmanaged and managed solution is provided, you should be able to support it yourself, either directly or through a certified Microsoft partner.
