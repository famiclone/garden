# Unix

## Notes

### Find and replace text within a file

```sh
echo "Current shell: <SHELL>" | awk -v VAR=$SHELL '{gsub(/<SHELL>/, VAR)}1'
```

## Links
