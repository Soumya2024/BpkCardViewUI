## Build the UI
a. Now it’s finally time to add some Backpack components to your new UI! What our
app looks like is determined by an xml file called ‘activity_main’. This file
describes all of the different components and their corresponding parameters on
the screen.
b. Open up ‘activity_main.xml’ from the ‘res/layout’ folder of the project sidebar.
There are three ways to view this file, listed in the upper right corner. ‘Code’ will
show you the raw xml code; ‘Design’ will let you view and edit visual components
on the screen; and ‘Split’ will give you a hybrid view.
c. Let’s start by deleting the greeting component that was automatically generated
at project creation, ‘hello world’. You can do so by deleting the xml snippet or by
deleting the visual component in the Design pane.
d. With our newly blank slate, it’s time to add some of our own components. Let’s
start with a card — take a look at the Backpack documentation. Copy the xml
snippet into your code as a child of the ‘ConstraintLayout’ tag. This component is
now floating casually around the screen and needs to be constrained to a
location. From the ‘Component Tree’ sidebar of the Design pane, right click on
‘BpkCardView’ and centre the component horizontally and vertically. The red
squiggles under your card component in the Code view should now be gone,
since the component has a defined location on the screen. Next, let’s embellish
your card by enlarging the corners — change the ‘cornerStyle’ attribute to large
from either the Code view or the attributes sidebar of the Design pane.
e. Now let’s add some information to the UI. Change the ‘android:text’ attribute of
the ‘BpkText’ component to read ‘Departure’. Then add the following attribute to
the component in order to increase its size: ‘style="@style/bpkTextHeading1"’.
f. Now for some more structure! Add a ‘LinearLayout’ (vertical) to your UI by
dragging it from the Palette sidebar of the Design pane into the Component Tree
underneath ‘BpkCardView’. Then move the ‘BpkText’ component into the layout.
g. You should now have a pretty good sense of how to manipulate components and
their attributes using Android Studio. Your task is to create a UI that incorporates
the following information in a visually pleasing fashion:
i. Flight information card with:
1. Flight number
ii. Departure card with:
1. A three-digit airport code of your choice
2. A departure time
iii. Arrival card with:
1. A three-digit airport code of your choice
2. An arrival time
