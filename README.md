Download Link: https://assignmentchef.com/product/solved-csci5521-homework-2
<br>
<ol>

 <li>Let X = {<em>x</em><sub>1</sub><em>,…,x<sub>n</sub></em>} be a set of <em>n </em>samples drawn i.i.d. from an univariate distribution with density function <em>p</em>(<em>x</em>|<em>θ</em>), where <em>θ </em>is an unknown parameter. In general, <em>θ </em>will belong to a specified subset of R, the set of real numbers. For the following choices of <em>p</em>(<em>x</em>|<em>θ</em>), derive the maxmimum likelihood estimate of <em>θ </em>based on the samples X:<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a>

  <ul>

   <li></li>

   <li></li>

   <li><em>p</em>(<em>x</em>|<em>θ</em>) = <em>θx<sup>θ</sup></em><sup>−1 </sup><em>,</em>0 ≤ <em>x </em>≤ 1<em>,</em>0 <em>&lt; θ &lt; </em>∞.</li>

   <li><em>p</em>(<em>x</em>|<em>θ</em>) = <u><sup>1</sup></u><em><sub>θ </sub>,</em>0 ≤ <em>x </em>≤ <em>θ,θ &gt; </em></li>

  </ul></li>

 <li>Let X = {<strong>x</strong><sub>1</sub><em>,…,</em><strong>x</strong><em><sub>n</sub></em>}<em>,</em><strong>x</strong><em><sub>i </sub></em>∈ R<em><sup>d </sup></em>be a set of <em>n </em>samples drawn i.i.d. from a multivariate Gaussian distribution in R<em><sup>d </sup></em>with mean <em>µ </em>∈ R<em><sup>d </sup></em>and covariance matrix Σ ∈ R<em><sup>d</sup></em><sup>×<em>d</em></sup>. Recall that the density function of a multivariate Gaussian distribution is given by:</li>

</ol>

<em> .</em>

<ul>

 <li>Derive the maximum likelihood estimates for the mean <em>µ </em>and covariance Σ based on the sample set X.<sup>1,2</sup></li>

 <li>Let ˆ<em>µ<sub>n </sub></em>be the maximum likelihood estimate of the mean. Is ˆ<em>µ<sub>n </sub></em>a biased estimate of the true mean <em>µ</em>? Clearly justify your answer by computing <em>E</em>[<em>µ</em>ˆ<em><sub>n</sub></em>].</li>

 <li>Let Σ<sup>ˆ</sup><em><sub>n </sub></em>be the maximum likelihood estimate of the covariance matrix. Is Σ<sup>ˆ</sup><em><sub>n </sub></em>a biased estimate of the true covariance Σ? Clearly justify your answer by computing</li>

</ul>

<em>E</em>[Σ<sup>ˆ</sup><em><sub>n</sub></em>].

<ol start="3">

 <li>Table 1 specifies the misclassification costs for a 3-class problem including a ‘Reject’ option. Assume that a model has been trained using training data, and the model can output posterior probabilities <em>P</em>(<em>C</em><sub>1</sub>|<em>x</em><sub>test</sub>)<em>,P</em>(<em>C</em><sub>2</sub>|<em>x</em><sub>test</sub>)<em>,P</em>(<em>C</em><sub>3</sub>|<em>x</em><sub>test</sub>) for any given test point <em>x</em>test.

  <ul>

   <li>Assume <em>λ </em>= 10. For a given <em>x</em><sub>test</sub>, let the posterior probabilities for the three classes be: <em>P</em>(<em>C</em><sub>1</sub>|<em>x</em><sub>test</sub>) = 0<em>.</em>5<em>,P</em>(<em>C</em><sub>2</sub>|<em>x</em><sub>test</sub>) = 0<em>.</em>25<em>,P</em>(<em>C</em><sub>3</sub>|<em>x</em><sub>test</sub>) = 0<em>.</em> Using Table 1, compute the risks for predicting <em>x </em>to be <em>C</em><sub>1</sub>, <em>C</em><sub>2</sub><em>,C</em><sub>3</sub><em>, </em>and ‘Reject’ respectively. Including ‘Reject’ as a possible option, what would your predicted class for <em>x</em><sub>test </sub>be? You have to show details of your computation and justify your answer.</li>

  </ul></li>

</ol>

Predicted Class

