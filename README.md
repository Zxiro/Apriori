**For High Support and High Conf, which means it has high freqency and correaltion. 
I set min_sup as 0.5,  min_conf as 0.75**

Start_Kaggle
{'BREAD'}  :  0.65

**With min_sup:  0.5 , min_conf:  0.75 The association rule is:  []**

Start_IBM
{'3'}  :  0.6325231481481481
{'8'}  :  0.6657021604938271
{'9'}  :  0.5810185185185185

**With min_sup:  0.5 , min_conf:  0.25 The association rule is:  []**

**As the result, there are few set that fit the support, without the set, there will be no chance to establish the rule between it.**

**For High Support and Low Conf, it doesn’t give a strict rule to connect, so it may depends on the amount of frequent set
I set min_sup 0.5,  min_conf as 0.25**

Start_Kaggle
{'BREAD'}  :  0.65

**With min_sup:  0.5 , min_conf:  0.25 The association rule is:  []**

Start_IBM
{'3'}  :  0.6325231481481481
{'8'}  :  0.6657021604938271
{'9'}  :  0.5810185185185185

**With min_sup:  0.5 , min_conf:  0.25 The association rule is:  []**

**As the result, although the threshold to establish the rule become lower, the amount of frequent set still not enough to establish the association rule**





**For Low support and High conf, which means the amount of freq will increase. However, the diffculites of establish a correlation between elements will increase too, due to the High conf**
**I set min_sup 0.1,  min_conf as 0.75**

Start_Kaggle
{'BISCUIT'}  :  0.35
{'BISCUIT', 'COCK'}  :  0.1
{'CORNFLAKES', 'BISCUIT'}  :  0.15
{'CORNFLAKES', 'BISCUIT', 'COCK'}  :  0.1
{'BISCUIT', 'MAGGI'}  :  0.1
{'MILK', 'BISCUIT'}  :  0.1
{'TEA', 'BISCUIT'}  :  0.1
{'TEA', 'BISCUIT', 'MAGGI'}  :  0.1
{'BOURNVITA'}  :  0.2
{'BREAD'}  :  0.65
{'BREAD', 'BISCUIT'}  :  0.2
{'MILK', 'BREAD', 'BISCUIT'}  :  0.1
{'BREAD', 'BOURNVITA'}  :  0.15
{'BREAD', 'COFFEE'}  :  0.15
{'SUGER', 'BREAD', 'COFFEE'}  :  0.1
{'BREAD', 'JAM'}  :  0.1
{'BREAD', 'MAGGI'}  :  0.15
{'BREAD', 'JAM', 'MAGGI'}  :  0.1
{'MILK', 'BREAD'}  :  0.2
{'SUGER', 'BREAD'}  :  0.2
{'BREAD', 'TEA'}  :  0.2
{'BREAD', 'TEA', 'BOURNVITA'}  :  0.1
{'BREAD', 'TEA', 'MAGGI'}  :  0.1
{'COCK'}  :  0.15
{'COFFEE'}  :  0.4
{'BISCUIT', 'COFFEE'}  :  0.1
{'BISCUIT', 'COFFEE', 'COCK'}  :  0.1
{'BISCUIT', 'CORNFLAKES', 'COFFEE'}  :  0.1
{'BISCUIT', 'CORNFLAKES', 'COFFEE', 'COCK'}  :  0.1
{'COFFEE', 'COCK'}  :  0.15
{'CORNFLAKES', 'COFFEE'}  :  0.2
{'CORNFLAKES', 'COFFEE', 'COCK'}  :  0.1
{'SUGER', 'COFFEE'}  :  0.2
{'CORNFLAKES'}  :  0.3
{'CORNFLAKES', 'COCK'}  :  0.1
{'MILK', 'CORNFLAKES'}  :  0.1
{'JAM'}  :  0.1
{'MAGGI'}  :  0.25
{'JAM', 'MAGGI'}  :  0.1
{'MILK'}  :  0.25
{'SUGER'}  :  0.3
{'SUGER', 'BOURNVITA'}  :  0.1
{'TEA'}  :  0.35
{'TEA', 'BOURNVITA'}  :  0.1
{'CORNFLAKES', 'TEA'}  :  0.1
{'TEA', 'MAGGI'}  :  0.2

