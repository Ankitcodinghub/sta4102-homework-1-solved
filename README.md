# sta4102-homework-1-solved
**TO GET THIS SOLUTION VISIT:** [STA4102 Homework #1 Solved](https://www.ankitcodinghub.com/product/homework-1-sta410h1f-2102h1f-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117144&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STA4102 Homework #1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Instructions: Solutions to problems 1 and 2 are to be submitted via Quercus and only PDF files will be accepted. (Ideally, you should submit only one file.) You are strongly encouraged to do problems 3 and 4 but these are not to be submitted for grading.

1. In this problem, you will use the discrete cosine transform (DCT) to denoise an image. An R function to compute a two-dimensional DCT is available in the R package dtt – this package contains functions to compute a number of “trigonometric” transforms. The R function that will be used in this package is mvdct.

Suppose that Z is an m × n pixel image, which we can represent as an m × n matrix. Then using {An}, we can define a transform of Z as follows:

Given the m × n matrix Zb, show that we can reconstruct the original image by Z =

.

(b) To denoise an image using the DCT, we first compute Zb and then perform hard- or soft-thresholding to obtain a thresholded (or shrunken) transform Zb∗ (which will typically be “sparser” than Zb). Our hope is that the components of Zb corresponding to noise in the image are eliminated and so the denoised image can be obtained by applying the inverse transform to Zb∗.

Using mvdct, write R functions to perform both hard- and soft-thresholding (dependent on a parameter λ). Your functions should not threshold the (1,1) component of the DCT matrix. (A simple R function to do hard thresholding will be provided on Quercus; this can be modified to do soft thresholding.)

(c) The file boats.txt contains a noisy 256 × 256 pixel grayscale image of sailboats. Its entries are numbers between 0 and 1 where 0 represents black and 1 represents white. The data can be read into R and displayed as an image as follows:

&gt; boats &lt;- matrix(scan(“boats.txt”),ncol=256,byrow=T) &gt; image(boats, axes=F, col=grey(seq(0,1,length=256)))

Using your functions from part (b), try to denoise the image as best as possible. (This is quite subjective but try different methods and parameter values.)

2. Suppose that U and V are independent Poisson random variables with means λu and λv. We then define X = U + 2V , which is said to have a Hermite distribution with parameters λu and λv. (The Hermite distribution is the distribution of a sum of two correlated Poisson random variables.)

(a) Show that the probability generating function of X is

g(s) = E(sX) = exphλu(s − 1) + λv(s2 − 1)i.

(b) The distribution of X can, in theory, be obtained exactly in closed-form with exact computation for given λu and λv somewhat more difficult. However, we can approximate the distribution very well by combining the exact probability generating with the discrete Fourier transform. The key to doing this is to find M such that P(X ≥ M) is very small so that we can use the discrete Fourier transform to compute (to a very good approximation) P(X = x) for x = 0,1,···,M − 1.

One approach to determining M is to use the probability generating function of X and

Markov’s inequality. Specifically, if s &gt; 1 we have

Use this fact to show that for , we can take

(c) Given M (which depends on ), the algorithm for determining the distribution of X goes as follows:

1. Evaluate the probability generating function g(s) at s = sk = exp(−2πιk/M) for k = 0,···,M − 1; the values of s can be created in R as follows:

&gt; s &lt;- exp(-2*pi*1i*c(0:(M-1))/M)

2. Evaluate P(X = x) by computing the inverse FFT of the sequence {g(sk) : k = 0,···,M − 1}:

Write an R function to implement this algorithm where M is determined using the method in part (b) with . Use this function to evaluate the distribution of X for the following two cases:

(i) λu = 1 and λv = 5;

(ii) λu = 0.1 and λv = 2.

Note that you do not need to evaluate the bound M with great precision; for example, a simple approach is to take a discrete set of points S = {1 &lt; s1 &lt; s2 &lt; ··· &lt; sk} and define

where δ = si+1 − si and sk are determined graphically (that is, by plotting the appropriate function) so that you are convinced that the value of M is close to the actual infimum.

Supplemental problems (not to hand in):

fl(x) − fl(y) = x − y + (xu − yv)

, (1)

with ¯x = ¯xn.

(a) Show that can be computed using the recursion

for k = 1,···,n − 1. (This is known as West’s algorithm.)

(b) A somewhat simpler one-pass method replaces ¯x by some estimate x0 and then corrects for the error in estimation. Specifically, if x0 is an arbitrary number, show that

n n X 2 X 2 2

(xi − x¯) = (xi − x0) − n(x0 − x¯) .

i=1 i=1

(c) The key in using the formula in part (b) is to choose x0 to avoid catastrophic cancellation, that is, x0 should be close to ¯x. How might you choose x0 (without first computing ¯x) to minimize the possibility of catastrophic cancellation? Ideally, x0 should be calculated using o(n) operations.

(An interesting paper on computational algorithms for computing the variance is “Algorithms for computing the sample variance: analysis and recommendations” by Chan, Golub, and LeVeque; this paper is available on Quercus.)

4. (a) Suppose that A, B, C, and D are matrices so that AC and BD are both well-defined. Show that

(AC) ⊗ (BD) = (A ⊗ B)(C ⊗ D)

(Hint: This is easier than it looks — the key is to start with the right hand side of the identity.)

(b) Use the result of part (a) to show that

(A ⊗ B)−1 = A−1 ⊗ B−1

for invertible matrices A and B.

k

H2k = Y(I2j−1 ⊗ H2 ⊗ I2k−j)

j=1

(Hint: Use induction, starting with the fact that the identity holds trivially for k = 1.)
