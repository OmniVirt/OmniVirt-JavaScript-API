# OmniVirt JavaScript API - Sample Code
Example of JavaScript API for OmniVirt VR Player. The API can be called from your JavaScript function that run after OmniVirt embed code, or JavaScript that is placed inside our editor's Custom HTML. For full API documentation, please visit https://www.omnivirt.com/developer/. Learn more about OmniVirt at https://www.omnivirt.com/

# 3 Easy Steps
1. Upload your 360° video into https://www.omnivirt.com/
2. Place default OmniVirt embed code from OmniVirt video page. https://www.omnivirt.com/view/24/
3. Place your custom API code inside <script> tag after OmniVirt embed code

```javascript
<script type="text/javascript" src="//upload.omnivirt.com/scripts/embed.js"></script>
<script>
... OmniVirt Embed Code ...
</script>

<script>
... Your Custom JavaScript Here ...
OmniVirt.api.broadcastMessage('seek', 0.5); // jump to the middle timeline of the video.
</script>

```

# Read our API full documentation at https://www.omnivirt.com/developer/
* OmniVirt.api.receiveMessage
* OmniVirt.api.sendMessage
* OmniVirt.api.broadcastMessage
