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

