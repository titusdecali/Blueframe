#Blueframe

Blueframe is an ultra light-weight frontend SCSS framework that provides a simple base to build your own custom framework from. It consists of css resets and short, easy to understand utility classes. Class names have been adopted from the best css frameworks including Skeleton and Boostrap, while adding a few new ones for convenience or faster typing.

After modifying the `/base/variables` file and adding your custom colors and responsive break points to match styleguide, you can then add any new custom classes to the `/modules/project.scss` file. This let's you continue to build your own custom framework for use across projects, while maintaining project-specific classes to a single file.


Check the `/base/.utils.scss` file to see how you can quickly add utility classes to your HTML quickly.

**Base Utility Classes**
Padding can be added as follows:
pr-1 = padding-right: $p1 (set padding distances for 1,2,3 variables in the same file)
ml-1 = padding-left: $p1
px-1 = padding for horizontal right/left: $p1
py-1 = padding for vertical top/bottom: $p1
pt-1 = padding-top: $p1
pb-1 = padding-bottom: $p1

Margin setting work the same way:
mr-1
ml-1
mx-1
my-1
mt-1
mb-1

*EX:*
<div class="mx-1"></div>

**Positioning Classes:**
*p-abs* = position: absolute;
*p-rel* = position: relative;

**Display Classes:**

d-block = display: block;
d-inline = display: inline;
.d-inline-block = display: inline-block;

**Overflow Classes:**
*o-h* = overflow: hidden;
*ox-h* = overflow-x: hidden;
*oy-h* = overflow-y: hidden;


**View Width/Height, Float Classes:**
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

**Centering**
Vertical Centering
.vc {
  display: inline-block;
  vertical-align: middle;
}

**Text Alignment*
.tc {
	text-align: center;
}

.tr {
text-align: right;
}

.tl {
  text-align: left;
}

**Text Decoration*
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

**Font Weights* 
_Adjust variabels as needed_
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

