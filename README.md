# Checkerboard Challenge Reflection
----
1. I think that I did well on the assignment. My submission accomplished all the required goals, and performed well. One difference between my submission and the posted solution was the method for constructing the rectangles for the board. I opted to create the rectangles first, and set their anchors afterwards; the solution set the anchors at the time of construction. Additionally, I did not utilize the initialize function, while the solution set default values through initialize. These two differences should create no performance discrepancies, and are mostly stylistic differences. Finally, I use two different methods for resizing the board versus making changes to dimensions or color, whereas the solution uses one method for handling all cases. This is one place my solution could have been better, as my implementation required some code reuse. The most challenging part of the assignment for me was determining which level of the UI hieracrchy to watch for changes, and how to use those changes to determine what the new state of the board should be.

2. I understood most of the programming concepts and foundational knowledge needed to complete the challenge. The only portion of the challenge that required extra research or reading was creating and applying the change listeners to UI elements.

3. I met all of the requirements as set out in the challenge.

4. My solution is very similar to the posted solution. There are a few stylistic differences, but none of these should affect performance. The only major differences are: 1) I used seperate methods for each menu item and 2) I used different methods for resizing the board versus changing dimensions or color. These differences would not cause a major performance difference, but could be improved because they are less modular and reuse some code.

5. Going forward, I could improve on optimizing methods by writing them more efficiently. I understand everything that was required for that challenge.
