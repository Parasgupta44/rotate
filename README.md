
# rotate
Create recursive image transformation animations 

-----------------------

## Usage Instructions

- Set up your python environment and run the following command in your terminal:
  - `pip install -r requirements.txt`
- An animation can be generated using the `rotate.py` or `transform.py` file.

--------------------

### How to use rotate&#46;py

#### Arguments:

`python3.7 rotate.py <input_image.png> <output_file.mp4>`

-------------

### How to use transform&#46;py

#### Arguments:

`python3.7 transform.py <input_image.png> <output_file.mp4> optional: <transform_type>`

#### Transform Types:

`0: rotation, 1: vertical flip, 2: horizontal flip, 3: vertical + horizontal flip`

----------------

### For both these files:

Valid output formats include .m4a,  .mp4,  .mov,  .avi

The image needs to have N x N dimensions where N is a power of 2. If these requirements are not met, the program can automatically resize the image to the closest power of 2.

--------------

### Examples

![demo_gif](./demo.gif)

--------------
