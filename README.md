import random

def roulette_selection():
    """
    This function selects 11 unique random numbers from the range 0 to 36,
    simulating a roulette number selection.
    """
    # Define the range of roulette numbers (0 to 36)
    roulette_numbers = list(range(37))
    # Randomly select 11 unique numbers
    selected_numbers = random.sample(roulette_numbers, 11)
    return selected_numbers

# Run the function and display the selected numbers
if __name__ == "__main__":
    selected = roulette_selection()
    print("Randomly selected roulette numbers:", selected)

