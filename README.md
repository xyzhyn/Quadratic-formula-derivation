# Quadratic formula derivation

<p>
  Every $2nd$ degree polynomial can be expressed using this formula:<br>

  $ax^{2} + bx + c = 0$

  Deriving the $solution(s)$ aka finding the $x(s)$.
  
  $\displaystyle ax^{2} + bx = - c$<br>
  $\displaystyle x^{2} + \frac{bx}{a} = - \frac{c}{a}$<br>
  $\displaystyle x^{2} + \frac{b}{a}(x) = - \frac{c}{a}$<br>

  We can see the left part as a portion of **the result** of a $2nd$ power binomial, then add the rest and 
  therefore add the same 
  quantity to the right part of the equation. This (not intuitive) intuition will let us remove the $1st$ 
  degree power of $x$, which is the biggest problem here. To be completely clear:

  $(x + c)^{2} = (x + c)(x + c) = x^{2} + cx + cx + c^{2} = x^{2} + (2)cx + c^{2}$

  Now:
  
  $\displaystyle x^{2} + \frac{b}{a}(x) + (\frac{b}{2a})^{2} = - \frac{c}{a} + (\frac{b}{2a})^{2}$<br>
  $\displaystyle (x + \frac{b}{2a})^{2} = - \frac{c}{a} + (\frac{b}{2a})^{2}$<br>
  $\displaystyle (x + \frac{b}{2a})^{2} = - \frac{c}{a} + \frac{b^{2}}{4a^{2}}$<br>
  $\displaystyle (x + \frac{b}{2a})^{2} = \frac{b^{2} - 4ac}{4a^{2}}$<br>
  
  Adding a little bit of chilly powder like Jesse Pinkman:

  $(xz)^{2} = (xz)(xz) = (x)(x)(z)(z) = x^{2}z^{2}$<br>
  $\displaystyle (\frac{x}{z})^{2} = \frac{(x)}{(z)} \times \frac{(x)}{(z)} = \frac{(x)(x)}{(z)(z)} = \frac{x^{2}}{z^{2}}$<br>
  $\sqrt{(xz)^{2}} = \pm xz = \sqrt{x^{2}}\sqrt{z^{2}}$<br>
  $\displaystyle \sqrt{(\frac{x}{z})^{2}} = \pm \frac{x}{z} = \frac{\sqrt{x^{2}}}{\sqrt{z^{2}}}$<br>

  Ok let's conclude:

  $\displaystyle x + \frac{b}{2a} = \pm \frac{\sqrt{b^{2} - 4ac}}{\sqrt{4a^{2}}}$<br>
  $\displaystyle x = - \frac{b}{2a} \pm \frac{\sqrt{b^{2} - 4ac}}{\sqrt{4a^{2}}}$<br>
  $\displaystyle x = - \frac{b}{2a} \pm \frac{\sqrt{b^{2} - 4ac}}{2a}$<br>
  $\displaystyle x = \frac{- b \pm \sqrt{b^{2} - 4ac}}{2a}$<br>

  $\displaystyle x_{1} = \frac{- b + \sqrt{b^{2} - 4ac}}{2a}$<br>
  $\displaystyle x_{2} = \frac{- b - \sqrt{b^{2} - 4ac}}{2a}$<br>


</p>
