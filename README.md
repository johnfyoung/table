# table

Experimenting with a responsive table

Tables do not work within grid frameworks and they always seem to be the culprit for breaking the layout. Scrolling is the answer but it would be nice to have a table that keeps the left column and the top row frozen so that headers and row id's are visible.

I wanted to try using layers of tables based on the same data: one for the data, one for the headers, one for the columns and one for the top left corner.

I was looking for a pure CSS solution but broke down and used a `scroll` event listener.

Note: Maybe a solution using `thead` and `tbody` set to `display: block` might work. I haven't fully explored that.
