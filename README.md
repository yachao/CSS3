# CSS3
DEMOS ABOUT:

### CSS3 Transform
```css
transform: none | <transform-function> [<transform-function>]*
transform: rotate | scale | skew | translate | matrix | rotate3d | scale3d | translate3d(tx,ty,tz) | matrix3d | perspective

transform-origin: [<percentage> | <length> | left | center | right | top | bottom] | [<percentage> | <length> | left | center | right] | [[<percentage> | <length> | left | center | right] && [<percentage> | <length> | top | center | bottom]] <length> ?
(1)transform-origin:(left,top)
(2)transform-origin:right
(3)transform-origin(25%,75%)
```
### CSS3 Transtion
```css
transition ： [<'transition-property'> || <'transition-duration'> || <'transition-timing-function'> || <'transition-delay'> [, [<'transition-property'> || <'transition-duration'> || <'transition-timing-function'> || <'transition-delay'>]]*
transition-property ： none | all | [ <IDENT> ] [ ',' <IDENT> ]*
transition-duration ： <time> [, <time>]*
transition-timing-function ： ease | linear | ease-in | ease-out | ease-in-out | cubic-bezier(<number>, <number>, <number>, <number>) [, ease | linear | ease-in | ease-out | ease-in-out | cubic-bezier(<number>, <number>, <number>, <number>)]*
transition-delay ： <time> [, <time>]*
```
### CSS3 Animation
```css
keyframes-rule: '@keyframes' IDENT '{' keyframes-blocks '}';
keyframes-blocks: [ keyframe-selectors block ]* ;
keyframe-selectors: [ 'from' | 'to' | PERCENTAGE ] [ ',' [ 'from' | 'to' | PERCENTAGE ] ]*;

@keyframes IDENT {
 from {
   Properties:Properties value;
 }
 Percentage {
   Properties:Properties value;
 }
 to {
   Properties:Properties value;
 }
}
or：
@keyframes IDENT {
  0% {
     Properties:Properties value;
  }
  Percentage {
     Properties:Properties value;
  }
  100% {
     Properties:Properties value;
  }
}

animation:[<animation-name> || <animation-duration> || <animation-timing-function> || <animation-delay> || <animation-iteration-count> || <animation-direction>] [, [<animation-name> || <animation-duration> || <animation-timing-function> || <animation-delay> || <animation-iteration-count> || <animation-direction>] ]*
animation-name: none | IDENT[,none | IDENT]*
animation-duration: <time>[,<time>]*
animation-timing-function:ease | linear | ease-in | ease-out | ease-in-out | cubic-bezier(<number>, <number>, <number>, <number>) [, ease | linear | ease-in | ease-out | ease-in-out | cubic-bezier(<number>, <number>, <number>, <number>)]*
animation-delay: <time>[,<time>]*
animation-iteration-count:infinite | <number> [, infinite | <number>]*
animation-direction: normal | alternate [, normal | alternate]*
animation-play-state:running | paused [, running | paused]*
```
### FLEXBOX
```css
display: flex | inline-flex
flex-flow: <flex-direction> <flex-wrap>
     <flex-direction>    row | row-reverse | column | column-reverse
     <flex-wrap>         nowrap | wrap | wrap-reverse
align-items: flex-start/baseline | flex-end | center | stretch
justify-content: flex-start | flex-end | center | space-between | space-around
align-content: flex-start | flex-end | center | space-between | space-around | stretch
order:  <number>
flex:  <flex-grow> <flex-shrink> <flex-basis>
```
