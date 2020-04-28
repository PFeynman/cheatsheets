# Pirobits Cheatsheets 

Community-driven cheatsheets and documentation for developers. Quickly find the commands you need for programming.

- [Pirobits Cheatsheets (English)](https://pirobits.com/cheatsheets)
- [Pirobits Cheatsheets (Español)](https://pirobits.com/es/cheatsheets)

## How to contribute

Contributing to Pirobits Cheatsheets is as easy as forking this repository, filling a JSON file and open a PR. You can either add new snippets to the existing categories or add new categories too. Feel free to add your name on the collaborator section of this file.

### Update a cheatsheet

If you want to add a snippet to the existing cheatsheets, go to the JSON file of the category it belongs to, and at the end, add your contribution. It must have the following format:

```
{
  "title_es": "...",    # The general purpose of these snippets, in Spanish
  "title_en": "...",    # The general purpose of these snippets, in English
  "snippets": [
    {
      "commands": ["..."],  # All the commands that have a similar functionality
      "usages": ["..."],    # Some usage examples, if you can give any
      "description_es": "...",  # The purpose of these commands, in Spanish
      "description_en": "..."   # The purpose of these commands, in English
    }
  ]
}
```

You can also add new snippets in the existing groups too. 

**If you don't speak English or Spanish, fill the title and description of the language you know and we will translate it for you. **

### Adding a new cheatsheet

If, on the other hand, you prefer to add new cheatsheets, add a new JSON file, named with the name of the category you want to add and give it the following format:

```
{
  "category": "...", # The category of the cheatsheet. It must be the same as the name of the file. 
  "groups": []  # Here you can add your snippets, as explained above. 
}
```

## Collaborators

-  [Alberto Sola (pirobtumen)](https://github.com/pirobtumen)
-  Your name, GitHub username and link (optional) 
