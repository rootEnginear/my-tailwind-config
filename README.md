# My Tailwindcss Config

After using Tailwindcss for half a year, this is the common configuration I used, so hopefully I can save some time for copy-pasting it.

## Config Explanation

### Font Family

I just use my personal go-to font stacks, which I don't remember where I got them from.

### Colors

- `transparent` should be included in Tailwindcss (the pratice is, if possible, use the `color/0` syntax)
- `current` can be very useful with SVGs

### Line Height

`snug`? `relaxed`? c'mon the number will do

- `1.5` is pretty standard
- `1.6` for better Thai readability
- `1` is for buttons

### Spacing

The number should reflect **its distance in PX. PERIOD.** Using `rem` can cause side-effects when changing the root `font-size`.

- `ul.list-disc.ml-list` is aligned super well. I'll investigate this phenomenal later.

### Etc

Others are pretty straightforward. ¯\\\_(ツ)\_/¯

## CSS Explanation

### Base

- `relative` everything is very useful in everyway
- `tabular-nums` is a big hit for me

### Utilities

- `nobr`: I just love the old `<nobr>` tag. It's quicker than `whitespace-nowrap` too.
