# To Create a list of fruits
fruits = ["apple", "banana", "cherry"]

#To Print the list
print("Fruits:", fruits)  # Output: Fruits: ['apple', 'banana', 'cherry']

#To Add an element to the list
fruits.append("orange")
print("Fruits after adding:", fruits)  # Output: Fruits after adding: ['apple', 'banana', 'cherry', 'orange']

# To Remove an element by value
fruits.remove("banana")
print("Fruits after removing banana:", fruits)  # Output: Fruits after removing banana: ['apple', 'cherry', 'orange']

# To Modify an element by index
fruits[0] = "mango"
print("Fruits after modifying:", fruits)  # Output: Fruits after modifying: ['mango', 'cherry', 'orange']

# To Create a dictionary of countries and their capitals
countries = {
    "France": "Paris",
    "Germany": "Berlin",
    "Italy": "Rome"
}

# To Print the dictionary
print("\nCountries and Capitals:", countries)  # Output: Countries and Capitals: {'France': 'Paris', 'Germany': 'Berlin', 'Italy': 'Rome'}

# To Add a new key-value pair
countries["Spain"] = "Madrid"
print("Countries and Capitals after adding Spain:", countries)  # Output: Countries and Capitals after adding Spain: {'France': 'Paris', 'Italy': 'Rome', 'Spain': 'Madrid'}

