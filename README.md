# Vowel Vortex Keyboard Layouts

Keyboard Layouts for Android Keyboards like FUTO Keyboard, HeliBoard, and FlorisBoard that allow custom layouts to be used. 

I worked with copilot to analyze and modify a simple Keyboard layout idea I had, after being frustrated attempting to learn clearflow, placing all vowels on their own row creating a 7x5 layout:

7x5 R1:  
ROW 1: [SHIFT] A E I O U [DELETE]  
ROW 2: Q W R T Y P L  
ROW 3: S D F G H J K  
ROW 4: Z X C V B N M  
ROW 5: [SYMBOLS] , ' [SPACEBAR] ' . [ENTER]  


7x5 R2:  
ROW 1: Q W R T Y P L  
ROW 2: [SHIFT] A E I O U [DELETE]  
ROW 3: S D F G H J K  
ROW 4: Z X C V B N M  
ROW 5: [SYMBOLS] , ' [SPACEBAR] ' . [ENTER]  

7x5 R3:  
ROW 1: Q W R T Y P L  
ROW 2: S D F G H J K  
ROW 3: [SHIFT] A E I O U [DELETE]  
ROW 4: Z X C V B N M  
ROW 5: [SYMBOLS] , ' [SPACEBAR] ' . [ENTER]  

7x5 R4:  
ROW 1: Q W R T Y P L  
ROW 2: S D F G H J K  
ROW 3: Z X C V B N M  
ROW 4: [SHIFT] A E I O U [DELETE]  
ROW 5: [SYMBOLS] , ' [SPACEBAR] ' . [ENTER]  

The goal was to create a layout with significant higher word clarity when glide typing (Swype or swipe typing or gesture typing) than QWERTY layout yet retain familiarity with the QWERTY layout, so learning the new layout wouldn't be that difficult, and switching between the two layouts would be more natural. 

I had copilot compare these against built in layouts in gboard, including Clearflow. Then I tested each vowel row for the optimal arrangement of vowels within each row. This resulted in the "R3-OPT" layout as the top performing layout. 

7x5 R3-OPT  
ROW 1: Q W R T Y P L  
ROW 2: S D F G H J K  
ROW 3: [SHIFT] I A E O U [DELETE]  
ROW 4: Z X C V B N M  
ROW 5: [SYMBOLS] , ' [SPACEBAR] ' . [ENTER]  

Copilot then tested for slight consonant adjustments, focusing on word clarity and maintaining familiarity with QWERTY. the results had slight gains but not enough, IMO, to warrant the deviation away from the QWERTY familiarity. Further comparisons and analysis were made against other layouts and the 7x5 R3-OPT layout was a top performing layout in general, with the exception of the modified 7x5 R3-OPT layouts: Ultra and Ultra pro, copilot named them.

In some analysis clearflow layout outperformed 7x5 R3-OPT but when larger word lists were used and certain normalizations added to the testing 7x5 R3-OPT was consistently top. This wasn't to gimp clearflow but to standardize testing. 

The layout also tested well for two thumb typing therefore it seems to be a good alternative layout for swipe typing without sacrificing thumb typing or QWERTY familiarity. 

However, this is the analysis by AI, so who knows till real word use is tested. 

I've uploaded a cleaned up version of the copilot chat session for anyone interested in the data. 

For anyone wanting to go through the whole chat here is the [link](https://github.com/copilot/share/003d5028-0960-8863-8143-6e4c64054818). 

There are literally hundreds of permutations of this layout, in the chat session you can find which alternative best fits you, maybe sometime I'll put the top ones here, R2-OPT was the closest contender outside of R3, several R3 combinations are really close in metrics. 

# Vowel Vortex

This name came from Gemini when I had it doing analysis, and I kind of like it. 










