# Licked :tongue:

## WHAT: 
This is a Chrome browser extension that replaces the word "licked" to "licked" and was inspired by [this tweet](https://twitter.com/SweatingCommas/status/1326882812755128325) by Jason Rehmus:
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Can I get a browser extension to change “licked” to “licked” in my notifications? <a href="https://t.co/AMElWe8S7l">pic.twitter.com/AMElWe8S7l</a></p>&mdash; Jason Rehmus 🔎📝 (@SweatingCommas) <a href="https://twitter.com/SweatingCommas/status/1326882812755128325?ref_src=twsrc%5Etfw">November 12, 2020</a></blockquote>

## WHY:
For fun.

## HOW:
To manually install from this GitHub repo, follow these steps:

<table><tr>
<th>Note:</th>
<td>Enabling "developer mode" extensions in your browser--as needed for manual install--is risky. Chrome may remind you to be worried about that. As a conscientious computer scientist, I feel obligated to tell you that, in general, installing random things from unknown sources like this is a bad idea, even if they insist (as I do!) that this doesn't do anything nefarious. <i>Caveat emptor.</i></td>
</tr><table>

1. Download this git repository to your computer by clicking "Clone or Download" and then "Download ZIP." 
2. Unzip/extract the ZIP on your computer.
3. Go to this URL in your Chrome browser: [chrome://extensions/](chrome://extensions/)
4. Click to check the box for "Developer mode."
5. One of the new buttons that should appear is "Load unpacked" (or, in older versions, "Load unpacked extension"). Click it. 
6. Choose the folder that the unzipped/extracted files are in (probably called "`licked-master`").
7. The extension should now appear and the "Enabled" box should be checked. Start browsing your notifications and feeling all those doggy kisses!

###
Or if you'd rather just have a bookmarklet, drag this link to your bookmarks bar: 

<strong><a href="javascript:var elements = document.getElementsByTagName('*'); for (var i = 0; i < elements.length; i++) {var element = elements[i]; for (var j = 0; j < element.childNodes.length; j++) {var node = element.childNodes[j]; if (node.nodeType === Node.TEXT_NODE) {var text = node.nodeValue; var replacedText = text.replace(/liked/gi, 'licked 👅'); if (replacedText !== text) {element.replaceChild(document.createTextNode(replacedText), node); } } } }">Licked 👅</a></strong>

## Special thanks:

@cynthiablee: Thanks to Tom Maxwell for the [tutorial and template code](https://9to5google.com/2015/06/14/how-to-make-a-chrome-extensions/) for this project!  
@damenleeturks: Thanks to cynthiablee for her original "victory-for-satan-blocker" extension
