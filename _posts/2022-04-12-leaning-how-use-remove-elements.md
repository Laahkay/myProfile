---
Layout:
Title: "SASS"
Date: "2022-04-12"
---

# INTRODUCTION

I went to another topic of the curriculam and done this topic as follows,
I started with Store data Sass Variables , nest CSS with Sass , Create Reusable CSS with Maxins and lastly HOw to Use @if and @else to Add Logic To Your Styles.

# Body 

How to store data with Sass is that we variables are defined using the let and const for example ,

h1 {
  font-family: $main-fonts;
  color: $headings-color;
}
thats how we set some colors to our text when  we are using Sass so we use the dollar sign to set our colors because without that we wont be able to set our colors if the dollar sign is not there, and after i went to another test which is How to NEst CSS with Sass but then in Sass we normally target element on different line to style them sor example 

nav {
  background-color: red;

  ul {
    list-style: none;

    li {
      display: inline-block;
    }
  }
}
that how we target them but should make sure that you have targeted the right text or inlines, And learned about How to create Reusable CSS with MIxins  so Mixin is a group of CSS declarations so that it can be Reused thoughout the style sheet so here we start with @mixin and also should be folloed by the parameters $x, $y, $blur, and $c, but we where asked to write a mixin for border-radius and give it a $radius paremeter and set it capacity ti 15px., My last test for the day was How to Use @if and @else to Add Logic To Your Styles so The @if directive in Sass is useful to test for a specific case - it works just like the if statement in JavaScript so that it can test for more conditions like in JS here is an example coming from freecode camp 

@mixin make-bold($bool) {
  @if $bool == true {
    font-weight: bold;
  }
}
And how to test @else if and @else for more conditions:

@mixin text-effect($val) {
  @if $val == danger {
    color: red;
  }
  @else if $val == alert {
    color: yellow;
  }
  @else if $val == success {
    color: green;
  }
  @else {
    color: black;
  }
}
 that was mast task for the day.

 # Conclusion 

 I have notice that Sass does not differ that much to CSS styling but then the difference is that here we use doller sign$ and @dign  to style our texts as for our parameters are been controlled by the condions of Sass styling..