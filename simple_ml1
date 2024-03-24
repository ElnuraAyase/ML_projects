# Sample dataset: Fruit weight (in grams) and corresponding fruit type (0 for apple, 1 for orange)
X = [100, 150, 200, 250, 300]  # Fruit weights
y = [0, 0, 1, 1, 1]             # Fruit types (0: apple, 1: orange)

# Simple linear regression equation: y = mx + b
# For simplicity, we'll manually define slope (m) and intercept (b)
m = 0.01  # Slope
b = -1    # Intercept
# Function to predict fruit type based on weight
def predict(weight):
    if m * weight + b < 0.5:  # If predicted value is less than 0.5, classify as apple
        return "Apple"
    else:
        return "Orange"

# Making predictions for some weights
weights_to_predict = [175, 225, 275]
for weight in weights_to_predict:
    fruit_type = predict(weight)
    print(f"For a fruit weighing {weight} grams, predicted type is: {fruit_type}")


