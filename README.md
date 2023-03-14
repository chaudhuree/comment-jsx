# comment-jsx
>in vs code press ctrl+k+s and paste this code

```json
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
