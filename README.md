# 🐢Turtlepix🐢

Replicate any image, pixel by pixel, using Turtle and Python.

![github_ex](https://user-images.githubusercontent.com/34638987/60859526-e8ee3580-a1c7-11e9-98b6-84719b589a0c.png)


## How It Works

1. After the image file is given, the image is loaded using Pillow and converted to a .jpeg. Then, the pixel map is created.
2. Next, the turtle enviroment is created along with the first turtle.
3. Then, the first square is created and filled with the corresponding pixel RGB value.
4. This process of creating a small square and filling it with the color fo the corresponding image is repeated for the rest of the image.

## Dependencies

    pip3 install pillow && sudo apt install python3-tk

## Licensing

This project is licensed under MIT license - see the [LICENSE.md](https://github.com/alexalbertt/turtlepix/blob/master/LICENSE) file for details
