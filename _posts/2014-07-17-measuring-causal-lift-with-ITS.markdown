---
layout: default
modal-id: 2
date: 2023-12-30
img: keywords.png
alt: image-alt
project-date: Dec 2023
client: Unnamed Social Media Giant
category: Incrementality/ Causal Impact
description: An Interrupted Time Series Data Science project to measure the Causal Lift from implementing localized keywords. <br></br><h1><b>Overview</b><br></br></h1><p>This project used the Interrupted Time Series (ITS) model to analyze the causal lift from implementing localized keywords for a social media giant’s online campaign in Spain. The social media company wanted to test if localized keywords would increase new users to sign up for their app in Spain. Due to various circumstances, a traditional A/B test could not be used for this test. The Interrupted Time Series model was chosen to analyze the causal lift as the model could show how and if the outcome has changed after an intervention without a control.</p><p>The tools used include <b>OLS</b> (for the regression model) , <b>Pandas</b> (for data cleaning/wrangling), <b>Datetime</b> (for processing time data)and <b>Plotly/Matplotlib</b> (for visualization).</p><br></br><h1>Interrupted Time Series - General summary</h1><br></br><p>The ITS model is used to understand how and if the outcome of a series of data has changed due to an intervention implemented for the full population at one specific point in time. Using data from both before and after the intervention occurred, we are able to construct a robust model giving us an actionable idea of how effective the intervention was in influencing conversions.</p><p>In mathematical terms, it means that the equation includes four key coefficients:</p><img class="img-responsive img-centered" src="https://raw.githubusercontent.com/chiyounglee01/images/main/its_equation.png" alt="graph"><p><b>Y</b> is the outcome variable</p><p><b>T</b> is a continuous variable which indicates the time (e.g., days, months, years…) passed from the start of the observational period</p><p><b>D</b> is a dummy variable indicating observation collected before (=0) or after (=1) the policy intervention</p><p><b>P</b>  is a continuous variable indicating time passed since the intervention has occured (before intervention has occurred P is equal to 0)</p>






---
