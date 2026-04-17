# Entry 4
##### 03/15/26

## Tinkering with A-Frame

##### Context
For this entry, the tool I explored was A-Frame. A-Frame is a web framework that allows developers to create virtual reality (VR) scenes using HTML. Instead of using complicated programming languages, A-Frame lets you build 3D environments with simple tags and elements. This makes it easier for beginners to start learning how VR works on the web.

##### What I Tinkered With

When I first started using A-Frame, I experimented with creating simple 3D objects inside a scene. I tested different elements like boxes, spheres, and planes to see how they appear in a VR environment. I also changed properties such as color, size, and position to understand how objects can be customized.
For example, I tried creating a box object and changing its color and position to see how it would look inside the scene.

##### What I Learned

While tinkering with A-Frame, I learned that small changes in the code can make big differences in the virtual scene. For example, changing the position numbers moves objects in 3D space, and changing the color attribute quickly updates how the object looks.
I also learned that A-Frame is helpful because it uses HTML-like syntax, which makes it easier to understand compared to more complex 3D programming tools.

##### Skills

One skill I improved is using the position and rotation attributes more accurately. Before, I was just placing objects randomly and hoping they looked right, but now I understand how the x, y, and z coordinates actually affect where objects appear in the scene. For example, I experimented with placing multiple objects at different distances and heights to create a more realistic layout. 

Another skill I developed is adding basic interactivity using events. I learned how to make objects respond when the user interacts with them, such as clicking. This made my project more engaging instead of just being a static scene.


##### Evidence of Tinkering

```language
<a-box position="0 1 -3" rotation="0 45 0" color="blue"></a-box>
<a-sphere position="2 1.5 -4" radius="0.5" color="red"></a-sphere>
<a-plane position\
0 0 -4" rotation="-90 0 0" width="6" height="6" color="green"></a-plane>
```
```language
<a-box position="0 1 -3" color="blue"
        event-set__enter="_event: click; color: red">
</a-box>
```





##### Sources
A-Frame documentation:

https://aframe.io/docs/1.5.0/introduction/

https://docs.google.com/presentation/d/1C8xDyvXzVgtX3G8UdXVNEn2PWVnsLF0sPu4QMRCL7xY/edit?slide=id.g849c2abd37_0_0#slide=id.g849c2abd37_0_0






















[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
