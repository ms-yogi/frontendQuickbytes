![Frontend QuickBytes](bg.png)

# frontendQuickbytes

This reepository contains real life frontend challenges which you can use to practice frontend! You can use any framework/library to solve these challenges. These are created for the fun and practice purpose to go beyond to-dos.

If you like these challenges, would appriciate getting a star 🌟

You can also contribute to these challenge list or share your solutions. We can create a solutions section too for those links!

Here is the list of all challenges -

1. [**Count your words**: Twitter like textarea with character count](count-your-words)
2. [**Dropdown Component with select/multiselect feature** - Similar to React Select](dropdown-component)
3. [**Autosuggest Input**](autosuggest-input)

## Count your words

Twitter like textarea with character count

If you have ever used twitter, you must know your tweet will have a character count limit of 280 characters and once you cross that character limit twitter starts marking your characters with red background and you will see a character count going in a negative value! That's it, that is the task. You can build the same textarea with a customised character count limit.

Features to include in it -

1. Create a simple textarea and add neceessary styling.
2. There should be a customisable character count limit to your textarea.
3. Show this limit below the textarea. _Improvement - You can add progress circle showing the count._
4. If characcters goees beyond the limit, highlight them, decrease the count to negative value and disable the submit button.
5. You can also add warnings when only 10% character limit is remaining.
6. If a user is adding symbols such as `@` or `#` made them as a link with relevant href.
7. After a submit button, display that paragraph.

## Dropdown Component

A component with select/multiselect featuee, similar to [React Select](https://react-select.com/home)

Dropdowns are part of most applications and they are smart to implement components. [React Select](https://react-select.com/home) is one of those libraries which I heavily trust on for any type of dropdown I need. But while learning if we can create a simple dropdown component, it will have so many benefits over going for the library.

Features to include in it -

1. Dropdown component, where list will be open on click of dropdown.
2. This list should get closed on clicking the dropdown again, on pressing `esc` key, on clicking outside and after selecting any element.
3. Enable multiselect option as well.
4. Search function on type will be a bonus.

## Autosuggest Input

We all have tried Google search input. It's pretty cool how it shows you some suggestions based on your typing. We need to create exactly the same. Consider a search location feature, where you are adding name if your city and country. Implement a search feature with list of cities and countries and show user options based on what the user is typing.

Features to include in it -

1. A search input with autosuggest option.
2. Enable debouncing feature to save excess api calls.
3. Use any api or json list to show suggestions
