import random

def roulette_selection():
    # Define the range of roulette numbers
    roulette_numbers = list(range(37))  # 0 to 36
    # Randomly select 11 unique numbers
    selected_numbers = random.sample(roulette_numbers, 11)
    return selected_numbers

# Run the function and display the selected numbers
if __name__ == "__main__":
    selected = roulette_selection()
    print("Randomly selected roulette numbers:", selected)
