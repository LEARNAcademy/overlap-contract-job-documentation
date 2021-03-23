# Style Guidelines for the LEARN Syllabus

### Markdown Syntax Reference
- Headers 1-6 `# Header1 ## Header2` etc.
- Unordered list `-` (dash)
- Inline code snippets `` (single backticks)
- Code block ``` (three backticks on the line before and after snippet)
- Bold `**words**`
- Italics `*words*`


### Overall
- Check all links, images, videos
- Check that all code snippets are accurate
- Check for typos, grammar mistakes, misspelled words
- Check for cohesive flow and continuity
- Check for descriptive variable names
- Add learning objects
- Ensure learning objectives are covered by the code explanation and snippets
- Ensure learning objectives are covered by the code challenges
- Check all vocabulary words are listed

### General
- Text instructions are written in first person plural
- Language and framework names are capitalized - JavaScript, React, Ruby, Rails, PostgreSQL, etc
- Terminal commands, code syntax, references to code terminology are wrapped in single back ticks in line
  - Example: Notice that in our loops we use `let` to assign `i` or `index` to a starting value.
- Code snippets are wrapped in three back ticks and styled with the language when appropriate
  - language name is in lowercase
  - ` ```javascript`
  - Example:

  ```javascript
  var arr = [5, 3, 5, 2, 5, 7]

  for(let i=0; i<arr.length; i++){
    if(arr[i] !== 5){
      console.log(arr[i])
    }      
  }
  ```
- Full file path in bold above code snippets `**src/App.js**`


### Structure
- Title contains the language or framework name and is styled with `#`
- `##### Overview` is written in complete sentences
- `##### Previous Lecture (time of video)`

  ```
  [![YouTube](http://img.youtube.com/vi/Bj3li2W6yks/0.jpg)](https://www.youtube.com/watch?v=Bj3li2W6yks)
  - replace: Bj3li2W6yks in both sections
  ```
- `##### Learning Objectives` are a bulleted list taken from LEARN learning objectives doc and reframed as needed (`- can ...`)
- `##### Vocabulary` is a bulleted list with terms in lowercase unless otherwise necessary (eg React)
  - Each vocab work should be defined within the body of the section
  - When the vocab word is defined it should be bold
  - Vocab words should be listed in the order in which they are defined
- `##### Additional Resources`

  ```
  - [ W3Schools JavaScript Arrays ](https://www.w3schools.com/js/js_arrays.asp)
  ```
- `##### Process` instructions for creating the project/file and running the code/application

### JavaScript
- The J and the S are capitalized: `JavaScript`
- JavaScript uses double quotes `""`
- No semicolons unless necessary
- Spaces around JS operators
  - Example: `8 + 5`
- Single space before curly braces in code blocks
  - Example:
  ```javascript
  if(5 > 3) {
    return "output"
  }

  const functionExample = (array) => {
    return "output"
  }
  ```
