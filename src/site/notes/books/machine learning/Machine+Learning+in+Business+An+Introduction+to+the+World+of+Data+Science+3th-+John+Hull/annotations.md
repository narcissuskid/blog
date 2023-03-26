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



>
>*me is unrealistic.  Typical-ly, ==a realistic objective is to find a model that agrees with human judge-ment 70% of the time.== 9.2   Pre-Processing  Suppose*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^hey1rlumu85\|show annotation]]
>
>
>
>{ #hey1rlumu85}



>
>*“argu”. A related procedure is ==lemmatization== .  This  uses  a look up table t*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^ks0xtj1ejj\|show annotation]]
>
>
>
>{ #ks0xtj1ejj}



>
>*olves what  is referred  to as ==stemming== . This is the removal of suffice*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^31z3j1kjagh\|show annotation]]
>
>
>
>{ #31z3j1kjagh}



>
>*to  remove  what  are  termed ==stop  words.== These  are words like “the”, “*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^8471ns6i1eg\|show annotation]]
>
>
>
>{ #8471ns6i1eg}



>
>*vert all up-per case characters ==to lower case== . It  is  common  to  remove  wh*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^xxkxlcruav8\|show annotation]]
>
>
>
>{ #xxkxlcruav8}



>
>*nd an appropriate root word. ==Correcting spelling mistakes== is desirable because it avoids d*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^nl4agv8in0b\|show annotation]]
>
>
>
>{ #nl4agv8in0b}



>
>*ence.  It  is also important to ==recognize abbreviations.== For example, “u” in a text mess*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^mxw495fm4n\|show annotation]]
>
>
>
>{ #mxw495fm4n}



>
>*may  also  be  appropriate  to ==remove  rare  words== that  appear  only once  or  tw*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^xyp4nck814l\|show annotation]]
>
>
>
>{ #xyp4nck814l}



>
>*one  positive  word?  There  is ==some  re-search indicating that the repetition of a word provides little additional information== .6   The  bag-of-words  model  t*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^78hj1cnf9ba\|show annotation]]
>
>
>
>{ #78hj1cnf9ba}



>
>*additional information.6   The ==bag-of-words  model  takes  no  account  of  the  order  of  words== .  It just  counts  the  words.*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^rue3feq7du9\|show annotation]]
>
>
>
>{ #rue3feq7du9}



>
>*. One possible improvement is to ==consider word pairs== as positive or negative. In the*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^ky0amq9yh28\|show annotation]]
>
>
>
>{ #ky0amq9yh28}



>
>*tive words is referred to as an ==n-gram== .  One word is a unigram, two co*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^ss06a4oxquo\|show annotation]]
>
>
>
>{ #ss06a4oxquo}



>
>*is  obtained,  is  known  as ==Laplace  smoothing== .  In  this  case  we can imagin*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^4ekvnmmspct\|show annotation]]
>
>
>
>{ #4ekvnmmspct}



>
>*er has the advantage that it is ==easy to imple-ment  and  very  fast.== However,  the  independence  a*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^6ay6xs0xtin\|show annotation]]
>
>
>
>{ #6ay6xs0xtin}



>
>*and  very  fast.  However,  the ==independence  assumption== is  imper-fect because some wo*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^wiahewlwsks\|show annotation]]
>
>
>
>{ #wiahewlwsks}



>
>*ïve Bayes  classifier that  it ==does  not  make the independence assumption.== Decision trees and neural netw*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^re9jnq153lq\|show annotation]]
>
>
>
>{ #re9jnq153lq}



>
>*s that  are  commonly  used  are ==term  frequency  (TF)== and  inverse  document frequenc*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^rx2hprtvr0n\|show annotation]]
>
>
>
>{ #rx2hprtvr0n}



>
>*are  term  frequency  (TF)  and ==inverse  document frequency (IDF)== . The TF for a document and a wo*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^k9tdiba81fo\|show annotation]]
>
>
>
>{ #k9tdiba81fo}



>
>*mation retrieval algorithm, the ==order of the words input by the user makes no difference== .   9.7   Other NLP Applications*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^u0bynlbshop\|show annotation]]
>
>
>
>{ #u0bynlbshop}



>
>*r  application  of  NLP  is  to ==word  sequences.== It  asks  the  ques-tion:  Wha*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^nhi8oem0a4m\|show annotation]]
>
>
>
>{ #nhi8oem0a4m}



>
>*at we have to do in practice is ==break the sentence down into subsequences of words== . For example, we might consider*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^m0rjldteuh\|show annotation]]
>
>
>
>{ #m0rjldteuh}



>
>*s mentioned in Chapter 1, uses a ==long short-term memory re-current  neural  network== (see  Section  7.5).  This  pr*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^gwp9t5lgv4\|show annotation]]
>
>
>
>{ #gwp9t5lgv4}



>
>*This involves  such  tasks  as ==separating  out  the  words,  eliminating  punctua-tion,  changing  upper  case  letters  to  lower  case,  removing  commonly occurring words, and removing words that are very rare.== The result is a vocabulary of*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^intxws2zjg\|show annotation]]
>
>
>
>{ #intxws2zjg}



>
>*ion. Among the machine learning ==models that can be used are the naïve Bayes classifier, SVM, logistic re-gression, decision trees, and neural networks== .   Search  engines  are  an  in*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^0buh45qnq2cs\|show annotation]]
>
>
>
>{ #0buh45qnq2cs}



>
>*terpretation.  Models  such  as ==neural  networks,  SVM,  and  ensemble  models  are  in the  black-box  category.== There  is  no  easy  way  to  u*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^zy5o7996e3\|show annotation]]
>
>
>
>{ #zy5o7996e3}



>
>*an easy interpretation. It  is ==the value of the tar-get  when  all  features  have  their  average  values.== It  is  also  the  average v*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^nmdbohxrwb\|show annotation]]
>
>
>
>{ #nmdbohxrwb}



>
>*𝑋̅1 +𝑏2𝑋̅2 +⋯+𝑏𝑚𝑋̅𝑚 This ==bias== does have an easy interpretatio*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^5kw35cgxxjg\|show annotation]]
>
>
>
>{ #5kw35cgxxjg}



>
>*ression models are implemented. ==R-squared i== s an indication of the overall p*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^0737v3ddc0sx\|show annotation]]
>
>
>
>{ #0737v3ddc0sx}



>
>*much it can be relied upon. The ==t-statistics== for the weights can be used to p*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^a3xznvuhlkm\|show annotation]]
>
>
>
>{ #a3xznvuhlkm}



>
>*weights can be used to provide ==con-fidence limits for the sensitivities== . Suppose bj is 10 with a t-stat*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^q1bn4129m8\|show annotation]]
>
>
>
>{ #q1bn4129m8}




>
>*nsidering changes. Sometimes, a ==principal  components  analysis  or  an  autoencoder  can  suggest  a  way  to redefine the features so that they are independent== (or nearly independ-ent).  10.2*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^jcnc5o7twhq\|show annotation]]
>
>
>
>{ #jcnc5o7twhq}



>
>*In  a  particular  situation,  t ==he  impact  of  feature  j  can  be  determined changing  feature  j  while  keeping  all  features  except  feature  j  fixed.== An extension  of  this  idea*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^xo37touoq5\|show annotation]]
>
>
>
>{ #xo37touoq5}



>
>*on  of  this  idea  is  where  t ==wo  features  are  considered  simultane-ously so that a three-dimensional plot is obtained.== To  provide  an  overall  unde*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^917i14wmtku\|show annotation]]
>
>
>
>{ #917i14wmtku}



>
>*ion of  xj. This is known as  a ==partial dependence plot== . (In the case of linear regress*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^18srexivpve\|show annotation]]
>
>
>
>{ #18srexivpve}



>
>*plicated  calculation  of  the ==contributions  of  features== leads  to  a  result  where  th*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^moskigtw6\|show annotation]]
>
>
>
>{ #moskigtw6}



>
>*However,  what  are  known  as ==Shapley  values== show that  a  more  complicated*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^1fmseg6p8r2\|show annotation]]
>
>
>
>{ #1fmseg6p8r2}



>
>*e have  just illus-trated that t ==he sum of the contributions equals the total change.== Others are:   If a feature nev*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^klv6uorjli8\|show annotation]]
>
>
>
>{ #klv6uorjli8}



>
>*edictions  are different (i.e., ==the benchmark does not have to be a prediction based on average feature values== ). However, they have a limited*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^7xjdzz8x6xp\|show annotation]]
>
>
>
>{ #7xjdzz8x6xp}



>
>*e values). However, they have a ==limited ability to explain the  workings  of  the  model  as  a  whole== .  Also,  interactions  between*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^r2vdp65thsk\|show annotation]]
>
>
>
>{ #r2vdp65thsk}



>
>*pproach is computationally very ==time consum-ing== when there are many features..1*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^mgb6esvc03\|show annotation]]
>
>
>
>{ #mgb6esvc03}



>
>*xplained using the new  model. ==The  samples  can  be  weighted  according  to  their  closeness to the current  values of the features.== The new model will often  conta*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^tv4xgtcfdq\|show annotation]]
>
>
>
>{ #tv4xgtcfdq}



>
>*he features. The new model will ==often  contain less features== than the original model (e.g.,*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^f08o40asa3m\|show annotation]]
>
>
>
>{ #f08o40asa3m}



>
>*p-pears  in  negative opinions. ==If the  jth  word  in the  vocabulary  is not  in  a particular  opinion,  we  define  pj  as  the  probability  that  word  j  does  not appear in positive opinions== and qj as  the probability it  d*
>[[books/machine learning/Machine+Learning+in+Business+An+Introduction+to+the+World+of+Data+Science+3th-+John+Hull/annotations#^0w8mnh70fgq\|show annotation]]
>
>
>
>{ #0w8mnh70fgq}

