# morbid-fortune

Prints fortunes based on DoT railroad casualties reports

## Usage

```
rcj@mcflurry🍦:~$ ./morbid-fortune
AS A RESULT OF A PASSENGER FATALITY  THIS EMPLOYEE WAS REQUESTED TO LOOK FOR HUMAN REMAINS ALONG THE ROADBED.  AS A RESULT OF HIS WORK  HE SUFFERED STRESS AFTER HIS ASSIGNMENT.
```

## Caveats

The data is quite messy (optional fields) so the output could just be wrong.
I am using a dumb heuristic to get things that look like long form text (any
field with more than eight characters)
