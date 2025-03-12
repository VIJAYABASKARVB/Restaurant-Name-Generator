# Restaurant Name & Menu Generator

This project uses **LangChain** and **Groq's LLM** to generate a unique restaurant name and an authentic menu based on a specified cuisine.

## Features
- Generates a creative and memorable restaurant name.
- Provides a list of five authentic dishes tailored to the specified cuisine.
- Utilizes **LangChain** for sequential processing of name and menu generation.

## Technologies Used
- **Python**: Main programming language.
- **LangChain**: For building language model chains.
- **Groq**: To access and interact with the LLM model.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/VIJAYABASKARVB/restaurant-name-menu-generator.git
   cd restaurant-name-menu-generator

2. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. Install required packages:
   ```bash
   pip install -r requirements.txt

4. Set your Groq API Key:Ensure you have a my_key.py file with the following content:
   ```bash
   api_key = "your_groq_api_key_here"

## Usage

Run the script to generate a restaurant name and menu:
```bash
python main.py
```
## Example Output

```bash
Restaurant Name: Spice Symphony

Menu:
1. Butter Chicken
2. Paneer Tikka
3. Biryani
4. Masala Dosa
5. Chole Bhature
```
## Customization

1.Cuisine: Modify the generate_restaurant_name_and_items() function call to change the cuisine.

2.Model Settings: Adjust the temperature parameter of the ChatGroq instance to control the creativity of responses.

## Requirements

Ensure you have the following Python packages installed:

1.langchain

2.langchain-groq

## You can install these via:
```
pip install langchain langchain-groq
```

## Contributions

Feel free to open a pull request or submit issues if you'd like to contribute!

