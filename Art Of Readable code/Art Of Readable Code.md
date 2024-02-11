# Art Of Readable Code
## _Chapter 2 : Packing Information into Names_
## Chossing Specific Words
- Specificity in naming methods or functions is crucial for clarity and understanding of code.
- Vague or ambiguous words like "get" should be avoided in method names as they don't convey the precise action being performed.
- Employing specific and descriptive names enhances code readability, maintainability, and makes it easier for other developers to understand the purpose and behavior of the code.
- 
## Avoid using Generic Names
- Names like "tmp", "retval", and "foo" are usually placeholders that indicate a lack of thought or consideration for a meaningful name.
- Instead of resorting to generic names, choose names that accurately describe the purpose or value of the entity. This enhances code readability and helps prevent misunderstandings
-  While generic names like "i", "j", and "k" are commonly used for loop iterators, consider using more precise names if it helps clarify the code and avoid bugs, especially in nested loops.
-  While there are situations where generic names can be useful, such as short-lived and temporary variables, ensure there's a valid reason for using them and strive to improve naming habits to enhance code quality over time.

## Using Concrete names instead of Abstract names 
- When naming variables, functions, or other elements, opt for concrete descriptions rather than abstract ones. This makes the purpose and functionality of the element clearer.
-  If an element needs to perform multiple tasks, avoid combining them under a single vague name. Instead, use separate, explicit names for each functionality to maintain clarity and avoid confusion.
-  Vague names can lead to misunderstanding and confusion, especially for new team members or in different contexts. Choose names that accurately convey the intended functionality or behavior.

## Attaching extra information to a name, by using a suffix or prefix
- Adding additional information to variable names can enhance readability and convey important details about the variable's content or purpose.
- When dealing with measurements like time or file size, it's beneficial to encode the units into the variable name to avoid ambiguity and ensure clarity.Examples include renaming variables like "delay" to "delay_secs", "size" to "size_mb", or "limit" to "max_kbps" to indicate the units of measurement.
## Deciding how long a name should be
- Avoid excessively long names which can be cumbersome and difficult to remember. However, don't go too far in the opposite direction by using overly short names.
- Shorter names are acceptable for variables with a smaller scope, where their purpose is immediately apparent within a limited context. Longer, more descriptive names are necessary for variables with a larger scope to ensure clarity and readability.
- Consider removing redundant words from variable names without losing important information. For example, "ConvertToString()" can be shortened to "ToString()" without sacrificing clarity.

