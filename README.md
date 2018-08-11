# Election-Meddling 

Twiter based, anonymous (Non API-dependant), artificial intelligence for PSYOPS/MOOTW mass political profiling and persuation.

### PROGRAM FLOW:

* Unauthenticated twitter client downloads tweets from target username(s)
* Supervised learning sentiment analysis is performed on the tweets to determine target's personality.
* Tweet text tokenizing, character filtering.
* Penn bank compliant Part Of Speech tag recognition.
* P.O.S based Context-dependant word stemming.
* Unsupervised topic recognition, tweet categorization.
* Topic specific sentiment analisys to determine target's political orientation on the Noan chart.
* (Optional) Propaganda function call to influence target based on learnt behaviour.

---
### Key concept:

If wanted to benefit (A) wing over (B) wing, pro BLANK vote propaganda will be sent - in some manner- to those who tend to the opposite (B) wing, and pro VOTE propaganda to those who tend to (A) wing, resulting in a higher proportion of votes for (A) wing. 

---

### Example output:

> python3.6 deploy.py -t potus -b left -c 100

<a href="https://github.com/zadewg/"><img src="https://image.ibb.co/n0w80p/nolan2.png" title="Nolan chart" alt="Nolan chart"></a>


<pre>
       ___           ___                       ___      
      /\  \         /\  \          ___        /\__\     
     /::\  \       /::\  \        /\  \      /::|  |    
    /:/\ \  \     /:/\:\  \       \:\  \    /:|:|  |    
   _\:\~\ \  \   /::\~\:\  \      /::\__\  /:/|:|  |__  
  /\ \:\ \ \__\ /:/\:\ \:\__\  __/:/\/__/ /:/ |:| /\__\ 
  \:\ \:\ \/__/ \/__\:\/:/  / /\/:/  /    \/__|:|/:/  / 
   \:\ \:\__\        \::/  /  \::/__/         |:/:/  /  
    \:\/:/  /         \/__/    \:\__\         |::/  /   
     \::/  /                    \/__/         /:/  /    
      \/__/                                   \/__/     
                  Red Team Intelligence               

      https://github.com/zadewg/Election-Meddling  


[*] Target: potus (Washington, D.C.) 23763183 followers
[*] Benefit left wing
[*] Collecting ~100 Tweets

.
.
.

                                                Tweets  len                   ID                Date   Likes    RTs  SA
751  .@realdonaldtrump: "We're meeting with the Cha...   94  1002633696086593536 2018-06-01 19:31:15   11748   2559   0
752  Congratulations to Vice Admiral Karl Schultz o...  195  1002628738146865154 2018-06-01 19:11:33    5983   1009   1
753  Admiral Paul Zukunft has done an outstanding j...  156  1002628407807619073 2018-06-01 19:10:15    5246    765   1
754  Honored to join @POTUS this morning at the @US...  269  1002627439892271106 2018-06-01 19:06:24    6754   1131   1
755  This is the lowest unemployment rate in more t...  170  1002620046764539904 2018-06-01 18:37:01    6033   1515   1
756  President Trump is working hard to create a th...  239  1002612998433923078 2018-06-01 18:09:01    4917   1226   1
757  The @NYTimes: “We Ran Out of Words to Describe...  148  1002598904498704385 2018-06-01 17:13:00    8885   2674   1
758  Record JOBS DAY!! 223K jobs added. Unemploymen...  280  1002602715820756993 2018-06-01 17:28:09   40487   9077   1
759  President Trump proclaims June 2018 as Great O...  190  1002595130304598016 2018-06-01 16:58:01    5415   1114   1
760  During National Homeownership Month, we affirm...  231  1002588594207383552 2018-06-01 16:32:02    3795    766   1
761  President Trump continues to bolster job creat...  158  1002585315549302784 2018-06-01 16:19:01    4919   1071   1
762  The United States is a nation whose identity, ...  276  1002584816016125954 2018-06-01 16:17:01    4473    941   0
763  “Throughout the Admirals tenure, he poured his...  221  1002580989497860096 2018-06-01 16:01:49    5350   1069   1
764  “We are gathered together today for a truly sp...  254  1002579894692265984 2018-06-01 15:57:28    5672   1086   1
765  “I am thrilled to be here with the brave men a...  246  1002578420306345985 2018-06-01 15:51:37    9402   1805   1
766  President Trump participates in the U.S. Coast...  144  1002565818696327168 2018-06-01 15:01:32    4322    875   1
767  Under President Donald J. Trump, the US unempl...  189  1002563670306672640 2018-06-01 14:53:00    7268   1819   1
768  President Trump Proclaims June 2018 as Nationa...  106  1002550752127135744 2018-06-01 14:01:40    3536    685   0
769  At 3.8%, the unemployment rate has fallen to i...  288  1002558333973393408 2018-06-01 14:31:48   12898   3026   1
770  Jobs! Jobs! Jobs! Once again, the economy is g...  225  1002548108755075074 2018-06-01 13:51:10   17077   3980   1
771  Looking forward to seeing the employment numbe...   70  1002510522032541701 2018-06-01 11:21:48   75725  11371   0
772  Lucia Mutikani in Reuters: "U.S. consumer spen...  192  1002314283663941632 2018-05-31 22:22:01    3210    750   1
773  The U.S. condemns the attacks by pro-governmen...  310  1002312027598217216 2018-05-31 22:13:04    7096   2072   1

Percentage of positive tweets: 60.51282051282051%
Percentage of neutral tweets: 23.974358974358974%
Percentage de negative tweets: 15.512820512820513%


Detected 116 mentions.

Hillary sentiment:                             0
Trump sentiment:                               0.07870129870129869
Cruz sentiment:                                0
Bernie sentiment:                              0
Obama sentiment:                               0
Rpublican sentiment:                           0
Democrat sentiment:                            0
Guns sentiment:                                0
Immigration sentiment:                         0.07575732734614314
Employment sentiment:                          0.21539018334606566
Inflation sentiment:                           0
Minimum Wage Up sentiment:                     0
Abortion sentiment:                            0
Govenment Spending sentiment:                  0
Taxes Up sentiment:                            0
Taxes Down sentiment:                          0.026713048855906002
Death penalty sentiment:                       0
Health care sentiment:                         0.17470238095238097
LGBT sentiment:                                0
Environment sentiment:                         0.06666666666666668
Welfare sentiment:                             0.16666666666666669
Social sentimnt:                               0
Labor Union sentiment:                         0 
Drugs sentiment:                               0.1463888888888889
War sentiment:                                 0.1733061354489926

[*] Action: Send Pro-Blank propaganda.
</pre>


### TO DO:

- Code styling, optimization. Propaganda function.

The program currently employs Textblob's default naive bayes clasifier for sentiment analysis. A far more advanced solution will be implemented soon.

---

AS SEEN IN: [Russian interference in 2016 U.S. Elections](https://en.wikipedia.org/wiki/Russian_interference_in_the_2016_United_States_elections) :grin:

