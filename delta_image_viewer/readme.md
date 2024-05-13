# Image loader
![DIV_thumbnail](https://github.com/deltamolfar/PublicE2/assets/72973198/5090c385-81db-4599-aa55-507fc5f2b79f)

## To use:
0) Save ![the E2](https://github.com/deltamolfar/PublicE2/blob/main/delta_image_viewer/loader%2Bdrawer)
1) Visit https://deltamolfar.github.io/PublicE2/ and convert image you want to use in gmod.
2) After pressing 'convert' button, you will download a .txt file.
3) Place this file in your E2 folder.
    General path is:
    "C:\Program Files (x86)\Steam\steamapps\common\GarrysMod\garrysmod\data\expression2\"
    ( You can place it in whatever expression2 folder you want, as long as you change it in the #include )
    ( I recommend delta_image_viewer\converted_images for keeping it tidy :) )
4) Alter the include to load your image.
    Example: Image "cat_x128" that is inside delta_image_viewer\converted_images
    Result: " #include "delta_image_viewer/converted_images/cat_x128" " ( without .txt in the end )
5) Configure other options accordingly to your preferences.
6) Either just spawn this E2 on the ready digital screen, or somewhere else and link SCREEN input of this E2 to the digital screen wirelink output.
7) Wait for image to load into E2, and then to render. (It's okay, if it takes long time)
8) Flex to your friends with bad quality memes, or cats.

>[!WARNING]
>Using ArrayModeN > 4, or using high perf (>20) will cause server-side lag!
>
>**Be careful!**

### PS
- The loading time heavily depends on server limits, and your configuration. But you should not have any problems with images up to 256x256.

- Cat images that I've used in the thumbnail are present in ![here](https://github.com/deltamolfar/PublicE2/tree/main/delta_image_viewer/converted_images).