**With min_sup:  0.1 , min_conf:  0.75 The association rule is: ["{'BISCUIT', 'COFFEE'}->{'CORNFLAKES', 'COCK'}", "{'BISCUIT'}->{'CORNFLAKES', 'COCK'}", "{'BISCUIT'}->{'CORNFLAKES', 'COFFEE', 'COCK'}", "{'BREAD', 'MAGGI'}->{'JAM'}", "{'BREAD'}->{'JAM', 'MAGGI'}", "{'BREAD'}->{'JAM'}", "{'BREAD'}->{'MILK', 'BISCUIT'}", "{'BREAD'}->{'MILK'}", "{'BREAD'}->{'TEA', 'BOURNVITA'}", "{'COCK'}->{'BISCUIT', 'COFFEE'}", "{'COCK'}->{'CORNFLAKES', 'BISCUIT', 'COFFEE'}", "{'COFFEE'}->{'BISCUIT', 'COCK'}", "{'COFFEE'}->{'COCK'}", "{'COFFEE'}->{'CORNFLAKES', 'BISCUIT', 'COCK'}", "{'COFFEE'}->{'CORNFLAKES', 'COCK'}", "{'CORNFLAKES', 'COCK'}->{'BISCUIT', 'COFFEE'}", "{'CORNFLAKES', 'COFFEE'}->{'BISCUIT', 'COCK'}", "{'CORNFLAKES'}->{'BISCUIT', 'COCK', 'COFFEE'}", "{'CORNFLAKES'}->{'BISCUIT', 'COCK'}", "{'CORNFLAKES'}->{'BISCUIT', 'COFFEE'}", "{'MAGGI'}->{'BISCUIT', 'TEA'}", "{'MAGGI'}->{'BREAD', 'JAM'}", "{'MAGGI'}->{'JAM'}", "{'TEA'}->{'BISCUIT', 'MAGGI'}", "{'TEA'}->{'MAGGI'}"]**

Start_IBM
{'0'}  :  0.3150077160493827
{'3'}  :  0.6325231481481481
{'3', '0'}  :  0.19945987654320987
{'3', '4'}  :  0.15335648148148148
{'3', '5'}  :  0.21315586419753085
{'3', '6'}  :  0.15432098765432098
{'3', '7'}  :  0.19733796296296297
{'3', '9'}  :  0.3697916666666667
{'3', '9', '0'}  :  0.11477623456790123
{'3', '5', '9'}  :  0.1284722222222222
{'3', '7', '9'}  :  0.11381172839506173
{'4'}  :  0.24440586419753085
{'5'}  :  0.3429783950617284
{'5', '0'}  :  0.10609567901234568
{'7', '5'}  :  0.11188271604938271
{'6'}  :  0.2503858024691358
{'7'}  :  0.31925154320987653
{'7', '0'}  :  0.10551697530864197
{'8'}  :  0.6657021604938271
{'8', '0'}  :  0.20794753086419754
{'3', '8'}  :  0.41087962962962965
{'3', '8', '0'}  :  0.12789351851851852
{'3', '5', '8'}  :  0.1392746913580247
{'3', '7', '8'}  :  0.1248070987654321
{'3', '8', '9'}  :  0.24498456790123457
{'4', '8'}  :  0.16300154320987653
{'5', '8'}  :  0.22608024691358025
{'6', '8'}  :  0.16338734567901234
{'7', '8'}  :  0.21064814814814814
{'8', '9'}  :  0.388695987654321
{'0', '8', '9'}  :  0.12364969135802469
{'5', '8', '9'}  :  0.13560956790123457
{'7', '8', '9'}  :  0.12094907407407407
{'9'}  :  0.5810185185185185
{'9', '0'}  :  0.18074845679012347
{'4', '9'}  :  0.14486882716049382
{'5', '9'}  :  0.2025462962962963
{'6', '9'}  :  0.14564043209876543
{'7', '9'}  :  0.18267746913580246

**With min_sup:  0.1 , min_conf:  0.75 The association rule is: []**

