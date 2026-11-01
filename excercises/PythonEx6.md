# Python Exercise 6

Open your Python coding editor

## Part 1 - File Handling

1.  Create a text file called `fruit.txt` with the content shown here:

    `- fruit.txt -`
    ```
    Apples
    Pears
    Oranges
    ```

2.  Create a Python program called `file1.py` to print the contents of `fruit.txt` below:
    
    Expected output:
    ```
    Apples
    Pears
    Oranges
    ```

    Get into the habit of always closing your data files with `close()` function.

3.  Create a Python program called `file2.py` to print the contents of `fruit.txt` below:

    Expected output:
    ```
    1. Apples

    2. Pears

    3. Oranges    
    ```

4.  Modify `file2.py` to print the contents of `fruit.txt` like below:

    Expected output:
    ```
    1. Apples
    2. Pears
    3. Oranges    
    ```

    > The `print()` function has a `end` argument that will help :wink: 

1.  Create a text file called `numbers.txt` with the content shown here:

    `- numbers.txt -`
    ```
    1
    2
    3
    4
    5
    ```

1.  Write a Python program called `file3.py` to read the numbers from `numbers.txt` and print:

    Expected output:
    ```
    1
    2
    3
    4
    5
    ```

6.  Write a Python program `file4.py` to read the numbers from `numbers.txt` and print the total and average values:

    Expected output:
    ```
    There are 5 numbers in numbers.txt
    Total = 15
    Average = 3.0
    ```

6.  Write a Python program `file5.py` to read the numbers from `numbers.txt`, add them to a Python *list* and print the list:

    Expected output:
    ```
    [1, 2, 3, 4, 5]
    ```

1.  Write a Python program `file6.py` ask the user to input a new fruit and write it to the `fruit.txt` file:

    Expected Output:
    ```
    Input a new fruit: Bananas
    ```

    `fruits.txt` has Bananas added:
    ```
    Apples
    Pears
    Oranges
    Bananas
    ```


    ```
    Input a new fruit: Grapes
    ```

    `fruits.txt` has Grapes added:
    ```
    Apples
    Pears
    Oranges
    Bananas
    Grapes
    ```

    > Run the program at least twice to add a new fruit.

1.  Write a Python program `file7.py` that writes names from a Python list to a new file called `names.txt`:

    ```python
    names = ["Alice", "Bob", "Charlie"]
    ```

    Expected `names.txt` file:
    ```
    Alice
    Bob
    Charlie
    ```


## Part 2 - Basic JSON

1.  Create a Python program called `player1.py` to convert the Python dictionary below to a JSON string and print it:

    ```
    player = {
        "name": "Lionel Messi",
        "club": "Paris Saint-Germain",
        "country": "Argentina",
        "caps": 164,
        "goals": 90
    }    
    ```  
    Expected output:
    ```
    {"name": "Lionel Messi", "club": "Paris Saint-Germain", "country": "Argentina", "caps": 164, "goals": 90}
    ```

    You must use the `json.dump()` function    

1.  Create a Python program called `player2.py` to convert the Python JSON string below to a dictionary and print details from it:

    ```
    player = '{"name": "Pedri", "club": "FC Barcelona", "country": "Spain", "caps": 14, "goals": 0}'
    ```  
    Expected output:
    ```
    - Player dictionary - 
    {'name': 'Pedri', 'club': 'FC Barcelona', 'country': 'Spain', 'caps': 14, 'goals': 0}

    Pedri plays for FC Barcelona and Spain

    ```

    You must use the `json.load()` function    

3.  Create a Python program called `writePlayer.py` to write the player dictionary for Pedri to a JSON file called `player.json`

    Expected contents in `player.json`:
    ```
    {"name": "Pedri", "club": "FC Barcelona", "country": "Spain", "caps": 14, "goals": 0}
    ```

4.  Create a Python program called `updateGoals.py` to allow you to update the goals value in the `player.json` file.

    Expected Output:
    ```
    Input a new value for goals:1

    ```

    Expected contents in `player.json`:
    ```
    {"name": "Pedri", "club": "FC Barcelona", "country": "Spain", "caps": 14, "goals": 1}
    ```

5.  Create a Python program called `updatePlayer.py` to allow you to update the both caps and goals values in the `player.json` file.

    Expected Output:
    ```
    Input a new value for caps (14):15
    Input a new value for goals (1):2

    ```

    > Notice how the current values are shown inside brackets.

    Expected contents in `player.json`:
    ```
    {"name": "Pedri", "club": "FC Barcelona", "country": "Spain", "caps": 15, "goals": 2}
    ```
