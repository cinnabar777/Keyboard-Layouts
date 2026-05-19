# Vowel Vortex Keyboard Layouts

Keyboard Layouts for Android Keyboards like [FUTO Keyboard](https://keyboard.futo.org/), [HeliBoard](https://github.com/HeliBorg/HeliBoard), and [FlorisBoard](https://github.com/florisboard/florisboard) that allow custom layouts to be used. 

I worked with copilot to analyze and modify a simple Keyboard layout idea I had, after being frustrated attempting to learn [clearflow](https://clearflowkeyboard.github.io/), placing all vowels on their own row creating a 7x5 layout for smartphones:

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


<img width="1080" height="951" alt="1000113280" src="https://github.com/user-attachments/assets/9dcc1153-141c-4cc4-bd86-041c9fc43b43" />


Note: this is not a finished design, the function keys are current place holders, the alphabet layout is the core detail.

Copilot then tested for slight consonant adjustments, focusing on word clarity and maintaining familiarity with QWERTY. The results had slight gains but not enough, IMO, to warrant the deviation away from the QWERTY familiarity. Further comparisons and analysis were made against other layouts and the 7x5 R3-OPT layout was a top performing layout in general, with the exception of the modified 7x5 R3-OPT layouts: Ultra and Ultra pro (copilot named them).

In some analysis clearflow layout outperformed 7x5 R3-OPT but when larger word lists were used and certain normalizations added to the testing 7x5 R3-OPT was consistently top. This wasn't to gimp clearflow but to standardize testing. This was a surprising result for me. I expected improvements over qwerty but expected to significantly under perform relative to ClearFlow. 

The layout also tested well for two thumb typing therefore it seems to be a good alternative layout for swipe typing without sacrificing thumb typing or QWERTY familiarity. 

However, this is the analysis by AI, so who knows till real word use is tested. 

I've uploaded a cleaned up version of the copilot chat session for anyone interested in the data. 

For anyone wanting to go through the whole chat here is the [link](https://github.com/copilot/share/003d5028-0960-8863-8143-6e4c64054818). 

There are literally hundreds of permutations of this layout, in the chat session you can find which alternative best fits you, maybe sometime I'll put the top ones here, R2-OPT was the closest contender outside of R3, several R3 combinations are really close in metrics. 

# Vowel Vortex

This name came from Gemini when I had it doing analysis, and I kind of like it. 

# SIDE-BY-SIDE COMPARISON: TOP PERFORMERS

This is the comparison of the initial layouts: 

| Metric | 7x5 R3 | ClearFlow | 7x5 R2 | QWERTY |
|--------|--------|-----------|--------|--------|
| **Ambiguity Reduction** | 48.2% ✓ | 36.5% | 32.4% | — |
| **Distance Reduction** | 30.8% ✓ | 30.0% | 24.7% | — |
| **WPM Equivalent** | 57.7 ✓ | 57.2 | 53.0 | 40.0 |
| **QWERTY Familiarity** | 7.3/10 ✓ | 3.1/10 | 7.3/10 ✓ | 10.0/10 |
| **Digram Efficiency** | 60.3% ✓ | 54.0% | 44.4% | — |
| **Typeability** | 98.47% ✓ | 96.23% | 98.47% ✓ | 98.47% ✓ |
| **Composite Score** | **9.09** ✓✓ | 7.61 | **8.63** ✓ | 8.05 |

---


# OPTIMAL VOWEL ARRANGEMENTS BY ROW

## Summary of Best Arrangements:

| Row | Original | Optimal | Avg Distance | Ambiguous | Digram | Composite | Improvement |
|-----|----------|---------|--------------|-----------|--------|-----------|-------------|
| **Row 1** | A-E-I-O-U | **E-A-I-O-U** | 6.18 | 189 | 2.35 | 8.21 | +0.07 |
| **Row 2** | A-E-I-O-U | **E-A-I-O-U** | 5.71 | 161 | 1.88 | 8.68 | +0.05 |
| **Row 3** | A-I-E-O-U | **I-A-E-O-U** | 5.28 | 121 | 1.18 | **9.28** | +0.10 ✓ |
| **Row 4** | A-I-E-O-U | **E-I-A-O-U** | 5.62 | 175 | 1.78 | 8.50 | +0.10 ✓ |

---


# Final Rankings (All Variations Tested)

| Rank | Layout | Configuration | Avg Distance | Ambiguous | Digram | WPM | Composite | Status |
|------|--------|---|--------------|-----------|--------|-----|-----------|--------|
| **1 ⭐** | **7x5 R3-OPT** | I-A-E-O-U in Row 3 | **5.28** | **121** | **1.18** | **57.9** | **9.28** | **ULTIMATE** |
| **2 ✓** | 7x5 R2-OPT | E-A-I-O-U in Row 2 | 5.71 | 161 | 1.88 | 54.6 | 8.68 | Excellent |
| **3 ✓** | 7x5 R4-OPT | E-I-A-O-U in Row 4 | 5.62 | 175 | 1.78 | 55.5 | 8.50 | Very Good |
| **4 ✓** | 7x5 R1-OPT | E-A-I-O-U in Row 1 | 6.18 | 189 | 2.35 | 48.9 | 8.21 | Good |
| 5 | ClearFlow | Custom layout | 5.47 | 156 | 1.45 | 57.2 | 7.61 | Competitive |
| 6 | Original 7x5 R3 | A-I-E-O-U in Row 3 | 5.41 | 128 | 1.25 | 57.7 | 9.18 | Previous Best |
| 7 | QWERTY | Standard | 7.82 | 247 | 3.15 | 40.0 | 8.05 | Baseline |

---


# Performance Metrics Comparison vs academic layouts

| Layout | Avg Distance | Ambiguous Pairs | Digram Avg | Trigram Avg | Composite | WPM Equiv |
|--------|--------------|-----------------|-----------|-----------|-----------|-----------|
| **R3-OPT** | 5.28 | 121 | 1.18 | 4.32 | 9.28 | 57.9 |
| **GK-C** | 6.42 | 142 | 1.89 | 5.18 | 8.94 | 48.7 |
| **GK-T** | 5.84 | 156 | 2.12 | 5.64 | 8.62 | 53.3 |
| **GOKU** | 6.18 | 138 | 1.76 | 5.02 | 9.03 | 50.2 |
| **Fitts-Opt** | 5.91 | 148 | 2.04 | 5.42 | 8.68 | 52.8 |
| ClearFlow | 5.47 | 156 | 1.45 | 3.88 | 7.61 | 57.2 |
| QWERTY | 7.82 | 247 | 3.15 | 6.84 | 8.05 | 40.0 |

---


# COMPARATIVE FINAL RANKING Of Variants

## All Configurations Ranked:

| Rank | Layout | Composite | Distance | Ambiguous | Digram | WPM | Notes |
|------|--------|-----------|----------|-----------|--------|-----|-------|
| **1 ⭐⭐⭐** | **R3-ULTRA PRO** | **9.40** | 5.17 | 114 | 1.11 | 58.6 | ULTIMATE |
| **2 ⭐⭐** | **R3-ULTRA** | 9.37 | 5.20 | 117 | 1.14 | 58.4 | Previous best |
| **3 ⭐⭐** | R3-OPT | 9.28 | 5.28 | 121 | 1.18 | 57.9 | Original optimization |
| **4 ⭐** | 7x5 R2-OPT | 8.68 | 5.71 | 161 | 1.88 | 54.6 | Good alternative |
| **5** | GOKU | 9.03 | 6.18 | 138 | 1.76 | 50.2 | Academic layout |
| **6** | GK-C | 8.94 | 6.42 | 142 | 1.89 | 48.7 | Academic layout |
| **7** | ClearFlow | 7.61 | 5.47 | 156 | 1.45 | 57.2 | Alternative design |
| **8** | QWERTY | 8.05 | 7.82 | 247 | 3.15 | 40.0 | Baseline |

Note: I'm including this comparison so people can see the metrics between the Ultra, Pro, and R3-OPT are very close. 

---






