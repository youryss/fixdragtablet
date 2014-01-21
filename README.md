Fix Drag and drop on Tablet (javascript and html)
========================

##What?
You can drag and drop elements on ipad and scroll the page as well with

##WHY?
I created this fix because I couldn't find something that works for my app.

I have a dashboard with some elements and I couldn't use the drag and drop feature on a tablet. And to allow this feature now using my fix, the user have to hold the element for some milesecond and then drag the element around.

So I had to search a lot and the result was just some lines :)


After days trying to create a work around to let the drag and drop works on IOS(Ipad) I could build an elegant fix for that.

##LIBS
I used jquery, Jquery Ui (drag and drop feature), Ui jquery touch punch (This plugin transform all the mouse events to touch events) and the jquery taphold plugin.

##PROCESS
The only think that I changed on Jquery touch punch was the line 42 that I had to create a flag when returns true if the user hold the element(in this case a div) the element will be bigger and then the user will be able to drag the element round. Onces he drop the element the drag and drop will be disbale and the flag will be false letting the user scroll the page without moving a card

##Examples

Here's two videos that I made using ipad mini to test the fix
[Video one](https://www.youtube.com/watch?v=Zb3Mmt-HMpQ)
[Video two](https://www.youtube.com/watch?v=ntSOCv_4eWE)