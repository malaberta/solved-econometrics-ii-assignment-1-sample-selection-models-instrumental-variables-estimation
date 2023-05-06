Download Link: https://assignmentchef.com/product/solved-econometrics-ii-assignment-1-sample-selection-models-instrumental-variables-estimation
<br>
The dataset logEarnings.dta(.csv) contains information on earnings of workers, the years of schooling, age, the square of age, marriage status of the worker, an indicator based on the distance between the secondary school and the residence of the individual while at school-going age and an indicator depending on regional subsidies of families for covering school expenses. A higher value for the first indicator implies a higher distance. Similarly, a higher indicator for the latter indicator implies higher regional subsidies.

<table width="462">

 <tbody>

  <tr>

   <td width="122">Variable name</td>

   <td width="340">Description</td>

  </tr>

  <tr>

   <td width="122">age</td>

   <td width="340">age</td>

  </tr>

  <tr>

   <td width="122">age2</td>

   <td width="340">square of age</td>

  </tr>

  <tr>

   <td width="122">distance</td>

   <td width="340">distance between secondary school and residence</td>

  </tr>

  <tr>

   <td width="122">married</td>

   <td width="340">1 if married, 0 if not</td>

  </tr>

  <tr>

   <td width="122">schooling</td>

   <td width="340">years of schooling</td>

  </tr>

  <tr>

   <td width="122">subsidy</td>

   <td width="340">regional subsidy for school expenses</td>

  </tr>

  <tr>

   <td width="122">logWage</td>

   <td width="340">log of earnings</td>

  </tr>

 </tbody>

</table>

<ol>

 <li><strong>The sample selection model. </strong>A researcher aims to gain insight in the potential earnings of the non-employed. (In the data, the non-employed can be identified by a missing value for the earnings variable). She realizes that the sample of observed wages may be subject to sample selection.

  <ul>

   <li>Run an OLS regression for log-earnings on schooling, age, and agesquared. Present the results and comment on the estimates.</li>

   <li>Briefly discuss the sample selection problem that may arise in usingthese OLS estimates for the purpose of predicting the potential earnings of the non-employed. Formulate the sample selection model. In your answer, include an explanation wht OLS may fail in this context.</li>

   <li>Which variable in your data may be a suitable candidate as an exclusion restriction for the sample selection model?</li>

   <li>Estimate the sample selection model with the Heckman two-step estimator, both with and without the exclusion restriction and compare the outcomes.</li>

   <li>Estimate the sample selection model with Maximum Likelihood, bothwith and without the exclusion restriction and compare the outcomes.</li>

   <li>On the basis of your results, how would you specify the distributionof potential earnings for the non-employed?</li>

  </ul></li>

 <li><strong>Earnings and schooling. </strong>The same researcher is interested in estimating the causal effect of schooling on earnings for employed individuals only. As a consequence, she performs the subsequent analysis on the (sub)sample of employed individuals.

  <ul>

   <li>Discuss the estimation of the causal effect of schooling on earningsby OLS. In particular, address whether or not it is plausible that regularity conditions for applying OLS are satisfied.</li>

   <li>The researcher has collected data on two potential instrumental variables <em>subsidy </em>and <em>distance </em>for years of schooling.

    <ul>

     <li><em>distance </em>measures the distance between the school location and the residence of the individual while at school-going age.</li>

     <li><em>subsidy </em>is an indicator depending on regional subsidies of families for covering school expenses.</li>

    </ul></li>

  </ul></li>

</ol>

The researcher has the option to use only <em>distance </em>as an instrumental variable, or to use only the instrumental variable <em>subsidy</em>, or to use both <em>distance </em>and <em>subsidy </em>as instrumental variables. Perform instrumental variables estimation for these three options. Which option do you prefer? Include in your answer the necessary analyses and numbers on which you base your choice.

<ul>

 <li>Compare the IV estimates with the OLS outcomes. Under which conditions would you prefer OLS over IV? Perform a test and use the outcome of the test to support your choice between OLS and IV. Motivate your choice.</li>

</ul>