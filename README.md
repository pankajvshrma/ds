#Problem - 1 

  Identify categories of products based on associated descriptions and categories of similar products. 

  => input , csv of products with description fields and  category column having uncategorized.
           e.g PID, category, name, description
            "Pid1" ,  ["shoes"],    Nike Emerge 3, Running shoes with Jogging experience with Round toes.
            "Pid2" ,  ["uncategorized"] ,  Puma Mens Axis, Fitness companion for Jogging with Leather sole and flat.

  => output , csv of products with category column filled.

Hint: Use token set similarity. Evaluation will be based on the % of match of categories we know in the original data set. Use Libraries rather coding basic algorithms.
  
#Problem - 2
  Filling missing purchase counts for the products. 

  => input , csv of product id with column of purchases by month from July till Nov. There will be missing columns for these purchase numbers. You Need to fill the missing values for purchases_Y15/M08 and purchases_Y15/M09
   e.g Product id, july, aug , sep
            "Pid1" , 25, 12, 13
            "Pid2" ,   , 23, 45
            "Pid3" ,  65 ,  , 99
  => output , csv of products with missing date values column filled.

Hint: Use Regression techniques. Evaluation will be based on the % of closest match in values in original data set. Use Libraries rather coding basic algorithms.

) 
