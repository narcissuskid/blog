---
{"dg-publish":true,"permalink":"/books/machine-learning/machine-learning-in-business-an-introduction-to-the-world-of-data-science-3th-john-hull/annotations/"}
---




>
>*the value of a target variable. ==One advantage of an SVM is that it works well when there are a large number of features.== In fact, the num-ber  of  featur*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^mh2icfs49e\|show annotation]]
>
>
>
>{ #mh2icfs49e}



>
>*other feature. As we will show, ==we can stop this happening and keep the weights  small  by  finding  the  widest  pathway  separating  the  observa-tions== .*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^bmmjgj52pyc\|show annotation]]
>
>
>
>{ #bmmjgj52pyc}



>
>*√𝑤12 +𝑤22  This  shows  that ==maximizing  the  width  of  the  pathway  is  the  same  as minimizing  √𝑤12 +𝑤22,  or  equivalently  minimizing  𝑤12 +𝑤2  2 .    This  ex-plains the point made earlier that maximizing the width of the pathway is a form of regularization.== Define  𝑏=𝑏𝑢 +𝑏𝑑2   so tha*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^lxym8rhn63\|show annotation]]
>
>
>
>{ #lxym8rhn63}



>
>*he wrong side of the pathway). ==The problem is then referred to as soft margin classification and there is a trade-off between the width of the pathway (which is a measure of the amount of regularization) and the severity of violations. As the pathway becomes wider the violations become greater.== Continuing  with  the  notation*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^njhnns6aq\|show annotation]]
>
>
>
>{ #njhnns6aq}



>
>*the  center  of  the pathway. ==The pathway becomes wider indicating the there is more reg-ularization== .  When  it  is  decreased  agai*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^ny2q1obbx0a\|show annotation]]
>
>
>
>{ #ny2q1obbx0a}



>
>*The  example  illustrates  that ==the  value  of  C determines the trade-off between the amount of regularization and the extent of the violations== . This baby example shows that S*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^zwu4rkkgul\|show annotation]]
>
>
>
>{ #zwu4rkkgul}



>
>*better than a linear boundary. ==The general approach to finding a non-linear  boundary  is  to  create  new  features  so  that  the  linear  model presented so far in this chapter can be used== .   Figure  5.5      Example  of*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^u3igooy2tre\|show annotation]]
>
>
>
>{ #u3igooy2tre}




>
>*dditional  features  that  are ==powers  of  existing  features== .  For  example, using  age  and*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^axt4m9h5vcp\|show annotation]]
>
>
>
>{ #axt4m9h5vcp}



>
>*by using what  is  known  as  a ==Gaussian  radial  bias  function  (RBF).== Suppose  that there are m featu*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^epwt9eipb4\|show annotation]]
>
>
>
>{ #epwt9eipb4}



>
>*limiting violations, we try to ==find a pathway with a pre-specified width that contains as many of the observations as possible== .  Consider a simple situation w*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^8gzb5ngdw3j\|show annotation]]
>
>
>
>{ #8gzb5ngdw3j}



>
>*gression.  Instead of trying to ==fit  the largest possible pathway between two classes while limiting violations,== we try to find a pathway with a*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^uyb9hosay0n\|show annotation]]
>
>
>
>{ #uyb9hosay0n}



>
>*e function to be minimized is ==𝐶∑𝑧𝑖𝑛𝑖=1+∑𝑤𝑗2== *
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^lgoscrzyfg\|show annotation]]
>
>svm classification object function
>
>{ #lgoscrzyfg}



>
>*inimized in SVM regression is ==𝐶∑𝑧𝑖𝑛𝑖=1+∑𝑤𝑗2== *
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^t65640463kk\|show annotation]]
>
>svm regression object function
>
>{ #t65640463kk}



>
>*e  linear regression because   ==The  relationship  between  the  target  and  the  features  is  repre-sented by a pathway rather than a single line.  The prediction error is counted as zero when  an observation lies within the pathway.== *
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^t8hnrd4pmug\|show annotation]]
>
>difference between svm and simple linear regression
>
>
>{ #t8hnrd4pmug}



>
>*Chapter 5     ==Errors for observations outside the pathway are calculated as the difference  between  the  target  value  and  the  closest  point  in  the pathway that is consistent with the feature values.  There is usually some regularization built into the objective func-tion.== Figure  5.8      Results  for*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^ndt939md7co\|show annotation]]
>
>
>
>{ #ndt939md7co}



>
>*he ith observation, we define: ==𝑧𝑖 =max(𝑏+1−∑𝑤𝑗𝑥𝑖𝑗𝑚𝑗=1,0)   if positive outcome   𝑧𝑖 =max(∑𝑤𝑗𝑥𝑖𝑗𝑚𝑗=1−(𝑏−1),0)   if negative outcome== The variable zi is a measure of*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^hy6afmc2pn9\|show annotation]]
>
>
>
>{ #hy6afmc2pn9}



>
>*by trial and error.  Typically, ==the size of the network is increased until  it  is found that further increases  produce  little increase in accuracy.== A neural network can easily giv*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^n5kaeylfxy\|show annotation]]
>
>how to set the size of the network
>
>
>{ #n5kaeylfxy}



>
>*s later in this chapter.   6.3 ==Other Activation Functions== The  sigmoid  function  𝑓(𝑦)=*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^e51q34rld7n\|show annotation]]
>
>
>
>{ #e51q34rld7n}



>
>*Method  As  already  indicated, ==neural  networks  learn  more  efficiently  when the features being input are scaled== using one of the methods in Sect*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^494sya1ce6\|show annotation]]
>
>neural networks need to scale features
>
>{ #494sya1ce6}



>
>*a minimum in many  dimensions. ==Variations  on  the  basic  gradient  descent  algorithm== have  been  developed  to  impr*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^xqsydej5xxs\|show annotation]]
>
>
>
>{ #xqsydej5xxs}



>
>*his calculates a gradient as an ==exponentially  decaying  moving  average  of  past  gradients== .  This approach  helps  to  spe*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^ide35ipho3\|show annotation]]
>
>
>
>{ #ide35ipho3}



>
>*tern of implied volatilities. ==Understanding  how  the  volatility  surface  moves  is  important  for  a number of reasons:==  It can help a trader hedge e*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^opzsvrg2bt9\|show annotation]]
>
>
>
>{ #opzsvrg2bt9}



>
>*ayer, and T targets, there are ==(F + 1)M + M(M + 1)(H − 1) + (M + 1)T== parameters  in  total.    For*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^6gqr6tkku2l\|show annotation]]
>
>computer the number of parameters
>
>{ #6gqr6tkku2l}



>
>*ised  learning.    It  explains ==autoencoders,  which  are a  form of  unsuper-vised learning where the objective is to  replace  a set of features with a smaller  number  of  manufactured  features  that  provide  similar  infor-mation.== It then moves on to cover varia*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^o0orhiqyq28\|show annotation]]
>
>
>
>{ #o0orhiqyq28}



>
>*vides  an  il-lustration of the ==exploitation vs. exploration trade-off which is central to reinforcement  learning.== We  then  move  on  to  conside*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^hmtd0dr5fmf\|show annotation]]
>
>
>
>{ #hmtd0dr5fmf}



>
>*popular approach is to choose a ==decay factor, ,== and set   ε=β𝑡−1  on trial t.*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^n9sozny27m\|show annotation]]
>
>
>
>{ #n9sozny27m}



>
>*179 ==Two  hyperparameters  in  reinforcement  learning  are  the  parameter in  equation  (8.3)  and  the  decay  factor  .== Typically,  both  are  deter-mi*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^lfi1u24wvi\|show annotation]]
>
>
>
>{ #lfi1u24wvi}



>
>*le of one million.  There  are ==three  state  variables== .  One  is  current  bid-mid  sp*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^45j3cve2gf6\|show annotation]]
>
>
>
>{ #45j3cve2gf6}



>
>*variables.  One  is  current ==bid-mid  spread== .  A second  is the  number  sha*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^sfapn8iezwj\|show annotation]]
>
>
>
>{ #sfapn8iezwj}



>
>*mid  spread.  A second  is the ==number  shares== (measured  in  millions) that*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^8q5ckyviqi7\|show annotation]]
>
>
>
>{ #8q5ckyviqi7}



>
>*to  be sold. The third is the ==number of days left== .    The action is the number of*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^hmok1g6q28e\|show annotation]]
>
>
>
>{ #hmok1g6q28e}

