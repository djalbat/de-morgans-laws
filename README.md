# De Morgan's Laws

De Morgan's laws for the [Occam](http://djalbat.com/occam) proof assistant.

The rules are divided into two, with those that can be derived intuitionistically distinguished from those that can only be derived classically.

## Intuitionistically derivable rules

\[
\frac{P\land{Q}}{\neg(\neg{P}\lor\neg{Q})}\quad\small\text{[ConjunctionInfersNegatedDisjunctionOfNegatives]}
\]
\[
\frac{P\lor{Q}}{\neg(\neg{P}\land\neg{Q})}\quad\small\text{[DisjunctionInfersNegatedConjunctionOfNegatives]}
\]
\[
\frac{\neg{P}\lor\neg{Q}}{\neg(P\land{Q})}\quad\small\text{[DisjunctionOfNegationsInfersNegatedConjunction]}
\]
\[
\frac{\neg{P}\land\neg{Q}}{\neg(P\lor{Q})}\quad\small\text{[ConjunctionOfNegationsInfersNegatedDisjunction]}
\]
\[
\frac{\neg({P}\lor{Q})}{\neg{P}\land\neg{Q}}\quad\small\text{[NegatedDisjunctionInfersConjunctionOfNegations]}
\]

## Classically derivable rules

\[
\frac{\neg({P}\land{Q})}{\neg{P}\lor\neg{Q}}\quad\small\text{[NegatedConjunctionInfersDisjunctionOfNegations]}
\]
\[
\frac{\neg(\neg{P}\land\neg{Q})}{P\lor{Q}}\quad\small\text{[NegatedConjunctionOfNegationsInfersDisjunction]}
\]
\[
\frac{\neg(\neg{P}\lor\neg{Q})}{P\land{Q}}\quad\small\text{[NegatedDisjunctionOfNegationsInfersConjunction]}
\]

## Contact

* james.smith@openmathematics.org
* http://djalbat.com
