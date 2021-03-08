# 2021-03-07 [Day 1]

## Today I learned : How to ignore `prettier` in `Markdown`

1. what is `prettier`?

- Click[here](https://prettier.io/docs/en/index.html)

1. Use `.prettierignore`
   
- what I wanted : to ignore `prettier` in `Markdown`
- what I did : 
  - I made `.prettierignore` on the same directory
  - and then, put code like this in the `.prettierignore` file
  ```
    <!-- all .md file will be ignoring prettier extension in Markdown -->
  
  *.md
  ```

  - I didn't want to be tracking in my github
  - so, I made `.gitignore` file and added `.prettierignore`
  