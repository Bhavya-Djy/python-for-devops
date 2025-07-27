COMMAND LINE ARGUMENTS:

import sys

# Print the number of arguments
print("Total arguments passed:", len(sys.argv))

# Print all arguments
print("Arguments List:", sys.argv)

# Access individual arguments
if len(sys.argv) >= 3:
    name = sys.argv[1]
    age = sys.argv[2]
    print(f"Hello, {name}! You are {age} years old.")
else:
    print("Usage: python cmd_args_example.py <name> <age>")

ENVIRONMENT VARIABLES:

import os

print (os.getenv("name"))
