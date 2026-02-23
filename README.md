# datafun-06-eda 
    A comprehesive list of notes and actions taken for this project.
    Project is meant to be started from scratch to implement skills acquired throughout this class and used to better organize information and thought process.

# Datadescription
    Name: [Dowjones] https://fred.stlouisfed.org/series/M1109BUSM293NNBR

    Count of Record: There are 649 counts

    List or table of the columns and description of what each column holds

    RangeIndex: 649 entries, 0 to 648
    Data columns (total 2 columns):
    #   Column  Non-Null Count  Dtype         
    ---  ------  --------------  -----         
    0   Date    649 non-null    datetime64[us] "Date of the stock index"
    1   Price   649 non-null    float64        "Price of the stock index"
    dtypes: datetime64[us](1), float64(1)


# Notes and processes taken

1. Creating new github repository with default README
2. Cloned git into VS to start project.
3. Reviewing the project initialization process provided by Dr. Case.
4. Following the examples of PI, copied the requirements.txt as a base starting point for this project!
5. Wanting to start this more advanced also copied pyproject.toml from previous Notebook project. data-04-notebooks
6. ran uv venv to create a virtual environment
7. activating virtual environment with .venv\Scripts\activate
8. created src folder
9. added pyarrow dependency to pyproject.toml
10. Installed dependencies (project.toml) using 
    uv pip install --upgrade pip setuptools wheel
    uv pip install --upgrade -e .[dev]

11. Created Notebook folder and starting notebook file
12. Selected python environment Kernal for notebook file
13. Started notebook project, added beginning markdowns and code.
14. Imported Library
15. Loaded dataset
    

# Updates

1. initial git commit with notes 1-5
2. Notes 6-12
3. Renamed notebook
4. 