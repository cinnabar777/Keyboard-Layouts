This is a loaded version of the layout for FUTO, easier to delete stuff than add. I have added gaps between the vowels to increase clarity, seemed to help. There were several issues with building this layout, the biggest was getting the different keys correctly sized. Overall this version, vowels on row 3, works well once you get the shift and delete key sized correctly, though it takes a little adjustment not to hit the m key when deleting. 

I've hidden the hint for all keys to help focus on learning the new layout. 

There is an apostrophe on each side, using the tiny vowel gap. Gesturing to them works for contractions etc. 

```
name: Vowel Vortex Final
description: Vowel Vortex layout for FUTO Keyboard
overrideWidths:
  Custom1: 0.14    # Consonants
  Custom2: 0.11    # not used
  Custom3: 0.02    # gap between vowels
  Custom4: 0.104   # Vowels (0.104 * 5 = 0.52)
  FunctionalKey: 0.2   # Sets $shift and $delete to exactly 0.2 width
rows:
  - letters: [
      {type: base, spec: 'q', hint: " ", attributes: { width: Custom1 }, moreKeys: ["~", "\u0022", "?", "¿"]},
      {type: base, spec: 'w', hint: " ", attributes: { width: Custom1 }, moreKeys: ["1", "`", "¹", "₁", "½", "⅓", "¼", "⅕", "⅙", "⅐", "⅛", "⅑", "⅒"]},
      {type: base, spec: 'r', hint: " ", attributes: { width: Custom1 }, moreKeys: ["2", "•", "²", "₂", "⅔", "⅖"]},
      {type: base, spec: 't', hint: " ", attributes: { width: Custom1 }, moreKeys: ["3", "`", "³", "₃", "¾", "⅗", "⅜", "√", "~", "×"]},
      {type: base, spec: 'y', hint: " ", attributes: { width: Custom1 }, moreKeys: ["!icon/action_redo|!code/action_redo", "4", "π", "⁴", "₄", "⅘"]},
      {type: base, spec: 'p', hint: " ", attributes: { width: Custom1 }, moreKeys: ["!icon/numpad|!code/key_to_number_layout", "5", "⁵", "₅", "⅚", "⅝", "=", "|", "%|%", "‰", "π", "Π", "+", "±", "₊", "⁺", "#"]},
      {type: base, spec: 'l', hint: " ", attributes: { width: Custom1 }, moreKeys: [")", "]", "⟩", "}", "\\", "|", ">", "≥", "›", "»"]}
    ]
  - letters: [
      {type: base, spec: 's', hint: " ", attributes: { width: Custom1 }, moreKeys: ["#", "№", "§", "★", "¶", ";"]},
      {type: base, spec: 'd', hint: " ", attributes: { width: Custom1 }, moreKeys: ["6", "⁶", "₆", "$", "€", "£", "¢", "¥", "₱", "₹", "°", "÷", "∆", "†", "‡"]},
      {type: base, spec: 'f', hint: " ", attributes: { width: Custom1 }, moreKeys: ["7", "!icon/action_text_edit|!code/action_text_edit", "⁷", "₇", "⅞", "_", "%|%"]},
      {type: base, spec: 'g', hint: " ", attributes: { width: Custom1 }, moreKeys: ["8", "&", "⁸", "₈", "^", "←", "↑", "↓", "→", ">"]},
      {type: base, spec: 'h', hint: " ", attributes: { width: Custom1 }, moreKeys: ["!icon/action_clipboard_history|!code/action_clipboard_history", "9", "⁹", "₉", "—", "–", "-", "·", "°"]},
      {type: base, spec: 'j', hint: " ", attributes: { width: Custom1 }, moreKeys: ["0", "⁰", "₀", "+", "±", "=", "≠", "≈", "∞", "×", "÷"]},
      {type: base, spec: 'k', hint: " ", attributes: { width: Custom1 }, moreKeys: ["(", "[", "⟨", "{", "/", "|", "<", "≤", "‹", "«"]}
    ]
  - letters: [
      $shift,
      {type: base, spec: 'i', hint: " ", attributes: { width: Custom4 }, moreKeys: ["!icon/action_voice_input|!code/action_voice_input", "×", "∞", "[[]]"]},
      {type: gap, attributes: { width: Custom3 }},
      {type: base, spec: 'a', hint: " ", attributes: { width: Custom4 }, moreKeys: ["!icon/action_select_all|!code/action_select_all", "@", "~", "'", "!icon/tab_key|!code/key_tab", "←", "↑", "↓", "→", "*", "&"]},
      {type: gap, attributes: { width: Custom3 }},
      {type: base, spec: 'e', hint: " ", attributes: { width: Custom4 }, moreKeys: ["|", "—", "–", "!", "¡", "=", "≠", "≈", "…", "![[]]"]},
      {type: gap, attributes: { width: Custom3 }},
      {type: base, spec: 'o', hint: " ", attributes: { width: Custom4 }, moreKeys: ["∅", "ⁿ", "•", "°", "Ω"]},
      {type: gap, attributes: { width: Custom3 }},
      {type: base, spec: 'u', hint: " ", attributes: { width: Custom4 }, moreKeys: ["÷", "_"]},
      $delete
    ]
  - letters: [
      {type: base, spec: 'z', hint: " ", attributes: { width: Custom1 }, moreKeys: ["!icon/action_undo|!code/action_undo", "*", "%|%", "★", "†", "‡"]},
      {type: base, spec: 'x', hint: " ", attributes: { width: Custom1 }, moreKeys: ["!icon/action_cut|!code/action_cut", "\u0022", "×"]},
      {type: base, spec: 'c', hint: " ", attributes: { width: Custom1 }, moreKeys: ["```", "♣", "♠", "♥", "♦", "√", "^", ":", "‚"]},
      {type: base, spec: 'v', hint: " ", attributes: { width: Custom1 }, moreKeys: ["!icon/action_paste|!code/action_paste", ":", "©", "®", "™"]},
      {type: base, spec: 'b', hint: " ", attributes: { width: Custom1 }, moreKeys: [";", "✓", "•", "·", "\u0022"]},
      {type: base, spec: 'n', hint: " ", attributes: { width: Custom1 }, moreKeys: ["!", "¡", "ⁿ", "№"]},
      {type: base, spec: 'm', hint: " ", attributes: { width: Custom1 }, moreKeys: ["?", "¿", "‽", "×", "μ", "♪", "[]()"]}
    ]
  - bottom: 
      - $symbols
      - {type: base, spec: "'", hint: " ", attributes: { width: Custom3 }, moreKeys: ["!icon/action_clipboard_history|!code/action_clipboard_history", "!icon/action_text_edit|!code/action_text_edit", "!icon/action_select_all|!code/action_select_all", "!icon/numpad|!code/key_to_number_layout", "!icon/action_voice_input|!code/key_to_number_layout", "!icon/action_redo|!code/action_redo", "!icon/action_cut|!code/action_cut", "!icon/action_copy|!code/action_copy", "!icon/action_paste|!code/action_paste", "!icon/action_undo|!code/action_undo"]}
      - {type: base, spec: ",", moreKeys: ["!icon/action_clipboard_history|!code/action_clipboard_history", "!icon/action_text_edit|!code/action_text_edit", "!icon/action_select_all|!code/action_select_all", "!icon/numpad|!code/key_to_number_layout", "!icon/action_voice_input|!code/key_to_number_layout", "!icon/action_redo|!code/action_redo", "!icon/action_cut|!code/action_cut", "!icon/action_copy|!code/action_copy", "!icon/action_paste|!code/action_paste", "!icon/action_undo|!code/action_undo"]}
      - $space
      - {type: base, spec: '.', moreKeys: ["\u0022", "?", "!", "!icon/numpad|!code/key_to_number_layout", ":", ";", "-", "—", "–", "/", "\\", "|", "#", "@", "&", "()", "[]", "{}", ">", "<", "$", "%|%", "*", "…", "°", "```", "~", "+", "=", "÷"]}
      - {type: base, spec: "'", hint: " ", attributes: { width: Custom3 }, moreKeys: ["!icon/action_clipboard_history|!code/action_clipboard_history", "!icon/action_text_edit|!code/action_text_edit", "!icon/action_select_all|!code/action_select_all", "!icon/numpad|!code/key_to_number_layout", "!icon/action_voice_input|!code/key_to_number_layout", "!icon/action_redo|!code/action_redo", "!icon/action_cut|!code/action_cut", "!icon/action_copy|!code/action_copy", "!icon/action_paste|!code/action_paste", "!icon/action_undo|!code/action_undo"]}
      - $enter
```
