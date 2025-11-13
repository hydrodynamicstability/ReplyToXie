# Reply to Gang (John) Xie, "A Practicing Statistician's Plea" (*Amstat News*, Dec. 2024, p. 28).

by Christopher Tong, 31 August 2025

I welcome the recent [op-ed](https://magazine.amstat.org/blog/2024/12/02/a-practicing-statisticians-plea/) by Gang (John) Xie in the December 2024 issue of *Amstat News*.  He argues that the manifest failure of model assumptions underlying most applications of statistical modeling "compromise the reliability  and validity of statistical inference".  He is particularly focused on situations when neither a random sampling nor a random assignment mechanism was used in the data generating process.  He also criticizes the widespread reliance on a single study to base scientific inferences.  I write here to clarify two essential details.

First, the creative and careful use of fictional assumptions (such as stochasticity) to define a model system in place of the actual data-generating process is a time-honored tradition in theoretical physics, engineering, and applied mathematics.  These assumptions are sometimes known to be incorrect at the outset; in other cases, an assumption is debunked later, or simply left as unverifiable.  Yet, the resulting model systems can (with limitations) continue to assist with reasoning about and predicting key aspects of the real world.  Examples include the Bohr-Sommerfeld model of the atom, the liquid drop and shell models of the atomic nucleus, and the two-fluid model of liquid helium II.  (I provided additional examples in an earlier [letter](https://magazine.amstat.org/blog/2015/05/01/sciencenotartii/) to *Amstat News*, May 2015, pp. 34-35.)  One 19th-century example based on a stochastic model arguably lacking in *a priori* justification is James Clerk Maxwell's kinetic theory of gases (Garber, 1973).  This theory famously predicted (before experimental data were sufficiently abundant and precise to deduce it) that the viscosity of a gas is independent of pressure.  Maxwell (and his uncredited wife, Katherine) subsequently experimentally verified this prediction across a wide range of pressures, as did O. E. Meyer working independently (Brush & Hall, 2003).  However, this was *not* a case of statistical inference:  the model preceded the data, not the other way around.  More generally, the successful use of the models I've listed above depends on post-hoc empirical verification (and delineation of model limitations) using new data under new, broader conditions, not just compatibility with existing data.  Unfortunately, this key caveat is rarely considered when statistical inferences are invoked in the scientific literature, except in studies that follow a formally phased approach (such as the discovery and validation phases of genome-wide association studies, or the three phases of clinical trials).  Hence, this first clarification does little to reduce the force of Xie's argument.  Additional perspectives on the often unwarranted use of probability mathematics for modeling real world data are given by Taleb (2010), Kay & King (2020), and Crane (2020).  

The second clarification is that the case against careless statistical inference does not simply rest on a critique of inappropriate assumptions.  Model uncertainty is furthermore the result of the scientifically justified reuse of data to peform model improvement and/or model selection, inherently risking uncontrolled overfitting, leading to both biased and overconfident inferences (Chatfield, 1995).  Statistical inference under either a frequentist or a likelihood principle-based framework requires the *pre-specification* of the statistical model prior to data collection (Feller, 1970; Diaconis, 1985), which is incompatible with the scientific need for model building *after* the data are in hand (Gelman & Loken, 2014).  Model uncertainty also includes uncertainty about systematic errors in the data.  Techniques such as sensitivity analysis, model averaging, cross-validation, regualrization, and "post-selection inference" address very limited aspects of model uncertainty, as they focus on internal, not external validation.  As above, a more complete uncertainty quantification requires new data.

Many other criticisms of the current practice of statisical inference have been raised.  For example, McShane et al. (2019) observe that outputs like p-values fail to reflect what they call "currently subordinate factors" that play a role in interpreting evidence, such as the quality of data, quality of study design and execution, context, "and other factors that vary by research domain".  Greenland (2017) identifies three commonly taught attitudes that discourage critical thinking about statistical inferences:  dichotomania, nullism, and reification.

Xie insists that "The validation or justification of scientific research findings...is a task for the scientific method itself, not achievable through statistical inference," and he calls for "a deeper understanding of the role and limitations of statistical tools and the importance of integrating them into a rigorous scientific framework."  I hope that the above clarifications serve to bolster these points.  

## References

E. Garber, 1973:  [Aspects of the introduction of probability into physics](https://doi.org/10.1111/j.1600-0498.1973.tb00182.x).  *Centaurus*, 17:  11-40.  

S. G. Brush and N. S. Hall (eds.), 2003:  [*The Kinetic Theory of Gases:  An Anthology of Classic Papers with Historical Commentary*](https://doi.org/10.1142/p281).  London:  Imperical College Press.  

N. N. Taleb, 2010:  *The Black Swan:  The Impact of the Highly Improbable*, second edition.  New York:  Random House.

J. Kay and M. King, 2020:  *Radical Uncertainty:  Decision-Making Beyond the Numbers*.  New York:  W. W. Norton.

H. Crane, 2020:  [Naive probabilism](https://researchers.one/articles/20.03.00003v1).  *Researchers.One*.

C. Chatfield, 1995:  [Model uncertainty, data mining, and statistical inference](https://doi.org/10.2307/2983440).  *Journal of the Royal Statistical Society*, A158:  419-466.  

W. Feller, 1970:  *An Introduction to Probability Theory and Its Applications*, revised third edition.  New York:  Wiley.

P. Diaconis, 1985:  [Theories of data analysis:  from magical thinking through classical statistics](https://doi.org/10.1002/9781118150702.ch1).  In *Exploring Data Tables, Trends, and Shapes*, ed. by D. C. Hoaglin, F. Mosteller, and J. W. Tukey.  New York:  Wiley, pp. 1-36. 

A. Gelman and E. Loken, 2014:  [The statistical crisis in science](https://www.jstor.org/stable/43707868).  *American Scientist*, 102:  460-465.     

B. B. McShane, D. Gal, A. Gelman, C. Robert, and J. L. Tackett, 2019:  [Abandon statistical significance](https://doi.org/10.1080/00031305.2018.1527253).  *The American Statistician*, 73 (sup 1):  235-245.  

S. Greenland, 2017:  [The need for cognitive science in methodology](https://doi.org/10.1093/aje/kwx259).  *American Journal of Epidemiology*, 186:  639-645.  

## Disclosures

The views expressed here are mine alone, and do not necessarily reflect the policies, views, or opinions of my employer.

Minor edit (12 Nov 2025):  corrected Taleb, McShane et al., and Greenland citations.

(c) Copyright 2025 by Christopher Tong.  All rights reserved.
