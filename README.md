# bash-bites 🍪

Small, readable Bash snippets for normal people.  
No cryptic one-liners, just tools that do what they promise.

> Replace text in strings OR files with one simple command.
> `cat file.txt | REPLACE search replace`

## Why bash-bites?

- **Readable** - No regex rage, just functions that do what they say
- **Learnable** - Understand your code, become a better Bash writer
- **Free & Open** - MIT licensed, always

## Examples

```bash
# Replace "world" with "everyone" in a string
REPLACE "Hello world" world everyone

# Replace "old" with "new" in a file (via pipe)
cat document.txt | REPLACE old new

# Replace multiple lines at once
cat my_life_story.txt | REPLACE 'This guy used to be punk
and anarchist' 'This guy now has a job
and goes fishing'

# More snippets coming soon...
