---
title: "Autocad-3 : Plotting precise boundary line using survey coordinates."
date: 2018-01-03T11:02:17+08:00
subtitle: "Plotting boundary line"
author: "michtintin"
draft: false
tags: ["Dwg: Plotting boundary line"]
categories: ["Autocad"]

---

# Plotting precise boundary line using survey coordinates.

{{< youtube LcatOR3rd2Y>}}

## Introduction.
### 00:00-00:05

"Hello Everyone, today I'll be demonstrating to you the first steps to a good landscape plan."
## Minimalist workspace.
### 00:06-00:25

No.1 is Minimalist workspace. Try to keep your workspace as clear as possible,
with only your layers tab and your properties tab, docked to the right hand side of your screen.

## Attaching scanned layout plan.
### 00:26-01:08
When you attach a file, make sure that you've reduced the size to as minimal as possible, so that it doesn't slow down the whole drawing.

After that, click ok, and make sure the unit sign is millimetres, you're attaching to the origin point and then click OK. Ignore the scale and just click enter. I will show you how I scale the drawing using coordinates.

Sometimes it's possible that you're given a very very old survey plan.

And it doesn't have any CAD files just a printed copy of A4 Size with coordinates and measurements, without a North sign and with the coordinates method you can find out the North signs, the measurements and the orientation of the drawing.


## Adjust the visibilities of the scanned plan.
### 01:09-01:40
Before that we will fade out the drawing select a drawing and then right-click and properties, customise properties and then click on fade and increase the fade-out percentage. Make sure the drawing is selected. You will have problem fading out if you don't select it. So then, increase the fade up to 50%.

## Adjust the points settings and place the points.
### 01:41-02:00

Then we will plot out all the coordinates on the plan using PO, point command.
Just click on any way you want to put this point or you can key in your coordinates you want this point to be. Click on set size in absolute units.

It's easier to adjust that way. And for the point size set it to 0.1 and above.

You can adjust the size to your preference. Just click on the preferred point and click OK. You will see that the point has changed. Remove it and then we will use coordinates to input the position of the point.


## Start placing the survey points using the given coordinates.
### 02:00-03:00  
Change the active layer to boundary line layer so PO, Enter. You need to have a dynamic input turned on for this exercise. Key in the coordinates x and y.
We key in the coordinates X as a positive number and Y as negative.
seven eight zero eight zero one three four without a decimal point because the coordinates are all in meters and our drawing is in millimetres.
So once you get in press ENTER and the point will be positioned at the exact coordinates that we have keyed in just now.

Now we'll go back to the drawing and continue to plot all the different
coordinates on the boundary line.

## Start with the boundary line and north signs, important information etc..
### 03:00-03:40  

Whenever you start a new project remember to start on the boundary line the position of the boundary line. The Northing signs, The important information of the drawing before you put in the design

If you're wrong on a position of the boundary line it will affect the distance of the perimeter

boundary planting because in

some countries they require you to have a minimum

distance of greenery along the boundary line before any

structure can be

erected

so boundary line first.

## Use a thin line, even this has caused some issues in the past.
### 03:40-0:00  

Another point I want tohighlight is when you draw the boundary line using coordinates or any boundary line

use a thin line of

0.1mm or

0.05mm.

So that the thickness of the

Boundary line is not included within the area of the site.

What happened one time was after we finished planting the greenery buffer along the perimeter we(my team and I) were told by the authority that some of the trees were not within the green buffer, and we had to

remove the trees and replant them again. I think this problem originates from

a boundary line that is not accurate. This is also important when you need to submit the

green area ratio to the authorities and

If you're off by a little it can add up to quite a large area if it happens all

along the boundary line so

remember to be as accurate as possible when it comes to boundary line and

if you made a mistake

Check with your seniors.

## Not a junior's responsibility but it is important to be aware.
### 05:05-05:37

But honestly I think that

fresh graduates shouldn't be given the task to plot in the boundary line and

Also be blamed for this heavy responsibility

because ultimately,

this is a job that a senior Landscape Architect has to

