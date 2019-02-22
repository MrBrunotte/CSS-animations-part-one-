# CSS Animations

## Keyframes and animation properties

### What are they?

They are CSS3 animation properties

### What do they do?

They customize the animation

### How do you use them?

By setting the appropriate value for such properties.


#### Keyframe basics 1
The keyframes always come with the vendor prefixes: -webkit, -moz, -ms, -o,
We use @media for media queries, but now we are building an animation so no we use the @keyframe!

We use a keyframes keyword, we give it an identifier, we set a duration time, we refer to that identifier 
in our target rule (.box), and we can also add additional supporting functions in order to carry out our animations.

#### Keyframe basics 2
The value for the animation-name and the name of the keyframe for that animation must match.
Numbers and special characters cannot be the first character in the name of the animation. If the animation-name is 
not set at all, the animation will not happen. If the animation-duration property is missing, the animation is still
going to happen. In that case, the default value will be used, and that is 0 seconds. Therefore that animation will
be instant. It will happen, but so fast that we will not be able to see it. The animation-timing-functions is applied
at the beginning and the end of the keyfram.