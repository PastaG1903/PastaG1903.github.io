##### Monday
*12:27*
An attempt was made to seal the hole with the PDMS sample. As described in last Saturday's notes [[Week 2 (Aug 12 - Aug 16)]], a PDMS piece was cut with an area slightly bigger than the hole to cover. Something to note is that the hole in the microchannel has a square shape, but the hole made in the bottom acetate layer is rectangular, this was initially to expose some of the PSA glue and directly paste the substrate. This idea was discarded, as humidity and manipulation made the device non-reusable.

Looking at it another way, the glue and the acetate layers are in different levels. In the near micro scale, the adhesion was not perfectly leveled or aligned, which lead to leakages and further substrate detachment.

The same device was used for the idea mentioned above. In this scenario, instead of relying on adhesion or attachment caused by in-device materials (such as PSA layer), an external piece of PSA was used to keep the PDMS piece in place.

The device was placed upside down on a table, and the substrate was carefully placed on the hole. A small strip of PSA was placed on the substrate and device as follows: the center of the strip was pressed against the substrate; holding that pressure by hand, each side of the strip was pulled to maximize pressure and placed on the acetate layer. Only after both ends of the strip were pasted/placed, the pressure by hand was released.

Enough rotational speed (not tracked) was used to get the fluid to the other side of the substrate. Reciprocation was achieved successfully.

The issue that arose was that the substrate could not maintain the generated pressure for relatively long times or leakage occurs.

Regardless of the method used to attach (externally) the substrate onto the device, enough pressure maintained for enough time will cause leakage. An option to use this implementation is to redesign the device so that less pressure is necessary or to use the same design, but use high relaxation times (reverse flow time >> forward flow time) to have enough pressure relaxation to prevent leakages when the device accelerates again.

*19:20*
Now that the skin cutter have arrived and the testing mold for the PDMS cylinder has been designed, tomorrow I will cut a couple of pieces of PDMS in the lab and will go to the Innovaction Gym to cut the mold in acrylic sheets on thicknesses of both 2mm and 3mm. As mentioned on Thursday's notes on [[Week 2 (Aug 12 - Aug 16)]], pressure accumulated could cause the PDMS to fall out of the device. However, if the piece is to thick, even though it will be more resistant to the pressure, it could cause the piece to be more difficult to be properly placed and removed, potentially damaging the surface. Since the current width of the channel is 4mm, ranges between 3.8mm and 4.1mm will be tested for the laser cutter.

##### Tuesday
*12:28*
Went to CETEC to cut holes into a 2mm PMMA sheet. Since the last PDMS batch has a thickness of a little over 2mm, the 3mm sheet was not used, as there would be a space of 1mm inside the air chamber of the device where some of the liquid could get trapped. The overall design of the device was not changed. Only the bottom layer was redesigned and placed circular holes instead of square holes to accommodate the PDMS cylinders cut by the skin biopsy cutters (width of cutter chosen was of 4mm). The range of diameters mentioned on Monday did not work, as I didn't take into account the material removal by the laser cutter. The smallest hole (d=3.8mm) was scaled down with a factor of 0.8 (d=3.04mm), which was the ideal size to place the PDMS cylinders for them to be held in place but also not too difficult to place. *Smaller sizes could lead to a more difficult placement and removal of the sample, potentially damaging the modified surface*.

Upon filling the device and rotating, one of the channels presented leakage due to fabrication issues. The other channel was able to get the water a few mm beyond the PDMS piece. The rotation speed was maintained for a few seconds, until it began to present leakage as well, but this time it was leaking from the hole in which the PDMS piece was.
Another issue arose when trying to remove the PDMS piece to change it for another one. The thickness of both the PMMA sheet and the PDMS are approximately the same, so tweezers were used to retrieve the piece. Pulling only from the bottom surface didn't suffice, as the PDMS is not rigid enough and it was cut by the tweezers. Instead, they were inserted into the air chamber from the sides of the hole, but with the pressure that had to be used, the top surface got deformed. This deformation could potentially damage a modified surface.

*Regardless of the method used to hold the PDMS piece in place, enought pressure for enough time can lead to leakage from the intersections.
Attempting another PDMS batch and pouring PDMS onto the holes to polymerize in the desired shape is recommended*.

![[WhatsApp Image 2024-08-20 at 08.56.00.jpeg]]
![[WhatsApp Image 2024-08-20 at 11.56.07.jpeg]]
![[WhatsApp Image 2024-08-20 at 12.04.24.jpeg]]
![[WhatsApp Image 2024-08-20 at 12.05.10.jpeg]]

### Recap of other attempts

The first idea was to directly paste a PDMS piece to an exposed portion of the PSA glue. However, a small piece would have a small area to attach to. Hence, the PDMS piece fell off easily, and pressure in the air chamber could cause leakages, weakening the attachment of the PDMS piece.
![[WhatsApp Image 2024-08-20 at 08.42.08.jpeg]]

Another idea was to use some sort of clamp to keep the PDMS in place. At first, a 3D printed clamp was used, but its design and weight made it very sensitive to rotational speeds and ended up falling off of the device. An alternative was to simply use a paper clip clamp ([[WhatsApp Image 2024-08-20 at 08.45.57.jpeg]]), but due to the geometry of it, the pressure distribution was uneven along the width of the channel. Despite the PDMS being held in place, one side of the PDMS was held with more force than the other. Because of this and the pressure in the air chamber, a leakage would occur.
![[WhatsApp Image 2024-08-20 at 08.45.57.jpeg]]

Then, as the different layers of the device were being held together by the Pressure Sensitive Adhesive and were difficult to separate, a piece of the PSA tape was used to keep the PDMS piecce in place. While it was possible to get to a rotational speed in which the water-air interface was beyond the PDMS piece, the pressure could not be maintained for more than some seconds (no more than, say, 15 seconds) without leakage. This would also happen if the speed was quickly decreased, but increased again. The reciprocation process could not be performed more than 4 times, with the maximum speed being held by just 5 seconds, before a leakage occured.
![[WhatsApp Image 2024-08-20 at 08.43.59.jpeg]]

Lastly, the cylinder PDMS pieces in the cylinder PMMA holes, as described earlier, also lead to leakages.