<table width="222">

 <tbody>

  <tr>

   <td width="14"></td>

   <td width="209">


    <table width="208">

     <tbody>

      <tr>

       <td width="34"></td>

       <td width="39"><em>C</em><sub>1</sub></td>

       <td width="38"><em>C</em><sub>2</sub></td>

       <td width="33"><em>C</em><sub>3</sub></td>

       <td width="64">‘Reject’</td>

      </tr>

      <tr>

       <td width="34"><em>C</em><sub>1</sub></td>

       <td width="39">0</td>

       <td width="38">1</td>

       <td width="33">1</td>

       <td width="64"><em>λ</em></td>

      </tr>

      <tr>

       <td width="34"><em>C</em><sub>2</sub></td>

       <td width="39">10</td>

       <td width="38">0</td>

       <td width="33">10</td>

       <td width="64"><em>λ</em></td>

      </tr>

      <tr>

       <td width="34"><em>C</em><sub>3</sub></td>

       <td width="39">100</td>

       <td width="38">100</td>

       <td width="33">0</td>

       <td width="64"><em>λ</em></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

Table 1: Misclassification costs for a 3-class problem including a ‘Reject’ option.

<ul>

 <li>Assume <em>λ </em>= 5. For a given <em>x</em><sub>test</sub>, let the posterior probabilities for the three classes be: <em>P</em>(<em>C</em><sub>1</sub>|<em>x</em><sub>test</sub>) = 0<em>.</em>4<em>,P</em>(<em>C</em><sub>2</sub>|<em>x</em><sub>test</sub>) = 0<em>.</em>5<em>,P</em>(<em>C</em><sub>3</sub>|<em>x</em><sub>test</sub>) = 0<em>.</em> Using Table 1, compute the risks for predicting <em>x </em>to be <em>C</em><sub>1</sub>, <em>C</em><sub>2</sub><em>,C</em><sub>3</sub><em>, </em>and ‘Reject’ respectively. Including ‘Reject’ as a possible option, what would your predicted class for <em>x</em><sub>test </sub>be? You have to show details of your computation and justify your answer.</li>

</ul>

<strong>Programming assignment:</strong>

The next problem involves programming. For Question 3, we will be using the 2-class classification datasets from Boston50, Boston75, and the 10-class classification dataset from Digits which were used in Homework 1.

<ol start="3">

 <li>We will develop two parametric classifiers by modeling each class’s conditional distribution <em>p</em>(<strong>x</strong>|<em>C<sub>i</sub></em>) as multivariate Gaussians with (a) full covariance matrix Σ<em><sub>i </sub></em>and (b) diagonal covariance matrix Σ<em><sub>i</sub></em>. In particular, using the training data, we will compute the maximum likelihood estimate of the class prior probabilities <em>p</em>(<em>C<sub>i</sub></em>) and the class conditional probabilities <em>p</em>(<em>x</em>|<em>C<sub>i</sub></em>) based on the maximum likelihood estimates of the mean ˆ<em>µ<sub>i </sub></em>and the (full/diagonal) covariance Σ<sup>ˆ</sup><em><sub>i </sub></em>for each class <em>C<sub>i</sub></em>. The classification will be done based on the following discriminant function:</li>

</ol>

<em>g<sub>i</sub></em>(<strong>x</strong>) = log<em>p</em>(<em>C<sub>i</sub></em>) + log<em>p</em>(<strong>x</strong>|<em>C<sub>i</sub></em>) <em>.</em>

We will develop code for a class MultiGaussClassify with two key functions:

MultiGaussClassify.fit(self,X,y,diag) and MultiGaussClassify.predict(self,X).

For fit(self,X,y,diag), the inputs (<em>X,y</em>) are respectively the feature matrix and class labels, and diag is boolean (TRUE or FALSE) which indicates whether the estimated class covariance matrices should be a full matrix (diag=FALSE) or a diagonal matrix (diag=TRUE).

For predict(X), the input <em>X </em>is the feature matrix corresponding to the test set and the output should be the predicted labels for each point in the test set.

For the class, the init (self,k,d) function can initialize the parameters for each class to be uniform prior, zero mean, and identity covariance, i.e., <em>p</em>(<em>C<sub>i</sub></em>) = 1<em>/k</em>, <em>µ<sub>i </sub></em>= <strong>0 </strong>and Σ<em><sub>i </sub></em>= I, <em>i </em>= 1<em>,…,k</em>. Here, the number of classes <em>k </em>and the dimensionality <em>d </em>of features is passed as an argument to the constructor of MultiGaussClassify.

We will compare the performance of three models:

