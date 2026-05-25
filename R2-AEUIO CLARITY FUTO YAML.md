This is the FUTO YAML for the "CLARITY" version of the Vowel Vortex layout. 

The numbers remain on the consonants. 

```
name: Vowel Vortex Clarity
description: Vowel Vortex layout for FUTO Keyboard
overrideWidths:
  Custom1: 0.143        # Consonants
  Custom2: 0.01         # not used
  Custom3: 0.0375       # gaps
  Custom4: 0.17         # Vowels
  FunctionalKey: 0.143  # function key
rows:
  - letters: [
      {type: base, spec: 'q', hint: " ", attributes: { width: Custom1 }, moreKeys: ["~", "\u0022", "?", "¿"]},
      {type: base, spec: 'w', hint: " ", attributes: { width: Custom1 }, moreKeys: ["1", "`", "¹", "₁", "½", "⅓", "¼", "⅕", "⅙", "⅐", "⅛", "⅑", "⅒"]},
      {type: base, spec: 'r', hint: " ", attributes: { width: Custom1 }, moreKeys: ["2", "²", "₂", "⅔", •, "⅖"]},
      {type: base, spec: 't', hint: " ", attributes: { width: Custom1 }, moreKeys: ["3", "`", "~", "×", "¾", "³", "₃", "⅗", "⅜"]},
      {type: base, spec: 'y', hint: " ", attributes: { width: Custom1 }, moreKeys: ["!icon/action_redo|!code/action_redo", "4", "π", "⁴", "₄", "⅘"]},
      {type: base, spec: 'p', hint: " ", attributes: { width: Custom1 }, moreKeys: ["5", "!icon/numpad|!code/key_to_number_layout", "⁵", "₅", "⅚", "=", "⅝", "|", "%|%", "‰", "π", "Π", "+", "±", "#", "₊", "⁺"]},
      {type: base, spec: 'l', hint: " ", attributes: { width: Custom1 }, moreKeys: [")", "]", "⟩", "}", "\\", "|", ">", "≥", "›", "»"]}
    ]
  - letters: [
      {type: base, spec: 'a', hint: " ", attributes: { width: Custom4 }, moreKeys: ["!icon/action_select_all|!code/action_select_all", "!icon/tab_key|!code/key_tab", "@", "~", "→", "←", "↑", "↓", "'", "*", "&"]},
       {type: gap, attributes: { width: Custom3 }},
      {type: base, spec: 'e', hint: " ", attributes: { width: Custom4 }, moreKeys: ["!icon/action_text_edit|!code/action_text_edit", "—", "–", "!", "¡", "=", "≠", "≈", "…", "![[]]"]},
       {type: gap, attributes: { width: Custom3 }},
      {type: base, spec: 'u', hint: " ", attributes: { width: Custom4 }, moreKeys: ["_", "÷"]},
       {type: base, spec: "'", attributes: { width: Custom3 }},
      {type: base, spec: 'i', hint: " ", attributes: { width: Custom4 }, moreKeys: ["!icon/action_voice_input|!code/action_voice_input", "×", "∞", "[[]]"]},
       {type: gap, attributes: { width: Custom3 }},
      {type: base, spec: 'o', hint: " ", attributes: { width: Custom4 }, moreKeys: ["°", "ⁿ", "•", "∅", "Ω"]},
    ]
  - letters: [
      {type: base, spec: 's', hint: " ", attributes: { width: Custom1 }, moreKeys: ["#", ";", "№", "§", "★", "¶"]},
      {type: base, spec: 'd', hint: " ", attributes: { width: Custom1 }, moreKeys: ["6", "$", "⁶", "₆", "€", "£", "¢", "¥", "₱", "₹", "°", "÷", "∆", "†", "‡"]},
      {type: base, spec: 'f', hint: " ", attributes: { width: Custom1 }, moreKeys: ["7", "⁷", "₇", "_", "⅞", "%|%"]},
      {type: base, spec: 'g', hint: " ", attributes: { width: Custom1 }, moreKeys: ["8", "⁸", "&", "₈", "^", "←", "↑", "↓", "→", ">"]},
      {type: base, spec: 'h', hint: " ", attributes: { width: Custom1 }, moreKeys: ["!icon/action_clipboard_history|!code/action_clipboard_history", "⁹", "9", "₉", "—", "-", "–"]},
      {type: base, spec: 'j', hint: " ", attributes: { width: Custom1 }, moreKeys: ["0", "⁰","₀", "+", "±", "=", "≠", "≈", "∞", "×", "÷", "°", "·"]},
      {type: base, spec: 'k', hint: " ", attributes: { width: Custom1 }, moreKeys: ["(", "[", "⟨", "{", "/", "|", "<", "≤", "‹", "«"]}
    ]
  - letters: [
      $shift,
      {type: base, spec: 'z', hint: " ", moreKeys: ["!icon/action_undo|!code/action_undo", "*", "%|%", "★", "†", "‡"]},
      {type: base, spec: 'x', hint: " ", moreKeys: ["!icon/action_cut|!code/action_cut", "\u0022", "×"]},
      {type: base, spec: 'c', hint: " ", moreKeys: [      "!icon/action_copy|!code/action_copy", "'", ",", ":", "```", "√", "^"]},
      {type: base, spec: 'v', hint: " ", moreKeys: ["!icon/action_paste|!code/action_paste", ":", "©", "®", "™"]},
      {type: base, spec: 'b', hint: " ", moreKeys: [";", "✓", "•", "·", "\u0022"]},
      {type: base, spec: 'n', hint: " ", moreKeys: ["!", "¡", "ⁿ", "№"]},
      {type: base, spec: 'm', hint: " ", moreKeys: ["?", "¿", "‽", "×", "μ", "♪", "[]()"]},
      $delete
    ]
  - bottom: 
      - $symbols
      - $action
      - {type: base, spec: ",", moreKeys: [
      "!icon/action_voice_input|!code/action_voice_input", 
      "!icon/action_clipboard_history|!code/action_clipboard_history", 
      "!icon/action_text_edit|!code/action_text_edit", 
      "!icon/numpad|!code/key_to_number_layout", 
      "!icon/action_select_all|!code/action_select_all", 
      "!icon/action_cut|!code/action_cut", 
      "!icon/action_copy|!code/action_copy", 
      "!icon/action_paste|!code/action_paste", 
      "!icon/action_redo|!code/action_redo", 
      "!icon/action_undo|!code/action_undo"]}
      - $space
      - {type: base, spec: '.', moreKeys: ["\u0022", "?", "!", "!icon/numpad|!code/key_to_number_layout", ":", ";", "-", "—", "–", "/", "\\", "|", "#", "@", "&", "()", "[]", "{}", ">", "<", "$", "%|%", "*", "…", "°", "```", "~", "+", "=", "÷", "(", ")", "'", ",", "]", "["]}
      - $enter
```
