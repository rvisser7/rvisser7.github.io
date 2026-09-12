---
layout: default
title: Genus 2 curves whose Jacobians have good reduction away from 2
description: Genus 2 curves C/Q whose Jacobians have good reduction away from 2, with downloadable data.
---

I've been on a quest to find as many genus 2 curves $C/\mathbb{Q}$ as I can whose
Jacobian has good reduction away from 2. This is still work in progress; so far
we've found **512** such curves, including the 366 found by
[Smart](https://doi.org/10.1112/S002461159700035X). We are indebted to the
[LMFDB](https://www.lmfdb.org/) for inspiring this project.

## Genus 2 curves

| File | Contents |
| --- | --- |
| [genus2_good2.txt]({{ site.genus2_base }}/genus2_good2.txt) | A list of polynomials $f(x)$, each denoting a genus 2 curve given as a simplified model $y^2 = f(x)$. |
| [genus2_good2_stats.txt]({{ site.genus2_base }}/genus2_good2_stats.txt) | Each line is in the format $\texttt{D:N:r:T:f(x):A:S}$, where $D$ is the absolute discriminant, $N$ the conductor, $r$ the rank, $T$ the torsion subgroup, $f(x)$ a polynomial defining $C$, $A$ the automorphism group, and $S$ the Sato–Tate group. |
| [genus2_good2_stats.pdf]({{ site.genus2_base }}/genus2_good2_stats.pdf) | A LaTeX-formatted summary of the various invariants (minimal discriminant, conductor, rank, and so on) for each curve $C/\mathbb{Q}$. For field systems we adopt the same notation as [Smart](https://doi.org/10.1112/S002461159700035X). |
| [genus2_good2_geometric_stats.pdf]({{ site.genus2_base }}/genus2_good2_geometric_stats.pdf) | A LaTeX-formatted summary of invariants of the 67 $\overline{\mathbb{Q}}$-isomorphism classes of the curves above (G2-invariants, geometric bad primes, geometric automorphism group, and so on). |

## Abelian surfaces

Including products of elliptic curves $E/\mathbb{Q}$ good outside 2, and Weil
restrictions of elliptic curves over quadratic fields $K$ good outside 2, we've
found a total of **234** isogeny classes of abelian surfaces with good reduction
away from 2.

| File | Contents |
| --- | --- |
| [abelian2_good2.pdf]({{ site.genus2_base }}/abelian2_good2.pdf) | A LaTeX-formatted summary of the various invariants (conductor, rank, endomorphism algebra, and so on) for each isogeny class of abelian surface $A/\mathbb{Q}$ found. |
| [lfunctions2_good2.txt]({{ site.genus2_base }}/lfunctions2_good2.txt) | Each line is in the format $\texttt{N:r:[L2,L3,...,L97]:S:m:c}$, where $N$ is the conductor, $r$ the rank, $L_2, L_3, \ldots, L_{97}$ the first few Euler factors, $m$ the number of known genus 2 curves $C/\mathbb{Q}$ whose Jacobian lies in this isogeny class, and $c$ the leading coefficient of the L-function. |

## Notes

For details on how these curves and all their invariants were computed, see
Chapters 5 and 6 of [my thesis]({{ site.files_base }}/thesis.pdf).

If you know of any examples of abelian surfaces good away from 2 not given in the
tables above, [please let me know](mailto:robin.visser@matfyz.cuni.cz). A £100
prize was offered for any new genus 2 curve whose Jacobian has good reduction
away from 2, subject to
[terms and conditions]({{ site.genus2_base }}/genus2_termsandconditions.txt).

**Update (8 June 2026).** The prize has been claimed by
[Raymond van Bommel](https://raymondvanbommel.nl/),
[Céline Maistret](https://sites.google.com/view/cmaistret/home),
[Jia Shi](https://janeshi99.github.io/) and
[Andrew V. Sutherland](https://math.mit.edu/~drew/), who found ten new genus 2
curves — see [their paper](https://arxiv.org/abs/2606.09512).

<figure>
  <img src="{{ site.genus2_base }}/genus2pic.jpg" alt="Meme contrasting thinking about computing all genus 2 curves of conductor 2^n with actually computing them">
</figure>
