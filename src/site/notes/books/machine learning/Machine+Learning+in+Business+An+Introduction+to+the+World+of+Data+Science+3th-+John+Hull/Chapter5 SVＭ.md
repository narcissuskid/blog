---
{"dg-publish":true,"permalink":"/books/machine-learning/machine-learning-in-business-an-introduction-to-the-world-of-data-science-3th-john-hull/chapter5-sv/"}
---

### classification
target: [[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^uyb9hosay0n\|fit  the largest possible pathway between two classes while limiting violations,]]
object function:
[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^lgoscrzyfg\|𝐶∑𝑧𝑖𝑛𝑖=1+∑𝑤𝑗2]]

[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^mh2icfs49e\|One advantage of an SVM is that it works well when there are a large number of features. ]]
[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^bmmjgj52pyc\|we can stop this happening and keep the weights  small  by  finding  the  widest  pathway  separating  the  observa-tions]]
[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^lxym8rhn63\|maximizing  the  width  of  the  pathway  is  the  same  as minimizing  √𝑤12 +𝑤22,  or  equivalently  minimizing  𝑤12 +𝑤2  2 .    This  ex-plains the point made earlier that maximizing the width of the pathway is a form of regularization.]]
[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^njhnns6aq\|The problem is then referred to as soft margin classification and there is a trade-off between the width of the pathway (which is a measure of the amount of regularization) and the severity of violations. As the pathway becomes wider the violations become greater.  ]]
approach to find non-linear boundary: [[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^u3igooy2tre\|The general approach to finding a non-linear  boundary  is  to  create  new  features  so  that  the  linear  model presented so far in this chapter can be used]]
create new featuers:
1. [[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^axt4m9h5vcp\|powers  of  existing  features]]
2. [[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^epwt9eipb4\| Gaussian  radial  bias  function  (RBF). ]]
### regression
target: [[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^8gzb5ngdw3j\|find a pathway with a pre-specified width that contains as many of the observations as possible]]
object function:
[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^t65640463kk\|𝐶∑𝑧𝑖𝑛𝑖=1+∑𝑤𝑗2]]
difference between svm and simple linear regression:
[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^t8hnrd4pmug\|The  relationship  between  the  target  and  the  features  is  repre-sented by a pathway rather than a single line.  The prediction error is counted as zero when  an observation lies within the pathway.]]