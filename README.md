# Blueframe - SCSS Front-end Framework

   Blueframe is an ultra light-weight frontend SCSS framework brought to you by Blueprint.vc. Blueframe is great for building smaller projects, or as a base to begin creating your own custom framework from. It consists of css resets and short, easy to understand utility classes. Class names have been adopted from the best css frameworks including Skeleton and Boostrap (minus the weight), while adding a few new ones for convenience or faster typing. It does not require any addition dependancies or script imports.

   After modifying the `/base/variables` file and adding your custom colors and responsive break points to match your project's styleguide, you can then add any new custom classes to the `/modules/project.scss` file. This let's you continue to build your own custom framework for use across projects, while maintaining project-specific classes to a single file.




Check the `/base/.utils.scss` file to see how you can quickly add utility classes to your HTML quickly.

**Base Utility Classes**

Padding can be added as follows:
```
// Set padding ($p1, $p2, $p3, etc) and margin spacing ($m1, $m2, $m3, etc) in the same _utils.scss file
// 

pr-1 = padding-right: $p1
ml-1 = padding-left: $p1
px-1 = padding for horizontal right/left: $p1
py-1 = padding for vertical top/bottom: $p1
pt-1 = padding-top: $p1
pb-1 = padding-bottom: $p1
```

Setting margins works the same way:
```
mr-1
ml-1
mx-1
my-1
mt-1
mb-1
```

**EX:**
```
<div class="mx-1"></div>
```

**Positioning Classes:**
```
p-abs = position: absolute;
p-rel = position: relative;
```

**Display Classes:**
```
d-block = display: block;
d-inline = display: inline;
d-inline-block = display: inline-block;
```

**Overflow Classes:**
```
o-h = overflow: hidden;
ox-h = overflow-x: hidden;
oy-h = overflow-y: hidden;
```

**View Width/Height, Float Classes:**
```
.w-100 {
  width: 100%;
  box-sizing: border-box;
}

.h-100 {
  height: 100%;
  box-sizing: border-box;
}

.float-right {
  float: right;
}

.float-left {
  float: left;
}
```
**Centering**
```
// Vertical Centering
.vc {
  display: inline-block;
  vertical-align: middle;
}
```
**Text Alignment**
```
.tc {
  text-align: center;
}

.tr {
  text-align: right;
}

.tl {
  text-align: left;
}
```
**Text Decoration**
```
.td-none {
  text-decoration: none;
}

.underlined {
  text-decoration: underline;
}

.caps {
  text-transform: uppercase;
}

.italic {
  font-style: italic;
}
```

**Font Weights**
```
// Adjust variables as needed
.normal {
  font-weight: $normal;
}

.light {
  font-weight: $light;
}

.semibold {
  font-weight: 600;
}

.bold {
  font-weight: $bold;
}
```
**Included Images**

Blueframe also includes a favicon and device-based images that can easily be modified to fit your project without searching for all the various image sizes you need to fit each device.

Enjoy, and good luck!



## **Copyright 2018 Blueprint Ventures Ltd.**

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
