# etch-a-sketch


For the final project for my Digital Electronics class, my partner and I  created a **digital Etch-A-Sketch**. When the system turns on, a cursor appears at the center of the screen. Our system then receives directional input from two LEFT-RIGHT and UP-DOWN knobs (rotary encoders) and a color input from two switches on the FPGA board, and then outputs an 8x8 pixel on the screen. The speed at which each 8x8 pixel displays on the screen is “8 knob turns,” which can be altered in the pixel-incrementer. Once the cursor reaches the end of the screen (in either the horizontal or vertical directions) the cursor will wrap around smoothly.
