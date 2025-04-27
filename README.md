# cmsc330-project-1-with-docmuentation-solved
**TO GET THIS SOLUTION VISIT:** [CMSC330 Project 1 with docmuentation Solved](https://www.ankitcodinghub.com/product/cmsc330-project-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;63808&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC330 Project 1 with docmuentation  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
The first programming project involves writing a program that parses, using recursive descent, a GUI definition language defined in an input file and generates the GUI that it defines. The grammar for this language is defined below:

gui ::=

Window STRING ‘(‘ NUMBER ‘,’ NUMBER ‘)’ layout widgets End ‘.’ layout ::=

Layout layout_type ‘:’ layout_type ::=

Flow |

Grid ‘(‘ NUMBER ‘,’ NUMBER [‘,’ NUMBER ‘,’ NUMBER] ‘)’ widgets ::=&nbsp;&nbsp;&nbsp;&nbsp; widget widgets |

widget widget ::=

Button STRING ‘;’ |

Group radio_buttons End ‘;’ |

Label STRING ‘;’ |

Panel layout widgets End ‘;’ |&nbsp;&nbsp;&nbsp;&nbsp; Textfield NUMBER ‘;’ radio_buttons ::=

radio_button radio_buttons |&nbsp;&nbsp;&nbsp;&nbsp; radio_button radio_button ::=

Radio STRING ‘;’

In the above grammar, the red symbols are nonterminals, the blue symbols are tokens and the black punctuation symbols are BNF metasymbols. Among the tokens those in title case are keywords. The character literals are punctuation tokens.

Below is an explanation of the meaning of some of the symbols in the above productions that should help you understand the actions that are to be performed when each of the productions is parsed:

<ul>
<li>In the window production the string is the name that is to appear in the top border of the window and the two numbers are the width and height of the window</li>
<li>In the production for layout_type that define the grid layout, the first two numbers represent the number of rows and columns, and the optional next two the horizontal and vertical gaps</li>
<li>In the production for widget that defines a button, the string is the name of the button</li>
<li>In the production for widget that defines a label, the string is text that is to be placed in the label</li>
<li>In the production for widget that defines a text field, the number is the width of the text field</li>
<li>In the production for radio_button, the string is the label of the button</li>
</ul>
You parser should properly handle the fact that panels can be nested in other panels. Recursive productions must be implemented using recursion. Syntactically incorrect input files should detect and report the first error.

Below is an example of an input file:

Window “Calculator” (200, 200) Layout Flow:

Textfield 20;

Panel Layout Grid(4, 3, 5, 5):

Button “7”;

Button “8”;

Button “9”;

Button “4”;

Button “5”;

Button “6”;

Button “1”;

Button “2”;

Button “3”;

Label “”;

Button “0”;&nbsp;&nbsp; End; End.

The above input file should produce the GUI shown below:

&nbsp;

<strong>Deliverables: </strong>

Deliverables for this project include the following:

<ol>
<li>Source code correctly implementing all required functionality.</li>
<li>Word or PDF file providing screen shots of successfully compiling and executing the program.</li>
<li>Description of the process and lesson learned while completing this project (to be included in the Word or PDF document).</li>
<li>A test plan that contains test cases that include both layout types, all widgets and nested panels. For each test case, the input file should be shown together with the resulting GUI. (to be included in the Word or PDF document).</li>
</ol>
&nbsp;
