# Airtel-Pass-By-Default-
This repo contains all the by default password combinations of airtel router to perform wifi attacks [EX; airXXXXX]



# IF YOU WANNA GENERATE YOUR OWN WITH ANY CONFIGURATIONS USE BELOW CODE

```

# Generate all combinations of the format "airXXXXX"
def generate_all_combinations(prefix, filepath):
    try:
        with open(filepath, "w") as f:
            for number in range(100000):  # Loop from 0 to 99999
                word = prefix + str(number).zfill(5)  # Create the word "airXXXXX"
                f.write(word + "\n")  # Write the word to the file with a newline

        print(f"All possible combinations have been generated and saved to {filepath}")
    
    except Exception as e:
        print(f"An error occurred: {e}")

# Usage
prefix = "air"  # The prefix before the number
filepath = r"C:\Code files\pass.txt"
generate_all_combinations(prefix, filepath)

```
