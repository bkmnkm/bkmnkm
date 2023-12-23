from prettytable import PrettyTable

# Create a PrettyTable instance
table = PrettyTable()

# Define the columns
table.field_names = ["Topic", "Notation/Terminology"]

# Add data to the table
data = [
    ("Function Notation", "f(x)"),
    ("Domain", "D(f) - set of all possible input values"),
    ("Range", "R(f) - set of all possible output values"),
    ("Independent Variable", "x"),
    ("Dependent Variable", "f(x)"),
    ("Function Evaluation", "f(a) - value of f at x=a"),
    ("Function Composition", "(f \circ g)(x) or f(g(x))"),
    ("Inverse Function", "f^{-1}(x)"),
    ("Piecewise Functions", "e.g., f(x) = {x^2 if x >= 0; -x^2 if x < 0}"),
    ("Sum of Functions", "(f + g)(x) or f(x) + g(x)"),
    ("Product of Functions", "(f \cdot g)(x) or f(x) \cdot g(x)"),
    ("Quotient of Functions", "(\frac{f}{g})(x) or \frac{f(x)}{g(x)}"),
    ("Trigonometric Functions", "\sin(x), \cos(x), \tan(x)"),
    ("Logarithmic Function", "\log(x)"),
    ("Exponential Function", "e^x"),
    ("Limits", "\lim_{{x \to a}} f(x)"),
    ("Derivatives", "f'(x) or \frac{df}{dx}"),
    ("Integrals", "\int f(x) \,dx"),
]

# Add rows to the table
for row in data:
    table.add_row(row)

# Print the table
print(table)

