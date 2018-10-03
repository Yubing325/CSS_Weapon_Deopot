# Snake Loading Animations

In my [CSS loading Animations repository](https://github.com/Yubing325/LoadingAnimations) I wrote several types of loading animations for web page loading. This time I've learned a more sophisticated effect regarding the loading animations. It can be applied to game related websites.

### Summary

This effect consist of server parts, the most important two I think are the "snake" animations in which it loop over a square shape. Another part is the backgroud square roates.

So two animations (`animate` and `roate`) are being created. The four edges which consists of the path where the snake crawls are four span elements. And by setting different rotate angles and `animation-delay` times, they are acting like one snake crawling through a square path.

For the rotating of square background, it is more simple to understand. Just setting another `rotate` animation degree and duration (how fast the square can rotate). Then it's done!



# Demo

![demo of this](/img/snake_loading.gif)

Credit: Thanks to https://www.youtube.com/watch?v=MajaScL0lCs
