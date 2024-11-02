{
  "nbformat_minor" : 4,
  "nbformat" : 4,
  "cells" : [
    {
      "cell_type" : "markdown",
      "source" : "# Programming Languages in Data Science\n",
      "metadata" : {

      }
    },
    {
      "cell_type" : "markdown",
      "source" : "## Introduction\n\nPredictive data analysis utilizes Machine Learning and statistical techniques to forecast future trends and enhance decision-making. In Python, this is accomplished using libraries such as Pandas for data manipulation, Scikit-Learn for model development, and Matplotlib for visualization. This exercise explores the key steps involved in creating predictive models, enabling the transformation of raw data into actionable insights.\n",
      "metadata" : {

      }
    },
    {
      "cell_type" : "markdown",
      "source" : "##LIST DATA SCIENCE LANGUAGES\n-PYTHON\n-R\n-SQL\n-JULIA\n-SAS\n-JAVA\n-SCALA\n-MATLAB",
      "metadata" : {

      }
    },
    {
      "cell_type" : "markdown",
      "source" : "# Popular Data Science Libraries\n\n## Python Libraries\n- **NumPy**: Fundamental package for numerical computing.\n- **Pandas**: Data manipulation and analysis tool.\n- **Matplotlib**: Plotting library for creating static, animated, and interactive visualizations.\n- **Seaborn**: Statistical data visualization based on Matplotlib.\n- **SciPy**: Library for scientific and technical computing.\n- **Scikit-learn**: Machine learning library for classification, regression, clustering, and more.\n- **TensorFlow**: Open-source library for machine learning and deep learning.\n- **Keras**: High-level neural networks API, running on top of TensorFlow.\n- **PyTorch**: Open-source machine learning library based on the Torch library.\n\n## R Libraries\n- **dplyr**: Data manipulation package for R.\n- **ggplot2**: Data visualization package based on the Grammar of Graphics.\n- **caret**: Package for streamlining the process of creating predictive models.\n- **tidyverse**: A collection of R packages for data science.\n- **shiny**: Web application framework for R.\n\n## Julia Libraries\n- **DataFrames.jl**: Data manipulation and analysis library for Julia.\n- **Plots.jl**: Visualization library for Julia.\n- **Flux.jl**: Machine learning library for Julia.\n\n## Other Languages\n- **Apache Spark**: Unified analytics engine for big data processing (supports Java, Scala, R, Python).\n- **MATLAB**: High-level language and interactive environment for numerical computation and visualization.\n",
      "metadata" : {
        "jp-MarkdownHeadingCollapsed" : true
      }
    },
    {
      "cell_type" : "markdown",
      "source" : "# Introduction to Data Science Tools\n\nData science encompasses a wide range of tools that facilitate data manipulation, analysis, visualization, and machine learning. Below is a table summarizing some popular data science tools, their primary functions, and the languages they support.\n\n| Tool           | Description                                      | Primary Language(s) |\n|----------------|--------------------------------------------------|---------------------|\n| **NumPy**      | Fundamental package for numerical computing.     | Python              |\n| **Pandas**     | Data manipulation and analysis tool.             | Python              |\n| **Matplotlib** | Plotting library for static, animated, and interactive visualizations. | Python              |\n| **Seaborn**    | Statistical data visualization based on Matplotlib. | Python              |\n| **Scikit-learn** | Machine learning library for various tasks.   | Python              |\n| **TensorFlow** | Open-source library for machine learning and deep learning. | Python              |\n| **Keras**      | High-level neural networks API for easy model building. | Python              |\n| **PyTorch**    | Open-source machine learning library.            | Python              |\n| **R**          | Programming language for statistical computing and graphics. | R                   |\n| **Apache Spark** | Unified analytics engine for big data processing. | Java, Scala, Python, R |\n| **MATLAB**     | High-level language and interactive environment for numerical computation. | MATLAB              |\n\nThis table highlights some essential tools that data scientists use to process and analyze data effectively.\n",
      "metadata" : {

      }
    },
    {
      "metadata" : {
        "trusted" : true
      },
      "source" : "# Introduction to Arithmetic Expressions\n\nArithmetic expressions are fundamental components of mathematics and programming. They consist of numbers and operators that perform various mathematical operations. In this section, we will explore some basic arithmetic operations and their examples.\n\n## Basic Arithmetic Operations\n\n1. **Addition (+)**: Combines two numbers to produce their sum.\n   - Example: \\( 3 + 5 = 8 \\)\n\n2. **Subtraction (−)**: Finds the difference between two numbers.\n   - Example: \\( 10 - 4 = 6 \\)\n\n3. **Multiplication (×)**: Calculates the product of two numbers.\n   - Example: \\( 7 \\times 6 = 42 \\)\n\n4. **Division (÷)**: Divides one number by another.\n   - Example: \\( 20 \\div 4 = 5 \\)\n\n5. **Exponentiation**: Raises a number to the power of another.\n   - Example: \\( 2^3 = 8 \\)\n\n## Examples of Combined Expressions\n\nHere are some examples of combined arithmetic expressions:\n\n- \\( (2 + 3) \\times 4 = 20 \\)\n- \\( 15 - (3 \\times 2) = 9 \\)\n- \\( 8 \\div 2 + 3 = 7 \\)\n- \\( 5^2 - 9 = 16 \\)\n\nThese expressions can be evaluated step by step following the order of operations (PEMDAS\/BODMAS).\n",
      "cell_type" : "code",
      "execution_count" : null,
      "outputs" : [

      ]
    },
    {
      "metadata" : {
        "trusted" : true
      },
      "source" : "def multiply_and_add(a, b, c):\n    \"\"\"\n    Multiply a and b, then add c to the result.\n    \n    Parameters:\n    a (int or float): First number\n    b (int or float): Second number\n    c (int or float): Number to add\n\n    Returns:\n    float: The result of (a * b) + c\n    \"\"\"\n    result = (a * b) + c\n    return result\n\n# Example usage\nnum1 = 5\nnum2 = 3\nnum3 = 2\nresult = multiply_and_add(num1, num2, num3)\nprint(f\"The result of multiplying {num1} and {num2}, then adding {num3} is: {result}\")\n",
      "cell_type" : "code",
      "execution_count" : null,
      "outputs" : [

      ]
    },
    {
      "metadata" : {
        "trusted" : true
      },
      "source" : "def convert_minutes_to_hours(minutes):\n    hours = minutes \/\/ 60\n    remaining_minutes = minutes % 60\n    return hours, remaining_minutes\n\n# Example usage:\nminutes_input = 130  # You can change this value to test with different inputs\nhours, remaining_minutes = convert_minutes_to_hours(minutes_input)\nprint(f\"{minutes_input} minutes is equal to {hours} hours and {remaining_minutes} minutes.\")\n",
      "cell_type" : "code",
      "execution_count" : null,
      "outputs" : [

      ]
    },
    {
      "cell_type" : "markdown",
      "source" : "## Objectives\n\n1. Understand the concept of time conversion between minutes and hours.\n2. Implement a Python function to perform the conversion.\n3. Test the function with various input values.\n4. Display the results in a clear and informative format.\n",
      "metadata" : {

      }
    },
    {
      "metadata" : {
        "trusted" : true
      },
      "source" : "",
      "cell_type" : "code",
      "execution_count" : null,
      "outputs" : [

      ]
    },
    {
      "cell_type" : "markdown",
      "source" : "# Author: DEGNAN CARINE BLIA\n",
      "metadata" : {

      }
    }
  ],
  "metadata" : {
    "language_info" : {
      "name" : ""
    },
    "kernelspec" : {
      "name" : "",
      "display_name" : ""
    }
  }
}
