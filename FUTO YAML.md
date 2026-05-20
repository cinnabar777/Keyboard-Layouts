This is a loaded version of the layout for FUTO, easier to delete stuff than add. I have added gaps between the vowels to increase clarity, seemed to help. There were several issues with building this layout, the biggest was getting the different keys correctly sized. Overall this version, vowels on row 3, works well once you get the shift and delete key sized correctly, though it takes a little adjustment not to hit the m key when deleting. 

I've hidden the hint for all keys to help focus on learning the new layout. 

There is an apostrophe on each side, using the tiny vowel gap. Gesturing to that area works for contractions etc. 

```
name: Vowel Vortex
description: Vowel Vortex layout for FUTO Keyboard with Grow parameters
overrideWidths:
  Custom1: 0.14  # not used
  Custom2: 0.11  # not used
  Custom3: 0.01  # gap between vowels / balance buffers
  Custom4: 0.114 # not used
  FunctionalKey: 0.19   # Sets $shift and $delete to exactly 0.19 width
rows:
  - letters: [
      {type: base, spec: 'q', hint: " ", attributes: { width: Grow }, moreKeys: ["~", "\u0022", "?", "¿"]},
      {type: base, spec: 'w', hint: " ", attributes: { width: Grow }, moreKeys: ["1", "`", "¹", "₁", "½", "⅓", "¼", "⅕", "⅙", "⅐", "⅛", "⅑", "⅒"]},
      {type: base, spec: 'r', hint: " ", attributes: { width: Grow }, moreKeys: ["2", "•", "²", "₂", "⅔", "⅖"]},
      {type: base, spec: 't', hint: " ", attributes: { width: Grow }, moreKeys: ["3", "`", "³", "₃", "¾", "⅗", "⅜", "√", "~", "×"]},
      {type: base, spec: 'y', hint: " ", attributes: { width: Grow }, moreKeys: ["!icon/action_redo|!code/action_redo", "4", "π", "⁴", "₄", "⅘"]},
      {type: base, spec: 'p', hint: " ", attributes: { width: Grow }, moreKeys: ["!icon/numpad|!code/key_to_number_layout", "5", "⁵", "₅", "⅚", "⅝", "=", "|", "%|%", "‰", "π", "Π", "+", "±", "₊", "⁺", "#"]},
      {type: base, spec: 'l', hint: " ", attributes: { width: Grow }, moreKeys: [")", "]", "⟩", "}", "\\", "|", ">", "≥", "›", "»"]}
    ]
  - letters: [
      {type: base, spec: 's', hint: " ", attributes: { width: Grow }, moreKeys: ["#", "№", "§", "★", "¶", ";"]},
      {type: base, spec: 'd', hint: " ", attributes: { width: Grow }, moreKeys: ["6", "⁶", "₆", "$", "€", "£", "¢", "¥", "₱", "₹", "°", "÷", "∆", "†", "‡"]},
      {type: base, spec: 'f', hint: " ", attributes: { width: Grow }, moreKeys: ["7", "!icon/action_text_edit|!code/action_text_edit", "⁷", "₇", "⅞", "_", "%|%"]},
      {type: base, spec: 'g', hint: " ", attributes: { width: Grow }, moreKeys: ["8", "&", "⁸", "₈", "^", "←", "↑", "↓", "→", ">"]},
      {type: base, spec: 'h', hint: " ", attributes: { width: Grow }, moreKeys: ["!icon/action_clipboard_history|!code/action_clipboard_history", "9", "⁹", "₉", "—", "–", "-", "·", "°"]},
      {type: base, spec: 'j', hint: " ", attributes: { width: Grow }, moreKeys: ["0", "⁰", "₀", "+", "±", "=", "≠", "≈", "∞", "×", "÷"]},
      {type: base, spec: 'k', hint: " ", attributes: { width: Grow }, moreKeys: ["(", "[", "⟨", "{", "/", "|", "<", "≤", "‹", "«"]}
    ]
  - letters: [
      $shift,
      {type: gap, attributes: { width: Custom3 }},
      {type: base, spec: 'i', hint: " ", attributes: { width: Grow }, moreKeys: ["!icon/action_voice_input|!code/action_voice_input", "×", "∞", "[[]]"]},
      {type: gap, attributes: { width: Custom3 }},
      {type: base, spec: 'a', hint: " ", attributes: { width: Grow }, moreKeys: ["!icon/action_select_all|!code/action_select_all", "@", "~", "'", "!icon/tab_key|!code/key_tab", "←", "↑", "↓", "→", "*", "&"]},
      {type: gap, attributes: { width: Custom3 }},
      {type: base, spec: 'e', hint: " ", attributes: { width: Grow }, moreKeys: ["|", "—", "–", "!", "¡", "=", "≠", "≈", "…", "![[]]"]},
      {type: gap, attributes: { width: Custom3 }},
      {type: base, spec: 'o', hint: " ", attributes: { width: Grow }, moreKeys: ["∅", "ⁿ", "•", "°", "Ω"]},
      {type: gap, attributes: { width: Custom3 }},
      {type: base, spec: 'u', hint: " ", attributes: { width: Grow }, moreKeys: ["÷", "_"]},
      {type: gap, attributes: { width: Custom3 }},
      $delete
    ]
  - letters: [
      {type: base, spec: 'z', hint: " ", attributes: { width: Grow }, moreKeys: ["!icon/action_undo|!code/action_undo", "*", "%|%", "★", "†", "‡"]},
      {type: base, spec: 'x', hint: " ", attributes: { width: Grow }, moreKeys: ["!icon/action_cut|!code/action_cut", "\u0022", "×"]},
      {type: base, spec: 'c', hint: " ", attributes: { width: Grow }, moreKeys: ["'", "```", "√", "^", ":", "‚", "♣", "♠", "♥", "♦"]},
      {type: base, spec: 'v', hint: " ", attributes: { width: Grow }, moreKeys: ["!icon/action_paste|!code/action_paste", ":", "©", "®", "™"]},
      {type: base, spec: 'b', hint: " ", attributes: { width: Grow }, moreKeys: [";", "✓", "•", "·", "\u0022"]},
      {type: base, spec: 'n', hint: " ", attributes: { width: Grow }, moreKeys: ["!", "¡", "ⁿ", "№"]},
      {type: base, spec: 'm', hint: " ", attributes: { width: Grow }, moreKeys: ["?", "¿", "‽", "×", "μ", "♪", "[]()"]}
    ]
  - bottom: 
      - $symbols
      - {type: base, spec: "'", attributes: { width: Custom3 }}
      - {type: base, spec: ",", moreKeys: ["!icon/numpad|!code/key_to_number_layout", "!icon/action_voice_input|!code/action_voice_input", "!icon/action_text_edit|!code/action_text_edit", "!icon/action_select_all|!code/action_select_all", "!icon/action_clipboard_history|!code/action_clipboard_history", "!icon/action_redo|!code/action_redo", "!icon/action_cut|!code/action_cut", "!icon/action_copy|!code/action_copy", "!icon/action_paste|!code/action_paste", "!icon/action_undo|!code/action_undo"]}
      - $space
      - {type: base, spec: '.', moreKeys: ["\u0022", "?", "!", "!icon/numpad|!code/key_to_number_layout", ":", ";", "-", "—", "–", "/", "\\", "|", "#", "@", "&", "()", "[]", "{}", ">", "<", "$", "%|%", "*", "…", "°", "```", "~", "+", "=", "÷"]}
      - {type: base, spec: "'", attributes: { width: Custom3 }}
      - $enter
```
