**As the result, there are lot sets that fit the support. Based on observation, we can easily tell the difference between concentrated dataset and sparse dataset. For the Kaggle dataset, we can find the rule, but for the IBM which is more sparse, there exist no rule between freq sets.**
**For Low support and Low conf, which means it is very easy to establish rule. However, the connection between sets may not be meaningful enough**
**I set min_sup 0.1,  min_conf as 0.25**

Start_Kaggle
{'BISCUIT'}  :  0.35
{'BISCUIT', 'COCK'}  :  0.1
{'CORNFLAKES', 'BISCUIT'}  :  0.15
{'CORNFLAKES', 'BISCUIT', 'COCK'}  :  0.1
{'BISCUIT', 'MAGGI'}  :  0.1
{'MILK', 'BISCUIT'}  :  0.1
{'TEA', 'BISCUIT'}  :  0.1
{'TEA', 'BISCUIT', 'MAGGI'}  :  0.1
{'BOURNVITA'}  :  0.2
{'BREAD'}  :  0.65
{'BREAD', 'BISCUIT'}  :  0.2
{'MILK', 'BREAD', 'BISCUIT'}  :  0.1
{'BREAD', 'BOURNVITA'}  :  0.15
{'BREAD', 'COFFEE'}  :  0.15
{'SUGER', 'BREAD', 'COFFEE'}  :  0.1
{'BREAD', 'JAM'}  :  0.1
{'BREAD', 'MAGGI'}  :  0.15
{'BREAD', 'JAM', 'MAGGI'}  :  0.1
{'MILK', 'BREAD'}  :  0.2
{'SUGER', 'BREAD'}  :  0.2
{'BREAD', 'TEA'}  :  0.2
{'BREAD', 'TEA', 'BOURNVITA'}  :  0.1
{'BREAD', 'TEA', 'MAGGI'}  :  0.1
{'COCK'}  :  0.15
{'COFFEE'}  :  0.4
{'BISCUIT', 'COFFEE'}  :  0.1
{'BISCUIT', 'COFFEE', 'COCK'}  :  0.1
{'BISCUIT', 'CORNFLAKES', 'COFFEE'}  :  0.1
{'BISCUIT', 'CORNFLAKES', 'COFFEE', 'COCK'}  :  0.1
{'COFFEE', 'COCK'}  :  0.15
{'CORNFLAKES', 'COFFEE'}  :  0.2
{'CORNFLAKES', 'COFFEE', 'COCK'}  :  0.1
{'SUGER', 'COFFEE'}  :  0.2
{'CORNFLAKES'}  :  0.3
{'CORNFLAKES', 'COCK'}  :  0.1
{'MILK', 'CORNFLAKES'}  :  0.1
{'JAM'}  :  0.1
{'MAGGI'}  :  0.25
{'JAM', 'MAGGI'}  :  0.1
{'MILK'}  :  0.25
{'SUGER'}  :  0.3
{'SUGER', 'BOURNVITA'}  :  0.1
{'TEA'}  :  0.35
{'TEA', 'BOURNVITA'}  :  0.1
{'CORNFLAKES', 'TEA'}  :  0.1
{'TEA', 'MAGGI'}  :  0.2

