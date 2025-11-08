HLTP -- Half-Life texture processor

This tool converts pictures into game-ready textures for Half-Life games and is designed to work with WadMaker

How to use: 

1.Place all the pictures you want to convert into a folder
2. Drag and drop the folder with all the pictures onto the HLTP exe
3. When the program is finished converting textures a folder called "curated" will be created inside the same folder you dragged onto hltp.exe, you may now rename this folder and drag it into WadMaker

Configuration:
Run the hltp.exe by itself to configure the program

-Transparent textures:
Enabled by default.
when enabled any texture with transparency will have any transparent pixels converted to Blue(0, 0, 255) for half life, transparent textures will have a "{" at the start of their name so the engine knows to render these textures with transparency.
When disabled any transparent textures will be fully opaque and any transparency will be replaced with your chosen transparent color black(0, 0, 0,) by default (Note:"Transparent color is only used when Transparent textures is disabled)

-Max texture size:
512 by default.
All half life textures must be divisible by 16 and under 512 pixels height/width. when converting image sizes are rounded to the nearest 16th and downsized to be under 512

Supported image formats: PNG, JPG, JPEG, TIFF, WEBP, BMP.
the program generates a log (log.txt) inside the "curated" folder

MIT License

Copyright (c) 2025 Copperware99
Copyright (c) 2025 Chillpill649

Permission is hereby granted, free of charge, to any person obtaining a copy...

