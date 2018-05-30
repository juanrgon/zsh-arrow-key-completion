Search through history for previous commands matching everything up to current cursor position. Move the cursor to the end of line after each match.

Example:
`[]` indicates the current cursor position. With the partial command:

```sh
$ rbenv exec[]
```
We want up arrow keypresses to result in:

```sh
$ rbenv exec rake generate[]
$ rbenv exec rake preview[]
```
and down arrow keypresses to result in:

```sh
$ rbenv exec rake preview[]
$ rbenv exec rake generate[]
$ rbenv exec[]
```
