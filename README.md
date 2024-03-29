# ![Mosaic Logo](http://mindlab.ai/images/mosaic.png)  
# Mosaic
The Ultimate JavaFX, Multi-split, Drag-n-Drop Layout Manager 

[![htm.java awesomeness](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](http://cogmission.ai)
***

## On [YouTube](https://youtu.be/eVH-Q85hqe0) (CLICK!)


# ![Demo](http://mindlab.ai/images/MosaicDemo.gif)

Mosaic is an **amazing** new layout manager which allows you to split your screen however you want with no nesting; Drag dividers in _**ANY**_ direction; and Drag-N-Drop contents anywhere, and the layout will intelligently morph into a new configuration while snapping to suggested locations!

OH YEAH...

Using Any Java Windowing Toolkit! (i.e. JavaFX, Swing, Apache Pivot etc.)

**Discerning Developer:** "Sounds cool... How does it do that!!!?"

Mosaic is an engine that furnishes dimensions and locations for objects it is given. So...
Step 1: Load it with objects in the same container 
Step 2: Attach mouse listener to your container (albeit JavaFX Node, Swing or Apach Pivot Container); inside of which; forward events to the Mosaic Engine
Step 3: Inside listener, apply location and dimension instructions to the object it tells you to...

Easy peasy!

***

### To use Demo: (in the "src/test/java" source tree)

1. Fork or clone repo
2. Setup in the IDE of your choice
3. Run the:
  * ai.cogmission.mosaic.refimpl.javafx.MosaicPaneRefImpl.java
  * -- or --
  * ai.cogmission.mosaic.refimpl.pivot.MosaicPaneRefImpl.java
4. All Dependencies are in "libs" directory.

***

### To Implement yourself: (in the "src/main/java" source tree)

Take a look at the  ai.cogmission.mosaic.refimpl.javafx.MosaicPane.java or  ai.cogmission.mosaic.refimpl.pivot.MosaicPane.java file for reference on how to implement your own container that can be managed by the Mosaic Engine.

Better instructions are on the way... (we need your help!)

***

### To Contribute: (This _**is**_ open source and free after all)

Contact me at: cognitionmission@gmail.com


