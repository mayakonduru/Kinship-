# Family Relationship Finder

This python program determines the familial relationship between two people in a family tree. It reads a JSON file that contaisn information like their genders, parents, and if they are married. 
Based on this a relationship is output between two people. 

# Features

- Uses a person class to model the relationships they have
- Supports parent-child relationships as well as spouse relationships.
- Handles distant relatives
- Uses a command line interface

  # Installation
  - Clone this repository or download the kinship.py script
  - The JSON file and relationship definitions also need to be downloaded.
 
  # Class and Methods
  - Person: Represents an individual in the family tree
  - Atrributes: name, gender, parents, spouse
  - Methods:
    - add_parent(parent): Adds a parent
    - set_spouse(spouse):Sets the spouse
    - connections(): Returms all possible connections of an individual in the family tree
    - relation_to(other): Determines the relationship to another person
   
  - Family: Represents the family and relationships:
    - Attributes: people(maps names to the person object)
    - Methods: relation(name1, name2): Returns the relationship between two people
