# ee352-lab-8-solved
**TO GET THIS SOLUTION VISIT:** [EE352 Lab 8 Solved](https://www.ankitcodinghub.com/product/ee352-lab-8-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94352&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE352 Lab 8 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
8 Preliminaries

</div>
</div>
<div class="layoutArea">
<div class="column">
In this laboratory, we cover the noise in amplitude modulation. As amplitude modulation, we choose Double Side Band Suppress Carrier (DSB-SC). As we performed in previous laboratories, for DSB-SC modulation, we multiply the message signal with the carrier signal. Thus, the amplitude of the carrier signal changes depending on the amplitude of the message signal. In addition to these works, in this week, we include the noise to our consideration. The term noise is used to represent the unwanted waves that disturb the trans- mission. While simulating our analog systems, we can generate the noise by using some built-in functions in Matlab. For this laboratory, it is useful to learn about the Matlab functions im2double(.),reshape(.),awgn(.), imshow(.) and numel(.).

Figure 1: Block Diagram

9 Labwork (AM in noise) 9.1 Construction

<ol>
<li>a) &nbsp;Read the image file ”cameraman.tif” that is given in the MATLAB library by using imread() and change the class of data by using im2double(). In the end, you must have a message signal matrix, M.</li>
<li>b) &nbsp;Denote sampling rate Fs of this image as the size of the M.</li>
<li>c) &nbsp;Turn your message signal matrix to a message signal vector y by using reshape().
Hint:Use time vector t = 0:(1/Fs):(numel(y) – 1)/Fs.
</li>
<li>d) &nbsp;Construct the carrier signal where c(t) = cos(2πfct), with fc = 20kHz.</li>
</ol>
9.2 Modulation

<ol>
<li>a) &nbsp;Obtain DSB-SC AM signal Xdsbsc.</li>
<li>b) &nbsp;Add additive white Gaussian noise (AWGN) with signal to noise ratio (SNR) values of 0dB, 5dB, 10dB,
20dB and 30dB using awgn() to your modulated Xdsbsc.
</li>
</ol>
9.3 Demodulation and Filtering

<ol>
<li>a) &nbsp;Demodulate modulated Xdsbsc signals by multiplying with carrier signal and using a LPF with suitable filter order. Hint: Use butter(.) and filter(.). Comment on choosing filter parameters.</li>
<li>b) &nbsp;After filtering, you will obtain the demodulated message vectors and you have to convert your demodu- lated message vectors to demodulated message signal matrices, using reshape() again.</li>
<li>c) &nbsp;Comment on the effect of the SNR on demodulated images.</li>
</ol>
May 20, 2021 Page 1

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
DSB-SC Modulation

</div>
</div>
<div class="layoutArea">
<div class="column">
n

</div>
</div>
<div class="layoutArea">
<div class="column">
Image

</div>
<div class="column">
Demodulated Image

</div>
</div>
<div class="layoutArea">
<div class="column">
DSB-SC Demodulation

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
EE 352 – Lab 8: AM in noise

</div>
</div>
<div class="layoutArea">
<div class="column">
9.4 Plots

a) Plot the original image and the demodulated images on the same figure using subplot. Use imshow() command to see your figures.

9.5 Mean Square Error (MSE) and comparison

a) Write a MATLAB function which calculates the MSE values between the message signal and demodulated signals with 5 different SNR values by using:

</div>
</div>
<div class="layoutArea">
<div class="column">
1 m−1 n−1

􏰅 􏰅[OriginalImageMatrix(i, j) − FilteredImageMatrix(i, j)]2 i=0 j=0

where m and n are the number of the rows and columns of the image respectively.

<ol start="2">
<li>b) &nbsp;Plot the calculated MSE values with respect to SNR=[0,5,10,20,30].</li>
<li>c) &nbsp;Comment on the result.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
May 20, 2021

</div>
<div class="column">
Page 2

</div>
</div>
<div class="layoutArea">
<div class="column">
MSE =

</div>
<div class="column">
mn

</div>
<div class="column">
(1)

</div>
</div>
</div>
