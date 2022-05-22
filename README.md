To generate blend: 

podman run -v /home/srishankar/Documents/synethetizer/Outputs:/out -it ffedoroff/neural-style th neural_style.lua -gpu -1 -style_image Grid_artistic.png -content_image 23118.png

