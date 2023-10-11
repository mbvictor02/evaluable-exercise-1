
# Monte Carlo Pi Estimation

Since ancient times, humans have attempted to calculate the value of π (pi), the mathematical constant representing the ratio of a circle's circumference to its diameter. Early civilizations, such as the Babylonians, approximated π by taking 3 times the square of a circle's radius, yielding a value of pi = 3. However, over the centuries, we have developed more sophisticated methods to calculate π with significantly greater precision.

One such approach involves Monte Carlo methods, also known as Monte Carlo experiments. These methods belong to a broad category of computational algorithms that heavily rely on repetitive random sampling to obtain numerical results. The fundamental idea behind Monte Carlo methods is to leverage randomness to tackle problems that may, in principle, be deterministic. These techniques find extensive applications in various fields, particularly in scenarios where other traditional approaches are impractical or unfeasible.

The code provided here implements a specific Monte Carlo algorithm within the mathematical framework of optimization. It involves the generation of random points on a surface to calculate different proportions of areas.

More precisely, this code calculates the proportion of the area enclosed by a square and the area of a circular section. The circle is centered at one of the square's corners, with a radius equivalent to the length of a side of the square. This technique, inspired by the Monte Carlo method, allows for an approximate estimation of π by assessing these area proportions.



Prerequisites
Python 3.x
Random library (built-in with Python)
How to Use
Run the script.
Enter the total number of random points to generate.
Enter the number of times you want to run the estimation method for more accurate results.
The script will then generate random points, calculate the estimated value of π, and provide you with the result and an estimate of the standard deviation.

Function Explanation
montecarlo(total_points)
This function estimates π by generating random points and calculating how many of them fall inside a unit circle.

total_points: The total number of random points to generate.
main
The main part of the script collects user input, runs the montecarlo function, and calculates the average estimated value of π along with the standard deviation.

Example
bash
Copy code
$ python monte_carlo_pi_estimation.py
Total number of points to generate: 10000
Number of times you want to run the method: 100
The estimated value of π is: 3.14232 +/- 0.042367
License
This code is available under the MIT License.

Feel free to use, modify, and share this code.

You may want to include the MIT License (or any other license you choose) in a separate LICENSE.md file or specify the licensing information as needed for your project.
## Prerequisites

Python 3.x
Random library (built-in with Python)

## How to use

Run the script.
In order to do this you must open a terminal and change directory 
via command cd "directory where this code is" and then run the code
by typing "name of the code".py . Name should be montecarlo-pi.py

Enter the total number of random points to generate.
Enter the number of times you want to run the estimation method for more accurate results.
The script will then generate random points, calculate the estimated value of π, and provide you with the result and an estimate of the standard deviation.
## Example run

$ python montecarlo-pi.py
Total number of points to generate: 10000
Number of times you want to run the method: 100
The estimated value of π is: 3.14232 +/- 0.042367
