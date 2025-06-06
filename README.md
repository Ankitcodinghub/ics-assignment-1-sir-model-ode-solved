# ics-assignment-1-sir-model-ode-solved
**TO GET THIS SOLUTION VISIT:** [ICS Assignment 1-SIR model (ODE) Solved](https://www.ankitcodinghub.com/product/ics-assignment-1-sir-model-ode-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;86038&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ICS Assignment 1-SIR model (ODE) Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
&nbsp;

<h1>Introduction</h1>
The SIR model is an epidemiological model that computes the spread of an infectious disease through a population of people. It is used to compute the number of susceptible (S), infected (I), and recovered (R) individuals at any given time through the spread of an infectious disease. The model can be written as a set of first order differential equations:

(1)

(2)

(3)

Here <em>β </em>is the parameter for the rate of infection and <em>γ </em>is the parameter for the rate of recovery. A first assumption can be made keeping the population in our model “closed” meaning <em>S </em>+<em>I </em>+<em>R </em>=1.

<h1>Problem 1: Numerical integration of the basic model</h1>
In the basic model we can assume the population is fixed <em>S </em>+<em>I </em>+<em>R </em>=1. The spread of infection goes one direction from susceptible to infected to recovered. Once an individual is recovered he or she is no longer susceptible.

<ol>
<li>Numerically integrate the above ODEs for states of an epidemic and no epidemic.What is the parameter that determines if the infectious disease will become an epidemic? Provide phase space diagrams, with analysis, of the system.</li>
<li>Given below is the historical data from a case of an influenza outbreak situation.The outbreak was in a boys school with a total of 763 boys. It also seems that one infected boy started the epidemic. Could you try to fit an SIR model to the data?</li>
</ol>
<table width="553">
<tbody>
<tr>
<td width="88">Day</td>
<td width="24">1</td>
<td width="24">2</td>
<td width="32">3</td>
<td width="32">4</td>
<td width="39">5</td>
<td width="39">6</td>
<td width="39">7</td>
<td width="39">8</td>
<td width="39">9</td>
<td width="39">10</td>
<td width="32">11</td>
<td width="32">12</td>
<td width="32">13</td>
<td width="24">14</td>
</tr>
<tr>
<td width="88">Number</td>
<td width="24">3</td>
<td width="24">8</td>
<td width="32">28</td>
<td width="32">75</td>
<td width="39">221</td>
<td width="39">291</td>
<td width="39">255</td>
<td width="39">235</td>
<td width="39">190</td>
<td width="39">125</td>
<td width="32">70</td>
<td width="32">28</td>
<td width="32">12</td>
<td width="24">5</td>
</tr>
</tbody>
</table>
<ol start="3">
<li>Can you propose a vaccination plan to prevent the epidemic?</li>
</ol>
Introduction to Computational Science Assignment 1

<h1>Problem 2: Demography</h1>
Now we want to start to add more terms to our model. Lets start to consider demography, i.e. Birth and death rates.

<ol>
<li>Add birth and natural death rate term into model. (Hint: keep <em>N<sub>population </sub></em>constant). How does the dynamics change? Run the model to capture an endemic state. Do you see oscillatory behavior in the fraction of infected population? What are requirements to observe this behavior? What is the frequency and amplitude of these oscillations (Hint: use Fourier analysis)?</li>
<li>Add an infection induced mortality term to the model (<em>N<sub>population </sub></em>6= constant), which will depend on some probability of dying while infected. What happens when the probability approaches 1?</li>
</ol>
Problem 3: Variation on the SIR model.

Pick a variation of the SIR model and provide similar detail and analysis used in the previous problems. Some examples can be SIER, MSIR, SEIS, MSEIR, MSEIRS etc. Add seasonal effects into the model you choose (Hint: add a time varying sinusoidal rate of infection).
