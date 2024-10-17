# Code Example with pygments
Pigments are in :
```web
https://pygments.org/docs/lexers/
```

An example foa ccodeblock for Python

```py title="add_numbers.py" linenums="1"
# Function to add tow numbers
def add_two_numbers(num1, num2):
    return num1 + num2

# Example usage
result = add_two_numbers(5,3)
print('The sum is:', result)
```

SLURM Example:
```slurm title="mpi-example.sl"  hl_lines="2-3"
#SBATCH --node = 1
#SBATCH --ntasks = 10
#SBATCH --mem-per-cpu = 3G

srun mycode
```

BATCH example
```bash
ssh usernamet@agamede.lgp.ehu.es
```