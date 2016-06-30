# Coding Style

Ajouter le fichier .editorconfig à la racine de votre projet pour forcer le coding style dans votre IDE.

Sur PHPStorm, installer le plugin : https://plugins.jetbrains.com/plugin/7294

```
; top-most EditorConfig file
root = true

; Unix-style newlines
[*]
charset = utf-8
end_of_line = LF
trim_trailing_whitespace = true
insert_final_newline = true
indent_style = space

[*.{yml,php,twig,html}]
indent_size = 4

[*.{css,less,js,json}]
indent_size = 2
```
