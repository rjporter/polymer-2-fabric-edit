<!DOCTYPE html>
<html lang="en" class=" is-copy-enabled is-u2f-enabled">
<head prefix="demo: http://thinkerworks.com/demo/polymer-2-fabric-edit#">
<meta charset='utf-8'>

<title>polymer-fabric-2-edit/readme.md at master · rporter/polmer-fabric-edit</title>

# Polymer 2 Fabric Edit

## copyright: &copy; 2016 Thinker Works

## author: Ralph Porter


Usage
```
<polymer-2-fabric-edit></polymer-2-fabric-edit>

<polymer-2-fabric-edit canvas-width="300" canvas-height="300" canvas-border-color="blue"></polymer-2-fabric-edit>
```

- TEXT
  use to input text
    bold, italic, underline, line-through, overline
    Font Family, Text Align, Stroke Color, Background Color,
    Text Background Color, Font Size, Stroke Width, Line Height, Char Spacing
    Shadow Color, Blur, OffsetX, Offset Y
    Text
- SHAPE
  add shapes
    Square, Rectangle, Diamond, Circle, Ellipse, Triangle, Horizontal Line,
    Verticle Line, Diagnal Line, Angled Line, Star, Polygon, Polyline, hexagon
    Arrow, Line Arrow, Anchor
  adjust
    Fill COlor, Stroke Color, Stroke Width, Angle, Dash Stroke Array
    Shadow Color, Blue, OffsetX, OffsetY
- FILE
    Add object to canvas (image, svg, json)
    Load Canvas Background
    Load Canvas From File
    Download Canvas as JSON, JPEG, PNG, SVG
- DRAW
  Freehand Draw
    Pencil, Pen, Marker, Cryon, Sprayer, Spray, Fine Spray, Medium Spray,
    Dense Spray, Circle, Pattern, hline, vline, square, Diamond, Texture
      Honey Im Subtle, Bedg Grunge, Bkg, Blob, Excheresque, Floral, Ladybug,
      Nasty Fabric, Retina Wood, Skin, Night Sky, Sun, Custom
        If Custom Load texture from Image File
    adjust
      Color, Line Width
      Shadow Color, Blue, OffsetX, Offsety
- CONTROL
    adjust
      selected object parameters  (parameter vary based on selected object type)
      Bold, Ialic, Underline, line-through, overline, Font Family, Font Size,
      Text Align, Text, Lint Height, Char Spacing, Fill Color, Stroke Color,
      Background Color, Stroke Width, Angle, Stroke Dash Array,
      Shadow Color, Blur, OffsetX, OffsetY
      Top, Left, Width, Height, ScaleX, ScaleY, FlipX, FlipY, Stroke Line Cap,
      StrokeLine Join, Stroke Mitor Limit, Opacity, Fill Rule,
      Global Composite Operation, ClipTo, SkewX, SkeyY,

      Remove selected object or group
      Group selected objects
      Ungroup selected group

      Send Backwords Send to Back, Bring Forward, Brint to Fromt

      locks
        Horizontal Movement, Veticle Movement, Horizontal Scaling,
        Verticle Scaling, Horizontal Skewing, Verticle Skewing, Rotation,
        Flip, Uni Scaling

Demo    -   Google Chrome Browser recommended

[Demo] (http://thinkerworks.com/demo/polymer-2-fabric-edit)

Installation

bower install polymer-2-edit

Dependicies
  Polymer 2.0   Polymer/polymer#2.0  [LICENCE] (https://github.com/Polymer/polymer/blob/master/LICENSE.txt)
  fabric.js             fabric#^1.6.6                [LICENCE] (https://github.com/kangax/fabric.js/blob/master/LICENSE)


  fabric-brush          *                            [LICENCE] (https://github.com/tennisonchan/fabric-brush/blob/master/LICENSE)

  fabric-brush has been modified for use in this element
  1. renamed spray-brush to sprayer-brush to allow fabrics.js spary-brush to be used.
  2. commented out drip code.

License

Copyright (c) 2016, 2017 Thinker Works (Ralph Porter)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
