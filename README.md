# Loop-explanation-and-practice

# List of student names
students = ["Alice", "Bob", "Charlie", "Diana"]

# Loop through each student in the list
for student in students:
    # Print a greeting message
    print(f"Hello, {student}! Welcome to the Python course.")

# Initialize a variable to hold the sum
total_sum = 0

# Loop through numbers from 1 to 100 (inclusive)
for number in range(1, 101):
    total_sum += number  # Add the current number to total_sum

# Print the final sum
print(f"The sum of numbers from 1 to 100 is: {total_sum}")

# Explanation:
# total_sum = 0: We start by initializing a variable to store the sum of numbers.
# range(1, 101): This function generates a sequence of numbers from 1 to 100, which we can iterate over with our loop.
# total_sum += number: Within the loop, we add the current number to total_sum. The += operator is a shorthand for total_sum = total_sum + number.
# After the loop completes, we print the final sum.
