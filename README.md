# Numpy-packages
bmi calc.
height = [5.3, 5.62, 5.5, 6.1, 5.10]
weight = [55, 68, 67, 95, 85]
# Import numpy
import numpy as np
# Create array from height with correct units: np_height_m
np_height_m = np.array(height) * 0.0254
# Create array from weight with correct units: np_weight_kg
np_weight = np.array(weight)
np_weight_kg = np_weight * 0.453592 
 # Calculate the BMI: bmi
bmi = np_weight_kg / np_height_m ** 2
# Print out bmi
print(bmi)

# Create baseball, a list of lists
baseball = [[180, 78.4],
            [215, 102.7],
            [210, 98.5],
            [188, 75.2]]
# Import numpy
import numpy as np
# Create a 2D numpy array from baseball: np_baseball
np_baseball = np.array(baseball)
# Print out the type of np_baseball
print(type(np_baseball))
# Print out the shape of np_baseball
print(np.array(baseball).shape)

# Import numpy package
import numpy as np
# Create np_baseball (2 cols)
np_baseball = np.array(baseball)
# Print out the 50th row of np_baseball
print(np_baseball[49,:])
# Select the entire second column of np_baseball: np_weight
np_weight = np_baseball[:, 1]
# Print out height of 124th player
print(np_baseball[123,0])

