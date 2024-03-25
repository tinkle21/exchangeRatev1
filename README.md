# Exchange Rate Analysis (Coding Challange)

This simple jupyter notebook using github codespaces to write and execute code interactively without hassale of downloading any package in local.(Everyone doesnot have own laptop always and required packages and editor installed and have permission to get it installed)

Fork this Repo in your GitHUB Account(Free)
Open code using Either GitHUB Codespaces or Google Colab(https://colab.google/) . It wont ask to create a account.
![image](https://github.com/tinkle21/exchangeRatev1/assets/42574217/3afd9938-fdf4-4ade-baa1-a1258d5494e5)

![image](https://github.com/tinkle21/exchangeRatev1/assets/42574217/8d422789-456b-4ac4-99ab-a30b8e61d6c1)

Create a API key from https://exchangeratesapi.io/ . This code is using free API key version which allow 250 API request per month. With limited functionality target can be still achievable.
![image](https://github.com/tinkle21/exchangeRatev1/assets/42574217/b88e2003-aa56-4bd4-bf50-81ce366d0e12)


Open Notebook in below sequence:
1) exchangeRate_api.ipynb
2) exchangeRate_data_anlysis.ipynb
   
Script Over View:
1)exchangeRate_api.ipynb 
Pass API key using terminal
Run API call 30 times one by one(using loop obviously). Free API restriction alow history of only one date it wont allow date interval else pay 40 dollar and just run once to achive target.
Save each response json in a list and save list as JSON in file.

2)exchangeRate_data_anlysis.ipynb
Check for data. All looks good. No need of cleansing .
Create pandas Dataframe from exchange date.
Add aditional column Aud_to_nzd
Perform Data Analsysis( max,min,average)
