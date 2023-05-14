
![90s anime render](https://user-images.githubusercontent.com/11538692/150200923-21247c45-d784-4f1a-a8be-808abe05c1fc.jpg)

I got really into emulating 90s anime style using blender. I actually managed to put together a pretty good pipeline that gives results pretty close to what I wanted.  There is a very precise shift in hue and value for shadows, utilizing the trick of shifting the hue toward blue in shadows. The exact shift was calculated from sampling anime stills. I followed a tutorial by tripplejaz about making 90s looking images in clip studio paint. I just translated the steps into blender.
While making the render I also learned a lot of new tricks for making the environment (Ghibli grass, anime starry night tutorial for clouds, using metaball on sapling for the bushes, adding bird flocks).
In the end the materials are actually really simple, with the anime shadows being just one simple  group. All the magic is in compositing. 


![90s anime render (sanitized assets)](https://user-images.githubusercontent.com/11538692/150199895-86316962-b845-4aad-a0c0-ba34cee8c966.jpg)

Here is a sanitized version of my 90s anime render setup. I removed the assets that were not meant for redistribution, but all the meat of the setup is untouched: the compositing and materials. Also included the grass, trees, birds and skydome.

All of the magic is in the groups, so make sure to look what's inside them. I added comments for easier navigation.

Feel free to use the stuff I made, but do drop me a credit if you do so.

Credits for tutorials:

* tripplejaz - clip studio paint tutorial for getting retro anime look, this one was crucial for setting up the compositing https://www.youtube.com/watch?v=3uG2TzYMbRc
* veryveig - 90's Anime in Blender, great study on makes it tick https://www.youtube.com/watch?v=ZsvZsVPhTVs
* DnBsyn - his comment on veryveig video about lineart color bleed was the cherry on top https://www.youtube.com/watch?v=ZsvZsVPhTVs&lc=UgzSRQZoGB54Ya6lBCl4AaABAg
* PhillWorks - Amazing study on colors used by the biggest names in anime industry https://twitter.com/phillworks/status/1265715231688278016?s=20
* Louis du Mont - bird flock https://www.youtube.com/watch?v=kQque9hD1Cg
* The Daily Show with CG - flag simulation https://www.youtube.com/watch?v=kihtLrCXCtQ
* Kristof Dedene - grass and skybox https://www.youtube.com/watch?v=m4aOZm6auxQ , https://www.youtube.com/watch?v=6hyztL8btlY
* LanceBeryl․Dev - also grass https://www.youtube.com/watch?v=zjKKZL03HNs
* Lightning Boy Studio - the base setup for the trees https://www.youtube.com/watch?v=DEgzuMmJtu8
