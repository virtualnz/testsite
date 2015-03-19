---
published: true
layout: default
category: exhibit
title: .jpeg
section: Stories
---

## The JPEG format

Because JPEGs are more heavily compressed than other image formats, their information is more volatile and likely to expand at high speed through an unchecked buffer, poorly allocated resource or any other available system space. I'd guess you're probably losing image data through one of these means.
You see, when you load a JPEG into memory, the EXtra colour Information Format (EXIF) header is loaded into RAM in order to prepare the video prebuffer for the incoming high-speed flow of colour information from the uncorked JPEG. If your bus isn't ready for this information, the rapidly decompressing file information can flow through other parts of your system.
Ordinarily this isn't a problem: as a matter of fact, JPEG was designed for this sort of thing. Older computers couldn't handle the explosive power behind the fledgeling image decompression algorithm, so rather than fight it, image experts invented the Jampacked Picture Extraction and Gathering (JPEG) protocol. They cleverly decided to allow the image data to spray wherever it would, knowing that after the extraction phase would send raw data all over the inside of the computer, the gathering phase would locate it all and reassemble it into an image. With the advent of faster computers the delay between spray and collection is so small as to be unnoticeable, while newer and bigger video cards are more capable of withstanding the onslaught of colours.
Still, the primary weakness of this algorithm is the haphazard placement of decompressed data. There's just too much of it to channel through normal means, so any loss of data containment results in corrupted images. In your case, it would appear that you're losing image data through the empty hole where your goddamned shift key should be.
<br><br>
-- anonymous.
