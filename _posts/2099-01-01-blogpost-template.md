---
title: "enter title here..."
layout: posts
tagline: ""
mermaid: false
header:
    teaser: /assets/images/< enter 4:3 CROPPED IMAGE filename + extension here >
tags:
#  - Electronics
#  - Modular Synth
#  - Eurorack Module
#  - Lessons Learned
#  - Design for Manufacture
#  - Code
#  - Jekyll / Github Pages
# --------
#  - Hobby
#  - Professional
---




>[!tip] Useful Liquid Tags - Delete before posting
{: .align-center width="400px"} - Needs to be inline with the image
>
{: .notice--primary} - needs to be the line below the **single line** of text

>[!success] Useful Liquid Tags - Adding a Gallery
>
>{% include gallery id="gallery" layout="half" caption="..." %}
>Layout="half"(2 images wide) or default 3 images wide

>[!caution] Useful HTML Tags - Adding a  single/half/third figure
```
<figure class="half">
    <a href="/assets/images/sealing-face-recessed.jpg"><img src="/assets/images/sealing-face-recessed.jpg"></a>
    <a href="/assets/images/sealing-face-recessed2.jpg"><img src="/assets/images/sealing-face-recessed2.jpg"></a>
    <figcaption>Photo: Sealing face is the ‘inner’ section of the top face.  
(O-Ring groove is found on the mating part).</figcaption>
</figure>
```

>[!note] Adding A Mermaid Diagram/Graph
>- Remember to set the frontmatter to `mermaid: true`, then just create a mermaid graph as per usual
>- Bare in mind that it uses an old version of mermaid, so some feature such as graph titles break functionality

>[!danger] Code Block Not Displaying Right?
>encase your code in the following liquid tags to ensure it doesn't get processed:
>```html
{% raw %}
>
{% endraw %}
>```
