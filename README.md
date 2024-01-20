# Default List

I copied this from [bubbletea/examples/list-default](https://github.com/charmbracelet/bubbletea/tree/master/examples/list-default)
and modified it to show 2 windows.

<img src="./correct_rendering.png" />

While playing with it I noticed that the help text ist rendered incorrectly, when the window gets to small to put everything on one line.

<img src="./line_wrap.png" />

Further reducing the width of the window makes the help widget to show an ellipsis and the rendering looks good again.

<img src="./with_ellipsis.png" />