**With min_sup:  0.1 , min_conf:  0.25 The association rule is:  ["{'BISCUIT', 'COCK', 'COFFEE'}->{'CORNFLAKES'}", "{'BISCUIT', 'COCK'}->{'COFFEE'}", "{'BISCUIT', 'COCK'}->{'CORNFLAKES', 'COFFEE'}", "{'BISCUIT', 'COCK'}->{'CORNFLAKES'}", "{'BISCUIT', 'COFFEE'}->{'COCK'}", "{'BISCUIT', 'COFFEE'}->{'CORNFLAKES', 'COCK'}", "{'BISCUIT', 'COFFEE'}->{'CORNFLAKES'}", "{'BISCUIT', 'MAGGI'}->{'TEA'}", "{'BISCUIT', 'TEA'}->{'MAGGI'}", "{'BISCUIT'}->{'BREAD'}", "{'BISCUIT'}->{'COCK'}", "{'BISCUIT'}->{'COFFEE', 'COCK'}", "{'BISCUIT'}->{'COFFEE'}", "{'BISCUIT'}->{'CORNFLAKES', 'COCK'}", "{'BISCUIT'}->{'CORNFLAKES', 'COFFEE', 'COCK'}", "{'BISCUIT'}->{'CORNFLAKES', 'COFFEE'}", "{'BISCUIT'}->{'CORNFLAKES'}", "{'BISCUIT'}->{'MAGGI'}", "{'BISCUIT'}->{'MILK', 'BREAD'}", "{'BISCUIT'}->{'MILK'}", "{'BISCUIT'}->{'TEA', 'MAGGI'}", "{'BISCUIT'}->{'TEA'}", "{'BOURNVITA'}->{'BREAD', 'TEA'}", "{'BOURNVITA'}->{'SUGER'}", "{'BOURNVITA'}->{'TEA'}", "{'BREAD', 'BISCUIT'}->{'MILK'}", "{'BREAD', 'BOURNVITA'}->{'TEA'}", "{'BREAD', 'COFFEE'}->{'SUGER'}", "{'BREAD', 'JAM'}->{'MAGGI'}", "{'BREAD', 'MAGGI'}->{'JAM'}", "{'BREAD', 'MAGGI'}->{'TEA'}", "{'BREAD', 'TEA'}->{'BOURNVITA'}", "{'BREAD', 'TEA'}->{'MAGGI'}", "{'BREAD'}->{'BISCUIT'}", "{'BREAD'}->{'BOURNVITA'}", "{'BREAD'}->{'COFFEE'}", "{'BREAD'}->{'JAM', 'MAGGI'}", "{'BREAD'}->{'JAM'}", "{'BREAD'}->{'MAGGI'}", "{'BREAD'}->{'MILK', 'BISCUIT'}", "{'BREAD'}->{'MILK'}", "{'BREAD'}->{'SUGER', 'COFFEE'}", "{'BREAD'}->{'SUGER'}", "{'BREAD'}->{'TEA', 'BOURNVITA'}", "{'BREAD'}->{'TEA', 'MAGGI'}", "{'BREAD'}->{'TEA'}", "{'COCK'}->{'BISCUIT', 'COFFEE'}", "{'COCK'}->{'BISCUIT'}", "{'COCK'}->{'COFFEE'}", "{'COCK'}->{'CORNFLAKES', 'BISCUIT', 'COFFEE'}", "{'COCK'}->{'CORNFLAKES', 'BISCUIT'}", "{'COCK'}->{'CORNFLAKES', 'COFFEE'}", "{'COCK'}->{'CORNFLAKES'}", "{'COFFEE', 'COCK'}->{'BISCUIT'}", "{'COFFEE', 'COCK'}->{'CORNFLAKES', 'BISCUIT'}", "{'COFFEE', 'COCK'}->{'CORNFLAKES'}", "{'COFFEE'}->{'BISCUIT', 'COCK'}", "{'COFFEE'}->{'BISCUIT'}", "{'COFFEE'}->{'COCK'}", "{'COFFEE'}->{'CORNFLAKES', 'BISCUIT', 'COCK'}", "{'COFFEE'}->{'CORNFLAKES', 'BISCUIT'}", "{'COFFEE'}->{'CORNFLAKES', 'COCK'}", "{'COFFEE'}->{'CORNFLAKES'}", "{'COFFEE'}->{'SUGER', 'BREAD'}", "{'COFFEE'}->{'SUGER'}", "{'CORNFLAKES', 'BISCUIT', 'COCK'}->{'COFFEE'}", "{'CORNFLAKES', 'BISCUIT', 'COFFEE'}->{'COCK'}", "{'CORNFLAKES', 'BISCUIT'}->{'COCK'}", "{'CORNFLAKES', 'BISCUIT'}->{'COFFEE', 'COCK'}", "{'CORNFLAKES', 'BISCUIT'}->{'COFFEE'}", "{'CORNFLAKES', 'COCK'}->{'BISCUIT', 'COFFEE'}", "{'CORNFLAKES', 'COCK'}->{'BISCUIT'}", "{'CORNFLAKES', 'COCK'}->{'COFFEE'}", "{'CORNFLAKES', 'COFFEE', 'COCK'}->{'BISCUIT'}", "{'CORNFLAKES', 'COFFEE'}->{'BISCUIT', 'COCK'}", "{'CORNFLAKES', 'COFFEE'}->{'BISCUIT'}", "{'CORNFLAKES', 'COFFEE'}->{'COCK'}", "{'CORNFLAKES'}->{'BISCUIT', 'COCK', 'COFFEE'}", "{'CORNFLAKES'}->{'BISCUIT', 'COCK'}", "{'CORNFLAKES'}->{'BISCUIT', 'COFFEE'}", "{'CORNFLAKES'}->{'BISCUIT'}", "{'CORNFLAKES'}->{'COCK'}", "{'CORNFLAKES'}->{'COFFEE', 'COCK'}", "{'CORNFLAKES'}->{'COFFEE'}", "{'CORNFLAKES'}->{'MILK'}", "{'CORNFLAKES'}->{'TEA'}", "{'JAM'}->{'BREAD', 'MAGGI'}", "{'JAM'}->{'MAGGI'}", "{'MAGGI'}->{'BISCUIT', 'TEA'}", "{'MAGGI'}->{'BISCUIT'}", "{'MAGGI'}->{'BREAD', 'JAM'}", "{'MAGGI'}->{'BREAD', 'TEA'}", "{'MAGGI'}->{'JAM'}", "{'MAGGI'}->{'TEA'}", "{'MILK', 'BREAD'}->{'BISCUIT'}", "{'MILK'}->{'BISCUIT'}", "{'MILK'}->{'BREAD', 'BISCUIT'}", "{'MILK'}->{'BREAD'}", "{'MILK'}->{'CORNFLAKES'}", "{'SUGER', 'BREAD'}->{'COFFEE'}", "{'SUGER'}->{'BOURNVITA'}", "{'SUGER'}->{'BREAD', 'COFFEE'}", "{'SUGER'}->{'BREAD'}", "{'SUGER'}->{'COFFEE'}", "{'TEA', 'MAGGI'}->{'BISCUIT'}", "{'TEA'}->{'BISCUIT', 'MAGGI'}", "{'TEA'}->{'BISCUIT'}", "{'TEA'}->{'BOURNVITA'}", "{'TEA'}->{'BREAD', 'BOURNVITA'}", "{'TEA'}->{'BREAD', 'MAGGI'}", "{'TEA'}->{'BREAD'}", "{'TEA'}->{'CORNFLAKES'}", "{'TEA'}->{'MAGGI'}"]**

