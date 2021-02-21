# Handpalm_Detect
EqualizeHist, GaussianBlur, Canny algorithm which is we used in that project


In another side, we used machine learning algorithm from line length algoithm and we assign our datas to excel tables which name is palm_info.xlsx.
We had 4 line lengths in palm_info tables (life_line, head_line,heart_line,fate_line) also we had gender information in there.
We convert our gender datas m(male) and f(female) to 0 and 1.
Then we split our dataset with 0.33 test_size and we try to learn our gender information from line lengths.
We used scaling method and linear regression method for better result accuracy.
Then we try to learn fate_line from life_line, head_line, heart_line and gender.
I wanted to use backward elimination so before of that features, I built model and print OLS Regression result.
I saw in my datas x1's P value is 0.911 and in regression, P value must be lower than 0.05 so I drop x1 value and try to built again to my model
Now on, model is looking better and my R-squared is 0.955 in social science, the acceptance value is at least 0.700 and nature science is approximately 0.600
So our model is looking consistent.
After that I wanted to show my result in linear regression and polynomial regression.
