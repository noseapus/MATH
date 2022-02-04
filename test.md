Let $D$ be the probability individual has a disease and $E$ be the probability of a positive test result. Then
\[
P(D)=0.01,\quad P(E|D)=0.95,\quad P(E|D^c)=0.06
\]
So the probability of a positive result is
\[
P(E)=P(E|D)P(D)+P(E|D^c)P(D^)=0.95\times 0.01+0.06\times0.99=0.0689
\]
The probability of having the disease given a positive test is, by Bayes
\[
P(D|E)=\frac{P(E|D)P(D)}{P(E)}=\frac{0.95\times0.01}{0.0689}=0.138
\]