Start_IBM
{'0'}  :  0.3150077160493827
{'3'}  :  0.6325231481481481
{'3', '0'}  :  0.19945987654320987
{'3', '4'}  :  0.15335648148148148
{'3', '5'}  :  0.21315586419753085
{'3', '6'}  :  0.15432098765432098
{'3', '7'}  :  0.19733796296296297
{'3', '9'}  :  0.3697916666666667
{'3', '9', '0'}  :  0.11477623456790123
{'3', '5', '9'}  :  0.1284722222222222
{'3', '7', '9'}  :  0.11381172839506173
{'4'}  :  0.24440586419753085
{'5'}  :  0.3429783950617284
{'5', '0'}  :  0.10609567901234568
{'7', '5'}  :  0.11188271604938271
{'6'}  :  0.2503858024691358
{'7'}  :  0.31925154320987653
{'7', '0'}  :  0.10551697530864197
{'8'}  :  0.6657021604938271
{'8', '0'}  :  0.20794753086419754
{'3', '8'}  :  0.41087962962962965
{'3', '8', '0'}  :  0.12789351851851852
{'3', '5', '8'}  :  0.1392746913580247
{'3', '7', '8'}  :  0.1248070987654321
{'3', '8', '9'}  :  0.24498456790123457
{'4', '8'}  :  0.16300154320987653
{'5', '8'}  :  0.22608024691358025
{'6', '8'}  :  0.16338734567901234
{'7', '8'}  :  0.21064814814814814
{'8', '9'}  :  0.388695987654321
{'0', '8', '9'}  :  0.12364969135802469
{'5', '8', '9'}  :  0.13560956790123457
{'7', '8', '9'}  :  0.12094907407407407
{'9'}  :  0.5810185185185185
{'9', '0'}  :  0.18074845679012347
{'4', '9'}  :  0.14486882716049382
{'5', '9'}  :  0.2025462962962963
{'6', '9'}  :  0.14564043209876543
{'7', '9'}  :  0.18267746913580246

