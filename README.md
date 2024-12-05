# CHAPTER_8
Flutter (Mobile app development)

CREATING AN NAVIGATION 


In this chapter, I focused on one of the most essential parts of any app—navigation. I learned how to use the Navigator widget to manage a stack of routes, making it possible to move between different pages. What’s even better is that I can pass data between pages and even send it back to the original page when needed.

One of the features I found really cool is the hero animation. It creates a smooth transition effect where a widget seems to “fly” from one page to another. To make this work, I just had to wrap the widgets I wanted to animate in a Hero widget and assign a unique key to each. It’s such a simple way to make transitions feel more natural.

I also explored the BottomNavigationBar widget, which displays a horizontal list of items at the bottom of the screen. Each item includes an icon and a title, and when tapped, it navigates to the corresponding page. To take it a step further, I used the BottomAppBar widget with an optional notch for embedding a FloatingActionButton. By customizing the shape with CircularNotchedRectangle() and positioning the button using FloatingActionButtonLocation.endDocked, I was able to create a polished, modern design.

Another handy tool I learned about was the TabBar widget. It lets me create a row of tabs that users can either tap on or swipe through to change the content. The TabBarView widget worked seamlessly with it to display the content of the selected tab. To keep everything in sync, I used the TabController class with SingleTickerProviderStateMixin—this part felt technical at first, but it clicked once I tried it out.

Finally, I added the Drawer widget, which slides in a panel from the left or right side of the screen. By setting the Scaffold drawer or endDrawer property, I could easily create a slide-out menu for navigation. Aligning the menu items was straightforward too, thanks to passing a simple list of widgets.
This chapter really emphasized how much thought goes into making navigation user-friendly and visually appealing. It’s not just about getting from point A to point B—it’s about making the journey smooth and enjoyable for the user.
