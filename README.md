# comment-jsx
keybinding code for jsx file commenting
in vs code press ctrl+k+s and paste this code
```
[
  {
    "key": "shift+alt+a",
    "command": "editor.action.insertSnippet",
    "args": {
      "snippet": "{/*\n ${TM_SELECTED_TEXT} \n*/}$0"
    },
    "when": "editorLangId == 'javascript' && editorTextFocus && !editorReadonly"
  }
]
```
