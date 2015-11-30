shaderWolf
==========

This is a now updated sample of animation and physics done in WebGL. I tried resisting WebGL for as long as I could but it seems to be more accessible than waiting for compiled JS frameworks to appear. I adapted the Android example I have been working through into this but I am calculating bounds using px instead of verts. Probably will switch back to verts after more work on the Android side. CSS animation has also been adapted into a shader now just to see how it works- seems to work well. Here was my inspiration: http://blog.teamtreehouse.com/css-sprite-sheet-animations-steps 

You will need a webserver to run this due to local asset restrictions in WebGL which at least on the Mac is:

Step 1: cd into directory
Step 2: python -m SimpleHTTPServer 8080

On your PC install python and do the same or learn IIS.
