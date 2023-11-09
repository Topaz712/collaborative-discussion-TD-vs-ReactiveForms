Some key take-aways I got from using template-driven and reactive forms is that it mostly comes down to preference

### Template Driven Forms

- Handles dynamic form scenarios, like disabling/enabling fields based on conditions and handling dynamic lists

  - They can be harder to unit test because the form logic is contained within the templates

- Simplicity and efficiency, "easy way" for practical, efficient development like when we gather user data with Angular's provided validation

- Can primarily use the template for form work but still have the option to access the reactive forms API through references to NgControl/NgForm if needed

### Reactive Forms

- Keeps as much code in the Typescript file and less in HTML

- Recommended for scalability, but they come with complexities

- Recommended for large projects with complex forms and validations because of it's flexibility and the ability to control elements according to specific requirements

- Reactive forms are built around observable streams, treating form inputs and values like flowing streams of input data
  - This allows for easy synchronous access, it make testing straightforward by ensuring that our data is consistent and predictable when needed/requested

### My conclusion

So basically, template-driven forms are simpler to use and need less code, but they provide less flexibility and control

On the other hand, reactive forms are more powerful, offering greater control over form behavior, but they require more code and are more complex to set up and use
