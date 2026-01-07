# freecodecamp-pin-extractor

Simple Python exercise: extract PINs from poems.

## Description

**pin_extractor(poems)** should accept a list of multiline strings (poems) and return a list of PIN strings. For each poem, the function takes the 1st word of line 1, the 2nd word of line 2, the 3rd word of line 3, etc., and uses the length of that word as the next digit. If a required word is missing on a line, the function should append `0` for that position.

