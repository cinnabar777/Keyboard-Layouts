# VOWEL VORTEX KEYBOARD LAYOUTS

Keyboard Layouts for Android Keyboards like [FUTO Keyboard](https://keyboard.futo.org/), [HeliBoard](https://github.com/HeliBorg/HeliBoard), and [FlorisBoard](https://github.com/florisboard/florisboard) that allow custom layouts to be used. The layouts are focused on glide (Swype, swipe, or gesture) typing on mobile, increasing word clarity (decreasing typos) while maintaining familiarity with the qwerty layout.

## THE IMPETUS

The [clearflow](https://clearflowkeyboard.github.io/) layout was being added to FUTO keyboard, hadn't really noticed it before, and ever since the demise of Swype I've been very disappointed with glide typing on other keyboards. I made a custom layout of ClearFlow in FUTO keyboard to test it. It's a wild departure from QWERTY! Therefore it was going to take some learning, however what started bothering me the most about it wasn't the alphabetical layout, it was the function keys on the sides and the size of the keys:

<img width="1080" height="1057" alt="1000113427" src="https://github.com/user-attachments/assets/0be80a46-b560-4ecd-99f8-7e2fb6116a65" />


While this makes the keyboard very symmetrical it also keeps the key sizes very small, something I've always hated on mobile. Therefore I really started to evaluate the benefits of switching layouts, later tests confirmed that while I may get less errors using ClearFlow the increase in typing speed is a myth.

### WORD DISTANCE

Throughout my testing layouts with Gemini and Copilot they both often wanted to give preference to layouts that minimized the gesture length of a word, and those layouts were given a higher theoretical typing speed. I finally decided to put this to the test via a very simplified typing test. I used ClearFlow, QWERTY, and a couple of my layouts, chose three words: that, there, and this. I chose those words because they had good tight gestures on ClearFlow and long gestures on my layouts. I gesture typed each word for one minute on each layout as fast as I could — this would give me a theoretical maximum I could type on any of these layouts, no way am I going to type faster than this.

### SPEED TESTS RESULTS

**ClearFlow:**  

- That: 309 cpm. 
- There: 275 cpm.  
- This: 316 cpm.  
- TTL: 900/3=300 cpm, 60 wpm.  

**Vowel Vortex:**  

- R4 OUIEA: That: 302 cpm.  
- R4 AEUIO: There: 295 cpm.  
- R4 AEUIO: This: 291 cpm
- TTL: 888/3=296 cpm, 59.2 wpm
- R4 IAEOU (R3-OPT): That: 305 cpm
- R4 IAEOU (R3-OPT): There: 310 cpm
- R4 IAEOU (R3-OPT): This: 288 cpm
- TTL: 903/3=301 cpm, 60.2 wpm

**QWERTY Gboard:**

- That: 302 cpm
- There: 334 cpm
- This: 293 cpm
- TTL: 929/3=309.7 cpm, 61.93 wpm

From the results you can see there isn't a significant difference, and there really is no way I could gesture type faster than this. Pointing this out to Gemini it pointed out Fitts’s Law, vector changes, etc, all confirming that you aren't going to type faster because of a different layout giving you shorter gesture length for words, yet the AIs pushed exactly that saying you would get faster speeds, until I pointed out that real word tests disagreed. 

The reality is, you are only going to type as far as you are going to type on any layout, it's your natural speed that defines how fast you can type on any layout. The "theoretical" speed created by mathmatical models usually don't take into account that you can move through longer distances faster, and often short tight gestures are slower to do. 

So if you aren't going to magically type faster then what's the point of using a different layout? Increased word clarity which reduces typing errors. That really is the main reason to use a different layout. ClearFlow does this very well, but at a very high learning curve.

## THE BASIC IDEA

Not satisfied with ClearFlow I decided to try some different layouts, I made some in the past using Multiling O Keyboard, but never tried the "Vowel Vortex" layout. The idea was simple, there's 26 letters in English plus the shift and delete key, 28 fits into 4 rows perfectly thus:


<img width="1080" height="875" alt="1000113430" src="https://github.com/user-attachments/assets/2735f9ea-0148-40b3-93ae-3c382be0443b" />


This idea leads to four core layouts:

7x5 R1:

- ROW 1: [SHIFT] A E I O U [DELETE]
- ROW 2: Q W R T Y P L
- ROW 3: S D F G H J K
- ROW 4: Z X C V B N M

7x5 R2:

- ROW 1: Q W R T Y P L
- ROW 2: [SHIFT] A E I O U [DELETE]
- ROW 3: S D F G H J K
- ROW 4: Z X C V B N M

7x5 R3:

- ROW 1: Q W R T Y P L
- ROW 2: S D F G H J K
- ROW 3: [SHIFT] A E I O U [DELETE]
- ROW 4: Z X C V B N M

7x5 R4:

- ROW 1: Q W R T Y P L
- ROW 2: S D F G H J K
- ROW 3: Z X C V B N M
- ROW 4: [SHIFT] A E I O U [DELETE]

I then worked with Copilot and Gemini to analyze and modify the simple Keyboard layout idea, still thinking that there was some amazing optimization to increased wpm and word clarity,

The goal was to create a layout with significant higher word clarity when glide typing (Swype or swipe typing or gesture typing) than QWERTY layout yet retain familiarity with the QWERTY layout, so learning the new layout wouldn't be that difficult, and switching between the two layouts would be more natural, however, I lost sight of maintaining familiarity with QWERTY during this process, becoming amazed at the potential Copilot said these layouts had.

### COPILOT OPTIMIZATION

I had copilot compare these layouts against built in layouts in gboard, including Clearflow. Then I tested each vowel row for the optimal arrangement of vowels within each row. This resulted in the "R3-OPT" layout as the top performing layout. However there was a mistake in this, I used my personal dictionary of ~10,000 words instead of staying with the top 100 words then moving to the top 1,000. Nonetheless Copilot came up with this as its favorite layout:

7x5 R3-OPT

- ROW 1: Q W R T Y P L
- ROW 2: S D F G H J K
- ROW 3: [SHIFT] I A E O U [DELETE]
- ROW 4: Z X C V B N M

<img width="1080" height="951" alt="1000113280" src="https://github.com/user-attachments/assets/9dcc1153-141c-4cc4-bd86-041c9fc43b43" />


Copilot then tested for slight consonant adjustments, focusing on word clarity and maintaining familiarity with QWERTY. The results had slight gains but not enough, IMO, to warrant the deviation away from QWERTY. Further comparisons and analysis were made against other layouts and the 7x5 R3-OPT layout was a top performing layout in general, with the exception of the modified 7x5 R3-OPT layouts: Ultra and Ultra pro (copilot named them).

In some analysis clearflow layout outperformed 7x5 R3-OPT but when larger word lists were used and certain normalizations added to the testing 7x5 R3-OPT was consistently top. This wasn't to gimp clearflow but to standardize testing. This was a surprising result for me. I expected improvements over qwerty but expected to significantly under perform relative to ClearFlow.

The layout also tested well for two thumb typing therefore it seemed to be a good alternative layout for swipe typing without sacrificing thumb typing or QWERTY familiarity.

I've uploaded a cleaned up version of the copilot chat session for anyone interested in the data.

For anyone wanting to go through the whole chat here is the [link](https://github.com/copilot/share/003d5028-0960-8863-8143-6e4c64054818).

There are literally hundreds of permutations of this layout, in the chat session you can find which alternative best fits you, R2-OPT was the closest contender outside of R3, several R3 combinations are really close in metrics.

___

#### SIDE-BY-SIDE COMPARISON: TOP PERFORMERS

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

#### OPTIMAL VOWEL ARRANGEMENTS BY ROW

##### SUMMARY OF BEST ARRANGEMENTS

| Row | Original | Optimal | Avg Distance | Ambiguous | Digram | Composite | Improvement |
|-----|----------|---------|--------------|-----------|--------|-----------|-------------|
| **Row 1** | A-E-I-O-U | **E-A-I-O-U** | 6.18 | 189 | 2.35 | 8.21 | +0.07 |
| **Row 2** | A-E-I-O-U | **E-A-I-O-U** | 5.71 | 161 | 1.88 | 8.68 | +0.05 |
| **Row 3** | A-I-E-O-U | **I-A-E-O-U** | 5.28 | 121 | 1.18 | **9.28** | +0.10 ✓ |
| **Row 4** | A-I-E-O-U | **E-I-A-O-U** | 5.62 | 175 | 1.78 | 8.50 | +0.10 ✓ |

---

#### FINAL RANKINGS (ALL VARIATIONS TESTED)

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

#### PERFORMANCE METRICS COMPARISON VS ACADEMIC LAYOUTS

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

#### COMPARATIVE FINAL RANKING OF VARIANTS

##### ALL CONFIGURATIONS RANKED

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

### GEMINI OPTIMIZATION

I really went in circles with Gemini, I am fairly certain Gemini is programmed to agree with you and tell you what it thinks you want to hear more than, well, anything else. I had to teach it how to analyze word conflict based on gestures instead of word ambiguity based on shared letters, and it would keep falling back into old patterns, nonetheless, after much conversation, testing, and annoyances Gemini's top layouts based on increased word clarity are:

| #    | Vowels    | **100** | **1k** |
| ------ | ----------- | ------- | ------ |
| **1**  | `i e o a u` | **1**   | **9**  |
| **2**  | `o i e a u` | **2**   | **11** |
| **3**  | `u e a i o` | **2**   | **14** |
| **4**  | `a e i o u` | **3**   | **12** |
| **5**  | `e i a o u` | **3**   | **13** |
| **6**  | `i e a o u` | **4**   | **12** |
| **7**  | `u i e o a` | **4**   | **15** |
| **8**  | `o a e i u` | **4**   | **16** |
| **9**  | `e o u a i` | **5**   | **15** |
| **10** | `a i e o u` | **5**   | **17** |

 The table lists the number of word conflicts that layout would have, but it only tested against the other words in that list, Gemini just didn't want to test against a dictionary, therefore, these results aren't really that useful, but I did do some real world testing.

### WORD CONFLICTS

I used different layout versions based on Copilot and Gemini and went through gesture typing the top 100 words, intentionally being off by one letter when dealing with the vowel row. Gemini layouts did usually get lower errors, around 55 to 60, while the original R4 "AEUIO" got 65, and Copilot's top layout got 66. This is out of ~300 gestures, and doing the test on Gboard I stopped counting at 130 and wasn't that close to finishing. I figure about a 2 to 3 times decrease in "sloppy gesture" errors when typing the top 100 words, regardless of which Vowel Vortex layout you use, however, it's much easier to be accurate on the larger keys. 

### MAXIMUM WORD CLARITY

I wasn't happy with the potential errors, yes I could gesture the top 100 words over ten times each and only have a handful of errors, amazing, but the potential for error bugged me. Much analysis with Gemini proved fruitless. I used custom sized gaps between the vowels which helped significantly but introduced another problem, if the user started the gesture off the vowel just enough to be on the gap then the algorithm didn't get the start point correct, and that's a big problem.

I came up with two ways to maximize word clarity and minimize potential errors when it came to the vowel row:

1. Use functional non-letter keys between each vowel for separation: period, comma, or apostrophe. These keys didn't cause a dead space like using a 'gap' did. This looks ugly but works amazingly well.
2. Increase the size of the vowels. This required moving shift and delete and having a rather non-uniform layout. In this situation using gaps or the functional keys as spacers works incredibly well.

This gave me, what I call, the "Vowel Vortex Clarity" layout:


<img width="1080" height="2400" alt="1000113410" src="https://github.com/user-attachments/assets/49fd041b-92c9-401f-a80c-fc6edc8c1445" />


### MAXIMUM FAMILIARITY

The above image compares the 'clarity' layout to QWERTY, look at how you would make the gesture, this layout maximizes familiarity, from the start you aren't hunting for letters, minimal learning curve.

Once I realized I wasn't getting a massive increase in typing speed, and the best work around for potential word errors and conflicts was either using gaps, functional non-letter keys, or increasing the vowel size things fell into place. While the Copilot layout, R3-OPT, was actually very nice for gesture typing it introduced too much deviation from QWERTY thus significant learning curve. For some people they might want to use an optimized vowel row, however, for me sticking with the QWERTY vowel order seems best over all, then use the tricks, if you need or want to maximize word clarity.

My personal preference is the simple big key version, no tricks added:


<img width="1080" height="875" alt="1000113430" src="https://github.com/user-attachments/assets/2735f9ea-0148-40b3-93ae-3c382be0443b" />


For me the key size is big enough in this version to side step most word conflicts with the vowels, and having the bottom row keys maintain this larger size helps with errors like 'then' vs 'them', but the flexibility is there for everyone to maximize their goals. Keeping the vowels on row 2 maximizes familiarity with QWERTY, the movements feel familiar from the start, but you have the options available! 

## VOWEL VORTEX NAME

This name came from Gemini when I had it doing analysis, and I kind of like it.

---

## CODE

## FUTO KEYBOARD

```
name: Vowel Vortex FUTO Simple
description: Vowel Vortex layout for FUTO Keyboard, basic
overrideWidths:
  FunctionalKey: 0.2   # Sets $shift and $delete to exactly 0.2 width

rows:
  - letters: q w r t y p l
  - letters: s d f g h j k
  - letters: $shift i a e o u $delete
  - letters: z x c v b n m
```

[Here is a complete YAML for FUTO keyboard](https://github.com/cinnabar777/Vowel-Vortex-Keyboard-Layouts/blob/main/FUTO%20YAML.md).

## CONCLUSION

My conclusion, since I do not have the hardware, and I'm not a software engineer, to run proper in-depth metrics with a real glide typing algorithm, is that each user should use what feels most comfortable and makes the most sense.

For anyone wanting to use one of these layouts I suggest first testing how you like the different vowel rows, then look for the type of optimization you want, distance vs clarity vs familiarity. You can even ask Copilot, or Gemini if you trust it, to optimize a Vowel row via your own personal word usage. 

All in all I am happy with the Vowel Vortex layouts, they offer increased word clarity, more comfortable typing on mobile (bigger keys), retain high familiarity with QWERTY, and are flexible, they can be customized to every person's preferences. 
