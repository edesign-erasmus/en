# Web animation types

While this chapter covers a little bit of basic animation principles and concepts, it is not about creating animated content (videos), but mostly how to animate UI elements with ```code```.   

But first, let's try to define web animations with a help of Dan Parry:

>In short, web animation is the visualization of change — something that starts in one state and ends in another state. The animation is how it gets from one to the other and how you handle states in between (the “interpolated states”) is what is important. 
> <br>*[Guide to making web animations UX friendly](https://dev.to/codesphere/guide-to-making-web-animations-ux-friendly-469d)*



<style>
    .animated-span {

        padding:0.25ch 1ch;
        animation: animate-bg 2s infinite alternate;
        transform: rotate(45deg);
    }
    @keyframes animate-bg {
        0% {
            background-color: hotpink;
            border-radius: 0.1ch;
        }
        100%{
            background-color: khaki;
            border-radius: 1.5ch;
        }
    }
</style>

As you probably know by now, the visual properties of UI ```<elements>``` are defined by **CSS Styles**. If you **change any of those properties** (i.e. background-color) **over time**, you've got yourself <span class="animated-span">**an&nbsp;animation**</span>


<div class="important">

So, it means, that we mostly talk about **CSS-animations**.<br>
We also cover animating with **Javascript**, but here is important to understand, that with Javascript we often just **modify the same CSS values**.
<br><small>*(NOTE: There are a few exceptions – when we modify **document** or **window** properties (like scroll position for example))*</small>

</div>


## CSS

There are two types – ***CSS-transitions*** and ***CSS-animations***. *Transition* is usually a change from **one *state* to another**, like when an object becomes active or passive. *CSS-animation* is **keyframe based** change over time, that can stop at the end or go back to beginnig, repeat itself for a couple of times or go on forever, change direction like a pendulum etc.

### Transitions
    
📌 Here is a [fantastic interactive guide of **css-transitions**](https://www.joshwcomeau.com/animation/css-transitions/) by Josh W Comeau. You'll learn about transitions and so much more from this article!


### Animations

📌 Here is another [fantastic interactive guide of **css-animation**](https://www.joshwcomeau.com/animation/keyframe-animations/) by... surprise! Josh W Comeau again!




## JavaScript animations

- Frameworks
- Tools (Lottie)

