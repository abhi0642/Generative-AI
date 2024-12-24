Steps to migrate the code to new imports

1. Install langchain-cli

   pip install langchain-cli

2. To check the changes updates, run the commands
   langchain-cli migrate --diff [path to code] #preview

3. langchain-cli migrate [path to code] # Apply

Remember to run these commands 2 times to get the most updated imports, it might change to the intermediate recent import, for the final updated keep in mind to run 2 times.
