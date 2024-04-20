# Scratch-3D-Size-Method
You can use this method for 3D rendering, projects and more!

1. First, you create a define block named "3D stamp"
2. Create a costume name "s//cat" (32x33 px or bigger)
3. Create a variable named "RPT1"
4. Place the block "set RPT1 to 0" under the define block I told you in step 1
5. Place the "repeat 10" block under the "set RPT1 to 0" block.
6. Change 10 of the repeat block into 30
7. Make a "_setSize (s)" define block.
8. Place a "if, else" block under the define block. 
9. In the boolean, place {s > 100}
10. Create a costume name "blank" (nothing in the costume) and "full" (all the costume fillen with the color #323232)
11. In the first box of the "if, else" block, place "switch costume to blank"
12. In the next box, place "switch costume to full"
13. Under the "if, else" block, place "set size to (s) %"
14. Create a define block named "stamp (c) (x) (y) (d) (s)"
15. Place the "_setSize (s)" block.
16. Then, "switch costume to join (s//) (c)"
17. Next, "go to x: (x) y: (y)"
18. "point in direction (d)" (Make sure you have set the rotation size into all around)
19. Place a "show" block.
20. Then a "Stamp" block. (This block is taken from Pen Extension"
21. Then a "Hide" block.
22. Another "_setSize (100000)" block.
23. And, the "switch costume to full" block.
24. Inside the loop I told you in Step 5, place a "stamp (cat) (rpt1) (0) (90 + (5 * (tan(10000000 * days since 2000)))) (150 + (70 * (tan(10000000 * days since 2000))))" block.
25. Under the stamp block, place a "change RPT1 by 0.5" block.
26. Put the "3D stamp" block in a forever loop.
27. Place the forever loop under a "when flag clicked" block.
28. Run your project and see!

You can see a tutorial in here: https://scratch.mit.edu/projects/1003549283. 

Also, don't forget  to give credit to me!
Post your project in this forum topic: 
