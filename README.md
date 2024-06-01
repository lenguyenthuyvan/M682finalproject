This is my very first project on Machine Learning. In M682 course, we were introduced to Python language. 
I chose to learn scikit-learn which I used to work on a classification model (Stroke prediction).

For studying purpose, in this project, I used 2 ways of cleaning the data to see the difference.
Here are some thoughts of mine during my learning process.

* In file "finalproject", I clean the data before putting it in the pipelines and got about 95% accuracy.
  I was very happy with it but then I realized that I did clean the data again in the pipelines. I was worried about overcleaning issue.
  Let's look at one of confusion matrices below
  [[977   1] 
  [ 42   2]]
  It looks like we missed quite a lot of people with stroke history. 

* In file "finalproject_VanLe", I only cleaned the inside the pipelines. I tried to avoid overcleaning problem.
  As I expected, the results do not look good. The accuracy was only 85%.
  Let's look at one of confusion matrices below
  [[829 149]
  [ 21  23]]
  Now it can predict people with stroke history better. However, that leads to the decline in the accuracy of no stroke cases.

 Hopefully, future projects will give me more ideas on how to deal with this type of problem.
 Maybe having a more appropriate model, a better pipeline or/and a different perspective when I look back to this.
