# Imagine Fun Resource Pack Fix

![image](https://lingtalfi.com/services/pngtext?color=cc0000&size=25&text=Please%20let%20me%20know%20if%20any%20issues%20are%20found%20so%20they%20can%20be%20fixed%20ASAP)

#### Note: While originally I based the 1.14+ versions on IF's 1.16 pack which seemed pretty good, I felt it would be better (and possibly more "full-proof") if I went and used the more trusted 1.12 version as the basis for all conversions. Any references to using the 1.16 pack as a basis are outdated as they all use 1.12 as a basis now. I've tried to update all references to the old process, but I figured I'd leave this here as clarification anyways.

#### It's widely known by anyone that plays on Imagine Fun that the best way to experience the server is on 1.12. This is in part due to the fact that the resource packs on higher versions aren't as complete as the one on the original version. I've sought to try and bring the resource pack for the other versions since then up to speed with 1.12.

## Table of Contents
- [What's new?](#whats-new)
  - [1.14+ Changes](#114)
  - [1.13 Changes](#113)
- [Known Issues](#issues)
- [Credits/Disclaimers](#credit)
- [Version History](#version)
## <a name="whats-new"></a>What's new?

#### A lot. Like, a lot a lot.

### <a name="114"></a>1.14+ Changes

#### ~~The current 1.16 version of the pack served as a great start for getting a pack working across these versions.~~ All versions of the pack including 1.14+ ones are now based on the official 1.12 version. However, worth noting is that the 1.14-1.16 versions of the pack are extremely similar and can be used interchangeably (assuming you ignore the version incompatibility warning). The majority of the issues that needed fixing here were some missing textures where animated textures should be (*cough cough radiator springs racers*). This was largely caused by an extra comma added to the end of the mcmeta file describing these textures' animations.
- #### Mack's eyes
  - Before ![image](https://user-images.githubusercontent.com/84101121/118085177-f0686200-b38f-11eb-9651-508a3b8b938a.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118085193-f8280680-b38f-11eb-8560-0515274abb64.png)
- #### Van's eyes
  - Before ![image](https://user-images.githubusercontent.com/84101121/118085284-286fa500-b390-11eb-95ce-ea12ec688c51.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118085306-31f90d00-b390-11eb-824a-0347aa5c22fd.png)
- #### Sheriff's eyes
  - Before ![image](https://user-images.githubusercontent.com/84101121/118085397-5b199d80-b390-11eb-9eb6-3f13766ab62e.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118085427-64a30580-b390-11eb-9325-e9601453c1bc.png)
- #### Sarge's eyes
  - Before ![image](https://user-images.githubusercontent.com/84101121/118085501-7f757a00-b390-11eb-98bd-0cb91d3440ca.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118085515-869c8800-b390-11eb-8eb2-a79c8096387c.png)
- #### Lizzie's eyes
  - Before ![image](https://user-images.githubusercontent.com/84101121/118085642-bb104400-b390-11eb-9350-99af54213098.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118085694-cbc0ba00-b390-11eb-9633-cae1229d83df.png)
- #### Doc's eyes
  - Before ![image](https://user-images.githubusercontent.com/84101121/118085797-fdd21c00-b390-11eb-9476-2f58b79a71db.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118085860-13474600-b391-11eb-8574-a4772f6031e7.png)
- #### Luigi and Guido's eyes
  - Before ![image](https://user-images.githubusercontent.com/84101121/118087379-7a65fa00-b393-11eb-9274-b3c76d057d62.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118087405-83ef6200-b393-11eb-8bcc-80f81b81c70c.png)
- #### Tinker Bell's lantern in Fantasyland
  - Before ![image](https://user-images.githubusercontent.com/84101121/118083428-e5f89900-b38c-11eb-9ac6-0efb9bf210fd.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118083617-3e2f9b00-b38d-11eb-81bc-fecc50eaae3d.png)
![image](https://user-images.githubusercontent.com/84101121/118083601-37088d00-b38d-11eb-8577-54254c1625da.png)
- #### Red and yellow flowers in Alice in Wonderland
  - Before ![image](https://user-images.githubusercontent.com/84101121/118089101-ff521300-b395-11eb-812d-9eb6c66fd0e8.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118089131-06792100-b396-11eb-86d4-daf8a9df53c3.png)
- #### Cheshire Cat's eyes
  - Before ![image](https://user-images.githubusercontent.com/84101121/118089204-1ee93b80-b396-11eb-81ae-585fe4806bb7.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118089242-24df1c80-b396-11eb-8301-e0df517509b6.png)

#### The other main issue that needed to be corrected was that paintings were in the 1.13- format rather than the 1.14+ one.
- #### Castle Bros
  - Before ![image](https://user-images.githubusercontent.com/84101121/118090589-c024c180-b397-11eb-9a61-a5532ed6849e.png)
  - After![image](https://user-images.githubusercontent.com/84101121/118090557-b438ff80-b397-11eb-87a7-51d9d8d21b94.png)

### <a name="113"></a>1.13 Changes

#### Unfortunately, 1.13 was a bigger mess than the other versions. By default, it seems that, much like 1.14, the server applies the 1.12 pack to 1.13. However, since 1.13 had many block changes, lots of models exist with broken textures. Additionally, simply applying the same pack for 1.14+ still left some models untextured due to (I believe) some name changes in the different blocks used for textures. It would have been a huge pain to try and track down every model that used these and I couldn't find the specific blocks used, so I instead decided to port the 1.12 version forward and this was already a lot better.
- #### Mainstreet
  - Before ![image](https://user-images.githubusercontent.com/84101121/118092692-6d98d480-b39a-11eb-8249-84339a29d42d.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118092710-725d8880-b39a-11eb-947a-e8b4c13a4f60.png)
- #### Partner Statue
  - Before ![image](https://user-images.githubusercontent.com/84101121/118092948-bea8c880-b39a-11eb-95ab-78c832e3ebd9.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118092961-c2d4e600-b39a-11eb-87d1-52dc3f3afad1.png)

#### After this, there were still some messy textures, but I was easily able to track down snow as the culprit. The conversion has snow changing to snow_block in 1.13, but this broke all the snow textures, ~~so I just inserted the texture so the game was happy. The alternative of this was finding each texture that uses snow and changing the line, but I figured this was easier.~~

#### Edit 5/14/21: I went back and realized it would be best to not include a Minecraft texture - so now every model which uses snow_block instead uses snow so they appear correctly.
- #### Cars Land (Lights)
  - Before ![image](https://user-images.githubusercontent.com/84101121/118094492-cec1a780-b39c-11eb-81db-4fcc6ddc30d2.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118094505-d3865b80-b39c-11eb-8120-e38c774609d4.png)
- #### Mr. Toad's Wild Ride (Lanterns)
  - Before ![image](https://user-images.githubusercontent.com/84101121/118094678-0a5c7180-b39d-11eb-83fb-3fe5133c5e6f.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118094696-10525280-b39d-11eb-8c6a-58bbe939a6de.png)

#### ~~The final touches on this version were just swapping some of the item models (specifically, diamond pickaxe, shovel, and sword) for the 1.16 ones rather than the converted 1.12 ones.~~ Since all versions of the pack were made without the use of the 1.16 version, I went into the files to find the issues here. Each item model seemed to have its own issue ranging from referenced models having capitalized letters to the converter refusing to convert a couple model names. Remedying these errors fixed the remainder of the models that would simply not show up at all.
- #### May the 4th signage (while this signage is no longer present, the same principle applies for the current signage in its place)
  - Before ![image](https://user-images.githubusercontent.com/84101121/118095639-52c85f00-b39e-11eb-9bd4-3de541cacb0f.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118095672-59ef6d00-b39e-11eb-9f97-23dcab03754d.png)
- #### Loungefly Backpacks
  - Before ![image](https://user-images.githubusercontent.com/84101121/118096202-0af60780-b39f-11eb-9481-4e3e4f4923de.png)
  - After ![image](https://user-images.githubusercontent.com/84101121/118096217-0e898e80-b39f-11eb-8d9a-a7a6687e86e2.png)

## <a name="issues"></a>Known Issues

- #### Due to the way Minecraft handles rendering entities through transparent entities on 1.13-1.14, Tink doesn't show up in her lantern outside Peter Pan when it becomes translucent. The one closer to Fantasyland's entrance seems unaffected by this.
  - 1.12, 1.15-1.16 ![image](https://user-images.githubusercontent.com/84101121/118096527-78099d00-b39f-11eb-94c2-234f55472b67.png)
  - 1.13-1.14 ![image](https://user-images.githubusercontent.com/84101121/118096510-70e28f00-b39f-11eb-8436-2d5bee2e726e.png)
- #### Due to the way Minecraft handles rendering transparent paintings in 1.15+, some paintings that were previously invisible now appear black.
  - 1.14- ![image](https://user-images.githubusercontent.com/84101121/118100844-ec930a80-b3a4-11eb-920d-3385a18fab40.png)
  - 1.15+ ![image](https://user-images.githubusercontent.com/84101121/118100872-f61c7280-b3a4-11eb-8610-d0fa2633e045.png)

## <a name="credit"></a>Credits/Disclaimers

I did not create any of the original textures or models - those were created by the staff at [Imagine Fun](https://imaginefun.net/).

The main lot of conversion from 1.12 over to 1.13 was done through a [resource pack converter](https://github.com/agentdid127/ResourcePackConverter) made by [@agentdid127](https://github.com/agentdid127).

While I discovered this myself before seeing it, user @Kumki Sakura🌸#9388 (on discord) found the issue with certain animated textures not working on versions higher than 1.12.2. I figured it wouldn't be right if I didn't credit them also.
![image](https://user-images.githubusercontent.com/84101121/118082611-7b932900-b38b-11eb-991d-e59b156481d6.png)


## <a name="version"></a>Version History

* 1.0.0
    * Initial Release - Updated Pack as of 5/13/21.
* 1.0.1
    * Snow Update - Fixed models using snow in 1.13 by modifying model files rather than adding a snow texture.
* 1.1.0
    * Enchanting Update - Updated Pack as of 5/18/21 (and maybe fixed a few more 1.13 snow-using models I missed before).
* 1.2.0
    * Pride Update - Updated Pack as of 6/1/21 and based all ports on 1.12 rather than 1.16.