**With min_sup:  0.1 , min_conf:  0.25 The association rule is:  ["{'0'}->{'3', '8'}", "{'0'}->{'3', '9'}", "{'0'}->{'3'}", "{'0'}->{'5'}", "{'0'}->{'7'}", "{'0'}->{'8', '9'}", "{'0'}->{'8'}", "{'0'}->{'9'}", "{'3', '8'}->{'0'}", "{'3', '8'}->{'5'}", "{'3', '8'}->{'7'}", "{'3', '8'}->{'9'}", "{'3', '9'}->{'0'}", "{'3', '9'}->{'5'}", "{'3', '9'}->{'7'}", "{'3', '9'}->{'8'}", "{'3'}->{'0'}", "{'3'}->{'4'}", "{'3'}->{'5', '8'}", "{'3'}->{'5', '9'}", "{'3'}->{'5'}", "{'3'}->{'6'}", "{'3'}->{'7', '8'}", "{'3'}->{'7', '9'}", "{'3'}->{'7'}", "{'3'}->{'8', '0'}", "{'3'}->{'8', '9'}", "{'3'}->{'8'}", "{'3'}->{'9', '0'}", "{'3'}->{'9'}", "{'5'}->{'0'}", "{'5'}->{'3', '8'}", "{'5'}->{'3', '9'}", "{'5'}->{'3'}", "{'5'}->{'7'}", "{'5'}->{'8', '9'}", "{'5'}->{'8'}", "{'5'}->{'9'}", "{'6'}->{'9'}", "{'7'}->{'0'}", "{'7'}->{'3', '8'}", "{'7'}->{'3', '9'}", "{'7'}->{'3'}", "{'7'}->{'5'}", "{'7'}->{'8', '9'}", "{'7'}->{'8'}", "{'7'}->{'9'}", "{'8', '9'}->{'0'}", "{'8', '9'}->{'3'}", "{'8', '9'}->{'5'}", "{'8', '9'}->{'7'}", "{'8'}->{'0', '9'}", "{'8'}->{'0'}", "{'8'}->{'3', '0'}", "{'8'}->{'3', '5'}", "{'8'}->{'3', '7'}", "{'8'}->{'3', '9'}", "{'8'}->{'3'}", "{'8'}->{'4'}", "{'8'}->{'5', '9'}", "{'8'}->{'5'}", "{'8'}->{'6'}", "{'8'}->{'7', '9'}", "{'8'}->{'7'}", "{'8'}->{'9'}", "{'9'}->{'0', '8'}", "{'9'}->{'0'}", "{'9'}->{'3', '0'}", "{'9'}->{'3', '5'}", "{'9'}->{'3', '7'}", "{'9'}->{'3', '8'}", "{'9'}->{'3'}", "{'9'}->{'4'}", "{'9'}->{'5', '8'}", "{'9'}->{'5'}", "{'9'}->{'6'}", "{'9'}->{'7', '8'}", "{'9'}->{'7'}", "{'9'}->{'8'}"]**

**As the result, it fits my assumption. There have lots of association rule appear, but it may not be practical enough when it comes to the real situation.**
 

**Comparison between two algorithms runtime, I make both algorithms ran same dataset, support and confidence ten times and got the average runtime which is shown below**
| Kaggle  | IBM |
| ------------- | ------------- |
| FP 0.00120072364807  | FP 0.042574357986  |
| Ap 0.00143535137176  | Ap 0.591068458557  |


**Conclusion:**
**We can find that FP and Apriori do not have difference when dealing with the small size dataset. However, when it comes to the large size dataset, the process which generate candidate pattern comparison between it and all transaction Apriori significantly increase the runtime nearly fifteen times. Because of that, I think FP Growth tree will be a better choice to complete the association rule**
