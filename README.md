# swagger-ui-open-response
Chrome extension to use with Swagger UI - Adds button to open the response in a new tab


## Information
It works on matching URL's - https://\*.localhost/\*

## How to add chrome extensions

1. Visit chrome://extensions.
2. Enable Developer mode by ticking the checkbox in the upper-right corner.
3. Click on the "Load unpacked extension..." button.
4. Select the <b>directory</b> containing your unpacked extension.

## How it works
It will add a button "Open" next to the already existing "Download" button on the response box.
<img src="https://i.imgur.com/Mnmd6Vq.png"/>

You can click it and it will open a new tab populated with the html from the response.

This is usefull when you have exception pages like .NET.