be responsible for or the architect has to be responsible for, so at least now

You know what to look out for and how to be as accurate as possible and avoid any

mistakes that can happen in the future.

So going back to the coordinates, so this one this coordinate will be the last coordinate and

Just like the previous one a positive x and a negative Y
## Open up two viewport windows.
### 05:38-06:24
Removing the decimal point and let's check out our positions. In order to check out a position(Northing),

I will teach you a method to open up two viewports, the command is written above. Click on horizontal and ok then you will see two horizontal windows on your screen. On the top window, zoom in so that you can see
the imported image and then the bottom window,

Zoom in to the points you derive from the coordinate you keyed in.

## Align and Scale the plan using the two windows.
### 06:25-7:10


Now

we're ready for the align command type ALIGN enter and then select your drawing and

click on the first point and

Then click on a second point that the coordinates are referring to

and then choose an opposite diagonal point click on it

Then click on the second destination point, the coordinates are referring to

after clicking the second point type Y and Y for yes.

This is to scale the drawing based on the two alignment points and once you're done, you will realise that all the points are in place.

##Change 2 viewports to 1 viewports.
### 7:11-7:30


Now that the points are in place, we can easily draw out the boundary line using the points. In order to

Maximize our workspace. Let's change our viewports to

single viewport VPORT and then click single and ok.

## Using reference line to check if the boundary lines are straight.
### 7:31-9:51
Now we will start drawing reference lines to check if they are all straight lines and to create nodes

From the first reference line we can see that the first part of the boundary line is an arc

It's not parallel to the reference line

Try to click as

Accurate as you can and

Then when you do your polyline you will be... you will snap to the intersections that you have created

You can help another line here, but I didn't do it when I was

Doing the tutorial

I click it at the end of the straight line and I start another line at end of the arc

New line, a new reference line

And then another new reference line. Oh, but it's so short so we can

do without

And there's another point there for us to snap so it's ok

And then we start another reference line and looks like this line is also an arc

It's not parallel to the reference line

We skip the short one and continue to the

next line

Looks like there are a few lines here, so

There's an arc here

We'll click here

And then there's another

Arc or line

Following this Arc

It's an Arc

So using a reference line we can change it we can check whether it's arc or straight line

## Plot the boundary line using the reference lines.
### 09:52-12:26
Okay, now. We're ready to draw the boundary line. Change the color to blue

PL spacebar and

select the intersection

Use intersection when there's too many lines crisscrossing

so after PL spacebar, A spacebar for Arc and then D spacebar for the direction of the

Arc and then click on the midpoint of the Arc and then click on an endpoint of the Arc.

As before snap to the intersection of the two lines

Use ctrl(Win) or shift(Mac) right click to pick the intersection node

And in order to change from Arc to Line

Just type L Spacebar. L means line and

then

spacebar A for Arc and then sometimes you don't need to

click the midpoints, so you just click the endpoint and AutoCAD calculates the

Arc

From your first and last point and then continue to the next node

And then click on the end of the arc and

L spacebar for line

Basically you can repeat all the steps as shown previously of Line and Arcs

Over here, I'm looking for the midpoint of the Arc

Basically the most curved area of the arc and then click on the point

Snap it to the point

L spacebar

Snap to the intersection of the reference lines

and then final arc
## Finally change the layer colour, thickness and check the North direction.
### 12:27-13:57
This Ark seems like it has been adjusted so I will manually adjust it to

match the

existing

Boundary line on the image

So you will see later that this section of the boundary line is

Not smooth, and it juts out. Okay now, we're ready to delete the reference lines

We don't need them anymore. E spacebar Select and spacebar

Now we can change the color of the boundary line back to the color of the layer

And

Then bring to front so that it stays permanently in front of the drawing

And if you want to change the thickness of the line you can change it now

I remember to draw your boundary line with a thin with thin line. One point, I want to highlight is

Remember to keep the radius of the Ark

Generated by the AutoCAD when you draw it with the polyline

Because it will be the smoothest arc

And now you can come to check the North Point direction with Google Maps.
