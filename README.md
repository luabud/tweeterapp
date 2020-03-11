
## Create a virtual environment 

1. Get set up with Visual Studio Code and the Python extension: [instructions here](https://aka.ms/pythonvscode).

2. Open a new terminal (```Ctrl-Shift-` ```) in VS Code and create a virtual environment.
 
    On Windows:

        py -3 -m venv env


    On Linux/MacOS:

        python3 -m venv env


3. Create a new terminal  (```Ctrl-Shift-` ```) to get the virtual environment automatically activated, and install the application's dependencies.

    ```
    python -m pip install -r requirements.txt
    ```
4. Build the node front end by opening a new terminal with Ctrl-Shift-` , and running:

    ```
    npm install
    npm run dev
    ```
    
5. Open a new terminal and Start the Django server:

    ```
    python manage.py migrate
    python manage.py loaddata initial_data
    python manage.py runserver
    ```

<!-- 
# Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments. -->
