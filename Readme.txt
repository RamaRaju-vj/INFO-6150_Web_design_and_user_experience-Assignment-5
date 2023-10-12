variables : Implemented in _variable.scss

place holder 
%button-style: _placeholders.scss
%common-card-styles: _animated-grid.scss

Interpolation: 
#{$stagger-delay} used in _animated-grid.scss

Nesting:
.pricing-container, .pricing-container2 {} used in _base.scss


@mixin & @include : 
@include keyword is used to include the code written in a mixin block in _buttons.scss

@extend: inheriting from %common-card-styles in _animated-grid.scss

@function double($value) used in _funtions.scss and functions are called from _base.scss

media quries : added in _animated-grid.scss & _base.scss for responsive website

@at-root Directive: allows you to control the output location of a rule. It's handy for breaking out of nested contexts(in container class)

function Directives: function add($a, $b) to encapsulate logic and calculations and are called from _base.scss

operators: (+,*) used in _base.scss

custom property: changed the button colour to green in custom button class in _base.scss

@keyframes : animation effect, used in _animated-grid.scss






