# prog1385-assign-03-upgrading-your-car-radio-solved
**TO GET THIS SOLUTION VISIT:** [PROG1385 Assign-03 Upgrading Your Car Radio Solved](https://www.ankitcodinghub.com/product/prog1385-assign-03-upgrading-your-car-radio-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;65912&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;PROG1385 Assign-03  Upgrading Your Car Radio Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
Retrieve and use the<strong><em> CarRadio-StartingPoint.zip</em></strong> file from eConestoga as your starting point.&nbsp; The CarRadio example provided above is an okay … but is significantly flawed in a lot of ways. Your task in this assignment is to take this “okay” class definition and make it better and more general by improving it in the following ways:

<strong>Generalizations: </strong>

<ul>
<li>Change the names of the two class-related files to h and AmFmRadio.cpp.</li>
<li>Change the name of the class to <em>AmFmRadio</em> (this class no longer models a radio within a car)</li>
<li>Rename the <em>struct Button </em>to <em>struct Freqs</em>, since we’re going to use the struct for more than buttons.
<ul>
<li>Change <em>AMButton </em>to <em>AMFreq </em>and <em>FMButton</em> to <em>FMFreq.</em> o &nbsp;&nbsp;&nbsp;&nbsp; You can keep the same default values for the AM/FM frequencies as found in CarRadio</li>
</ul>
</li>
</ul>
<strong>Additions &amp; Replacements: </strong>

<ul>
<li>Replace the existing constructor with two constructors that initialize all private data and that use the following parameters to initialize the appropriate data:
<ul>
<li>one that takes a single bool parameter that indicates whether the radio should be on or not when instantiated. Give this parameter a default of <em>false</em> (as discussed in Module 1 (default parameters)).</li>
<li>one that takes a single bool parameter that indicates whether the radio should be on or not when instantiated and an array of 5 <em>struct Freqs</em> that contains the initial radio preset values (i.e. the station’s frequency).</li>
</ul>
</li>
<li>Add a destructor that simply displays “Destroying AmFmRadio”.</li>
<li>Make sure that the instance of <em>AmFmRadio </em>created in the cpp mainline is instantiated powered on.</li>
<li>Add a method called <em>ScanDown()</em> that behaves similarly to <em>ScanUp()</em>, except that the scanning is down. o When the AM and FM band reach the minimum frequency, they roll-over to the maximum frequency in the band o Make menu entry #8 correspond to “Scan Down”. Make menu entry #9 correspond to “Quit the program”.&nbsp; ▪ &nbsp;&nbsp;&nbsp; <u>Do not otherwise change the user interface</u>.&nbsp; ▪ <strong>I’m serious</strong>.</li>
<li>Create a mutator for the <em>current_station</em> data member. o Actually while you’re at it, please make sure that all variables / elements holding an FM Frequency elsewhere in the code match the data type of current_station … I don’t think that they did in the starting code</li>
<li>When switching from AM to FM (and vice versa), go immediately to the previous frequency tuned on that band. o &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; g. if you’re listening to 700 on AM and switch to FM and then back to AM, make sure that you go to 700, not 530.
<ul>
<li>Hint: it would be a good idea to use a new <u>data member</u> of type <em>struct Freqs. </em></li>
</ul>
</li>
<li>When turning the radio on after being off, go immediately to the previous band (AM or FM) and last frequency tuned on that band.
<ul>
<li>g. if you’re listening to 92.9 on FM and turn the radio off, turning the radio on again should tune to 92.9 on FM.</li>
<li>Hint: the previous hint works here too.</li>
</ul>
</li>
<li>When turning the radio off, turn the volume down to 0. When turning the radio back on, restore the previous volume level. o &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Turn the volume level to 0 when the radio is turned on for the first time.</li>
<li>Create a second version of <em>SetVolume</em>(). The second one takes a volume as a parameter. The reason for this addition is so that someone using <em>SetVolume</em>() can get the value in their own way and pass it to the method.
<ul>
<li>You will not be using this second version in this assignment. You will be using it in a later assignment. o &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; There is already a method called <em>SetVolume()</em> and you are adding another – what does this mean?&nbsp; What are the best practices in coding something like this?</li>
</ul>
</li>
<li>Change <em>ScanUp()</em> so that it can be called without any output being displayed. If you have any other methods (except <em>ShowCurrentSettings()</em> ) that display output, make it possible for them to be called without any output being displayed.
<ul>
<li>Note that this does <strong>not</strong> mean that you should totally eliminate output being displayed but should make output display optional. o &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; This does <strong>not </strong>apply to <em>ShowCurrentSettings()</em>, as its entire purpose is to display output.&nbsp; This also doesn’t apply to the prompt in the existing <em>SetVolume()</em></li>
<li>Suggestion: Create a private bool data member (e.g. “displayOutput”) that keeps track of whether or not output should be displayed (except <em>ShowCurrentSettings()</em> and prompting <em>SetVolume()</em>)<em>. </em></li>
<li>Reasoning: You will be inheriting from this class in a later assignment and you don’t want to display output from the parent class when you’ll be doing it from the child class instead. The child class will contain the user interface to be used for that assignment.</li>
<li>Please ensure that by default this private bool data member is set so that no output is coming from any methods (except for</li>
</ul>
</li>
</ul>
<em>ShowCurrentSettings()</em>and prompting <em>SetVolume()</em>) o Also create a mutator for this “displayOutput”&nbsp; data member

<ul>
<li>Make sure to create <strong>accessors</strong> for the private data members representing the current station, the current volume, the set of radio presets, the current band (AM or FM) as well as the new “displayOutput” data member.
<ul>
<li>When creating your accessor for the radio presets and current band – refer to the notes in Module-06 (slides 15 through 17)</li>
</ul>
</li>
</ul>
<strong>Style and Convention Requirements </strong>

<ul>
<li>Make any new data members that you create private.</li>
<li>As discussed in class, all of the class’ source code belongs in the cpp – there should be no code in the AmFmRadio.h (class definition)</li>
<li>Your code must not unnecessarily duplicate similar code segments. Make use of your methods (e.g. the mutator mentioned above) appropriately.</li>
<li>Using the what was called the <strong><u>classic commenting</u></strong> style in the lessons, o &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Add full file header / class header comments in each of your three source files (yes, even the .h file). For the descriptions of each, describe what is done (generally) by the contents of the file being commented.
<ul>
<li>Add full method header comments on each method you develop and don’t forget your inline comments as well</li>
<li>Make sure that all comments that already exist in the example are correct. Yes – even when you take over someone else’s code – you become responsible for their comments!</li>
</ul>
</li>
</ul>
<strong>Other Stuff </strong>

<ul>
<li>If you want to create additional methods or data members, you can.</li>
<li>Watch the datatypes being used – ensure that all code within the class is consistent with the data member datatypes.</li>
<li>Please realize that not all of the changes that you are making will be used in this assignment. We are trying to design the class to be more useful in general. We will be using many of the changes in subsequent assignments.</li>
<li>Also realize that some of the requirements above have already been implemented.</li>
</ul>
ZIP up the source files : AmFmRadio.h, AmFmRadio.cpp, and driver.cpp and submit them to the eConestoga dropbox by the deadline.
