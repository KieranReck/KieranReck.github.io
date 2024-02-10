---
title: "Lobed Corners - A DFM Secret"
layout: posts
tagline: ""
header:
    teaser: /assets/images/Lobe-Metalwork(large-tool-diagram).jpg
tags:
#  - Electronics
#  - Modular Synth
#  - Eurorack Module
  - Lessons Learned
  - Design for Manufacture
#  - Code
# --------
#  - Hobby
  - Professional

gallery1:
  - url: /assets/images/Rad-Metalwork(ISO).jpg
    image_path: /assets/images/Rad-Metalwork(ISO).jpg
  - url: /assets/images/Rad-Metalwork(Front-View).jpg
    image_path: /assets/images/Rad-Metalwork(Front-View).jpg

gallery2:
  - url: /assets/images/Rad-Metalwork(small-tool-diagram).jpg
    image_path: /assets/images/Rad-Metalwork(small-tool-diagram).jpg
    alt: "Tool Path for a small diameter milling tool."
  - url: /assets/images/Tool-Bend-Diagram.png
    image_path: /assets/images/Tool-Bend-Diagram.png
    alt: "Milling tool bending due to length required for deep cuts"

gallery3:
  - url: /assets/images/Lobe-Assy(front-View).jpg
    image_path: /assets/images/Lobe-Assy(front-View).jpg
  - url: /assets/images/Lobe-Metalwork(Front-View).jpg
    image_path: /assets/images/Lobe-Metalwork(Front-View).jpg
---

Picture this, you have designed a housing for some delicate electronics, it strikes the perfect balance between aesthetics, protection, and thermal transfer, machined out of a single block of aluminium to keep things simple, but you get your first quote back from the machinist and it is astronomical. After some digging you find out that your beautiful design has one very expensive flaw, a large area of material needs to be removed but you have only allowed space for a small radius in the corners.

{% include gallery id="gallery1" layout="half" %}

Machinists like to perform a cut in the minimum number of operations, this leads them to use the largest machining tool they can to achieve all of the features. If your design only has a 2mm radius in the corners, they will want to use the 2mm (4mm dia) tool. Intuitively, small tools remove less material at a time which means it takes longer to complete the cut. Less intuitively, the deeper a cut is the longer the tool needs to be, and when using small diameter/thin tools this length tends to bend the tool, adding unnecessary wear and stress. The machinist factors this into their quote and the price increases.

{% include gallery id="gallery2" layout="half" caption="Left: Tool Path for a small diameter milling tool  |  Right: Milling tool bending due to length required for deep cuts." %}

What if they use a large tool for most of the cut and swap to the small one just for the corners? That tool swap takes time and now you are adding wear to two tools. The price stays high.

![Rad-Metalwork(2Tools-Diagram)](../assets/images/Rad-Metalwork(2Tools-Diagram).jpg){: .align-center}

So, what if they used a large diameter tool? It wouldn't be able to remove all of the required material in the corners. You could add a process to swap to a smaller tool just for the corners, but that takes additional time and time is money.

![Rad-Metalwork(large-tool-unmachined-areas)](../assets/images/Rad-Metalwork(large-tool-unmachined-areas).jpg){: .align-center}

Now, what if we approach this design with a DFM (Design For Manufacture) mindset? How would you tweak the profile to achieve the same functionality but allow for just the large cutter to be used? 

#### Lobes!

By flaring the corners you open up your radii significantly whilst leaving all other dimensions untouched. The machinist can use a larger cutter, which takes less time, creates less tool wear under less stress, reducing the price you need to pay.

{% include gallery id="gallery3" layout="half" %} 

![Lobe-Metalwork(large-tool-diagram)](../assets/images/Lobe-Metalwork(large-tool-diagram).jpg){: .align-center}
Tool Path for a large diameter milling tool when the design include lobed corners.

### Lessons learned

- Small radii in the corners of large cuts puts the price of your part up significantly
- When performing a deep cut, small diameter mill tools are placed under greater stress, causing them to bend, wear quicker, and increase the change of breaking
- If your design desperately requires these small radii they can be achieved, but at a cost.
- If your design allows it, add lobes to the corners to allow the use of larger tools.

***