<ul>

 <li>MultiGaussClassify with full class covariance matrices,</li>

 <li>MultiGaussClassify with diagonal covariance matrices, and</li>

 <li>LogisticRegression<a href="#_ftn2" name="_ftnref2"><sup>[2]</sup></a></li>

</ul>

applied to three datasets: Boston50, Boston75, and Digits. Using my cross val with 5-fold cross-validation, report the error rates in each fold as well as the mean and standard deviation of error rates across folds for the three models applied to the three classification datasets You will have to submit (a) <strong>code </strong>and (b) <strong>summary of results</strong>:

(a) <strong>Code</strong>: You will have to submit code for MultiGaussClassify as well as a wrapper code hw2q3(). For the class, please use the following template: class MultiGaussClassify:

def init (self, k, d):

… def fit(self, X, y, diag=False):

… def predict(self, X):

…

Your class MultiGaussClassify <strong>should not </strong>inherit any base class in sklearn. Again, the three functions you must implement in the MultiGaussClassify class are init , fit, and predict.

<strong>The wrapper code </strong>hw2q3() (main file) has no input and is used to prepare the datasets, and make calls to my cross val(method,<em>X</em>,<strong>y</strong>,<em>k</em>) to generate the error rate results for each dataset and each method. The code for my cross val(method,<em>X</em>,<strong>y</strong>,<em>k</em>) must be yours (e.g., code you developed in HW1 with modifications as needed) and you cannot use cross val score() in sklearn. For the method argument in my cross val, you can call the method corresponding to MultiGaussClassify with full covariance matrix as just ‘multigaussclassify’ and the method corresponding to MultiGaussClassify with diagonal covariance matrix as ‘multigaussdiagclassify.’

The results should be printed to terminal (not generating an additional file in the folder). Make sure the calls to my cross val(method,<em>X</em>,<strong>y</strong>,<em>k</em>) are made in the following order and add a print to the terminal before each call to show which method and dataset is being used:

<ol>

 <li>MultiGaussClassify with full covariance matrix on Boston50,</li>

 <li>MultiGaussClassify with full covariance matrix on Boston75,</li>

 <li>MultiGaussClassify with full covariance matrix on Digits,</li>

 <li>MultiGaussClassify with diagonal covariance matrix on Boston50,</li>

 <li>MultiGaussClassify with diagonal covariance matrix on Boston75,</li>

 <li>MultiGaussClassify with diagonal covariance matrix on Digits,</li>

 <li>LogisticRegression with Boston50,</li>

 <li>LogisticRegression with Boston75, and</li>

 <li>LogisticRegression with Digits.</li>

</ol>

For example, the first call to my cross val(method,<em>X</em>,<strong>y</strong>,<em>k</em>) should result in the following output:

Error rates for MultiGaussClassify with full covariance matrix on Boston50:

Fold 1: ###

Fold 2: ###

…

Fold 5: ###

Mean: ###

Standard Deviation: ###

(b) <strong>Summary of results</strong>: For each dataset and each method, report the test set error rates for each of the <em>k </em>= 5 folds, the mean error rate over the <em>k </em>folds, and the standard deviation of the error rates over the <em>k </em>folds. Make a table to present the results for each method and each dataset (9 tables in total). Each column of the table represents a fold, and add two columns at the end to show the overall mean error rate and standard deviation over the <em>k </em>folds. For example:

<table width="364">

 <tbody>

  <tr>

   <td colspan="7" width="364">Error rates for MGC with full cov matrix on Boston50</td>

  </tr>

  <tr>

   <td width="56">Fold 1</td>

   <td width="56">Fold 2</td>

   <td width="56">Fold 3</td>

   <td width="56">Fold 4</td>

   <td width="56">Fold 5</td>

   <td width="51">Mean</td>

   <td width="35">SD</td>

  </tr>

  <tr>

   <td width="56">#</td>

   <td width="56">#</td>

   <td width="56">#</td>

   <td width="56">#</td>

   <td width="56">#</td>

   <td width="51">#</td>

   <td width="35">#</td>

  </tr>

 </tbody>

</table>

<a href="#_ftnref1" name="_ftn1">[1]</a> You have to show the details of your derivation. A correct answer without the details will not get any credit. <sup>2</sup>You can use material from the Matrix Cookbook and/or the textbook for your derivation.

<a href="#_ftnref2" name="_ftn2">[2]</a> You should use LogisticRegression from scikit-learn, similar to HW1.