---
layout: default
title: "Syntax Highlighting Test Case"
---

```c++
// draw slices
for (int s = 0; s < slice; ++s)
{
    int i = s < 12 ? s 
                   : s - 12;
    
    float cx = getWidth() / 2.0f 
             - moveLeft
             + (s < 6 ? moveRight 
                      : (s < 12 ? - moveRight 
                                : moveRight * 2.39f));
             
    float cy = getHeight() / 2.0f 
             - shiftCentreY
             + (s >= 6 && s < 12 ? moveDown
                                 : moveUp);
 }                                
```
