---
{"dg-publish":true,"permalink":"/projects/studio-le-mon/block-bench/block-bench/"}
---


## Info

>[!multi-column]
>>As it's very core, BlockBench is a ==Pixel Art / Low Poly / 3D Modeling== Software. It's the most versatile software for creating Minecraft assets.
>
>>**Works in**
>>- Mobile / Tablet
>>- Pc
>>

#### Tutorials
- [[Projects/Studio Le Mon/BlockBench/ArtByKev's - BlockBench for Begginers - [Index]\|ArtByKev's - BlockBench for Begginers - [Index]]]


## New project

When first opening the program, we have different project types: 

> [!column|list] Project types
> - [[Projects/Studio Le Mon/BlockBench/Generic Model\|Generic Model]]
> - [[Java Block/Item\|Java Block/Item]]
> - [[Bedrock Entity\|Bedrock Entity]]
> - [[Bedrock Block\|Bedrock Block]]
> 
> - [[Modded Entity\|Modded Entity]]
> - [[Optifine Entity\|Optifine Entity]]
> - [[Minecraft Skin\|Minecraft Skin]]

## [[Projects/Studio Le Mon/BlockBench/Commands\|Commands]]


## Moving in Viewport


> [!multi-column]
> ![Pasted image 20260212180012.png](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212180012.png)
> 
>![Pasted image 20260212180248.png](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212180248.png)

> [!multi-column]
> ![Pasted image 20260212180529.png](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212180529.png)
> 
> ![Pasted image 20260212175751.png](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212175751.png)
> 

More camera angles:

![Pasted image 20260212180634.png|wmedium](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212180634.png)

To return to initial angle: 

![Pasted image 20260212180830.png|wmedium](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212180830.png)
*(This could also be done by pressing "1" in your Numpad keyboard)*

## Right-Side Panel

---
![Pasted image 20260212181032.png|left wsmall](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212181032.png)**OUTLINER** = Where we find the list of all our cubes, bones, and meshes that we have ==active== in this project.



---
> [!multi-column]
>> To add new elements:
>> 
>> ![Pasted image 20260212181116.png](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212181116.png)
>
>>To hid the grid on the cube:
>>
>>![Pasted image 20260212181503.png](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212181503.png)
> 


>[!quote|ArtsByKev] ArtsByKec
>"Modeling is all about creating a pile of cubes that looks like something when we are done." 
>


## Tools Panel


>[!multi-column]
>>[[Projects/Studio Le Mon/BlockBench/Move\|Move]] 
>>![Pasted image 20260212184614.png](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212184614.png)
>
>>[[Projects/Studio Le Mon/BlockBench/Resize\|Resize]]
>>![Pasted image 20260212184701.png](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212184701.png)
>


>[!multi-column]
>>[[Projects/Studio Le Mon/BlockBench/Rotate\|Rotate]]
>>![Pasted image 20260212185516.png](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212185516.png)
>
>>[[Projects/Studio Le Mon/BlockBench/Pivot\|Pivot]]
>>![Pasted image 20260212185802.png](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212185802.png)
>>

> [[Projects/Studio Le Mon/BlockBench/Vertex Snap\|Vertex Snap]]
> ![vertex snap_1.gif](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/vertex%20snap_1.gif)
> 


---

## Transform Space

![Pasted image 20260212190214.png|wmedium](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212190214.png)

###### Global

![rotacion_global.gif](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/rotacion_global.gif)
When you move the cube, you also move the pivot.  When you rotate, you rotate axis in this 3D space and not around the cube axis.

###### Local

![Rotacion_local.gif](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Rotacion_local.gif)
You only move the cube, but not the pivot. When you rotate a cube you rotate around its own axis.

###### Parent 
(Bone?)


---
## Tips

- ArtsByKev heavily recommends to spend some time testing and getting used to moving the pivot, moving and rotating in the different spaces of local and global. 
	- *In 2020' the space was set to global by default. Nowadays however it is set to local, so keep that in mind.*
- Another recommendation is to ==keep a track on where the pivot is located.== Always double check your pivots and all of your cubes as you're moving them around and also that you at regular intervals double check whether you are working in a global or local space.
- Be aware that ==local space can be applied to **rotation** while you're working in the global space on **movement**== and vice versa. 
- Mastering these tools with not only speed up your modeling process, it will also make complex modeling a breeze down the lane


#### Duplicate a cube

![Pasted image 20260212193606.png|wmedium](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212193606.png)

We can rename to differenciate them, or we could also change their color:

![Pasted image 20260212193838.png|wmedium](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212193838.png)



#### C-Fighting

![c-fighting.gif|left](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/c-fighting.gif)It happens because these two cubes are equally thick, and in blockbench (or any other game this asset would be put into) it simply does not know which of these two cubes to render first in this area, where they both exist at the same time. 



To solve this issue, we can add the **inflate tool**, and that is done by going up to the customization of the toolbar:

![Pasted image 20260212195604.png|wmedium](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212195604.png)
![Pasted image 20260212195751.png|wmedium](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/Pasted%20image%2020260212195751.png)

We type it and we add it by clicking "Inflate".
Then, on the green cube, we put "-0.001" in the "Inflation" tab above. This makes it a bit tinnier than the pink one, solving the C-fighting issue:

![c-fighting_inflation.gif](/img/user/Projects/Studio%20Le%20Mon/BlockBench/IMG/c-fighting_inflation.gif)

This is a simple and fast way, and doesn't damage our *textures.*


---






 