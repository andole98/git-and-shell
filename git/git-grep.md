On Linux

```bash
git grep -l [REGEX] | xargs sed -i "s/OLD_TEXT/NEW_TEXT/g"
```

On Mac

```bash
git grep -l [REGEX] | xargs sed -i '' -e "s/OLD_TEXT/NEW_TEXT/g"
