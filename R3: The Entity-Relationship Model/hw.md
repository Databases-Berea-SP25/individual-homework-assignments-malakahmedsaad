# Malak Mohamed  
**R3: The Entity-Relationship Model**

---

## 1. Concepts and Terms  
### Chapter Summary: pp 98, 99 (Terms)  
1. **ER Models**: Visual representations of logical structure, consist of entities representing people, places, etc.  
   - No repetitions allowed.  
   - Entities have independent identifiers if they are **strong entities** or partial identifiers if they are **weak entities**.  
2. **Attributes**: Characteristics of entities.  
   - Types: **Required**, **optional**, **simple**, **composite**, **multivalued**, **derived**.  
3. **Identifiers**: Unique entity instances.  
4. **Degrees**: Unary, binary, and ternary relationships.

### Part 1: pp 53–58 (The E-R Model)  
5. **E-R Models**: Stands for Entity-Relationship Models.  
#### Examples of Entities:
1. **CUSTOMER**: A person or organization that has ordered or might order products.  
2. **PRODUCT**: A type of furniture made by Pine Valley Furniture that may be ordered by customers.  
3. **ORDER**: The transaction associated with the sale of one or more products to a customer, identified by a transaction number.  
4. **ITEM**: A component used in making products, supplied by one or more suppliers.  
5. **SUPPLIER**: A company that provides items to another company.  
6. **SHIPMENT**: The transaction associated with items received in the same package.

### Part 2: pp 65–72 (Modeling Entities and Attributes)  
7. **Entity Type**:  
   - A collection of entities sharing common properties or characteristics.  

8. **Entity Type Definition Structure**:  
   1. Begin with "An X is..." to clearly state the entity type's meaning.  
   2. Include the unique identifier for each entity instance (e.g., "An expense is identified by a journal entry number").  
   3. Define inclusion and exclusion criteria.  
      - Example:  
        - "A customer is a person or organization placing an order or being contacted for promotions."  
        - "A customer does not include buyers through distributors or agents."  
   4. Clarify creation or deletion criteria for entity instances.  
   5. Specify when an entity transitions to another type (e.g., a bid becoming a contract).  
   6. Define whether historical data needs to be retained (e.g., ITEM characteristics over time).  
      - **Note**: Historical requirements can impact E-R diagrams and data storage methods.

---

## 2. Example: Lion in a Zoo  
### Entities and Attributes:  
1. **Weak Entities**:  
   - Food, cage.  
2. **Strong Entities**:  
   - ID, Origin, Birthdate.  
3. **Composite Attributes**:  
   - Zoo worker's name, Species name.  
4. **Derived Attributes**:  
   - Total amount of food per year, Animals from the same origin, Age.

---

## 3. Exercise 2-3  
### a. Stored Attribute vs. Derived Attribute  
1. **Stored Attribute**: Directly stored in the database.  
2. **Derived Attribute**: Calculated from other attributes.

### b. Simple Attribute vs. Composite Attribute  
1. **Simple Attribute**: Cannot be broken down further.  
2. **Composite Attribute**: Can be divided into smaller parts.

### d. Strong Entity Type vs. Weak Entity Type  
1. **Strong Entity Type**: Independent, with a unique identifier.  
2. **Weak Entity Type**: Dependent on a strong entity.

### g. Composite Attribute vs. Multivalued Attribute  
1. **Composite Attribute**: Can be broken into smaller parts.  
2. **Multivalued Attribute**: Can have multiple values.

---

## 4. Exercise 2-21  
1. **Entity Type**:  
   A general category or template for a group of similar objects.  
   - Example: The entity type "lion" represents all lions in the zoo.  

2. **Entity Instance**:  
   A specific occurrence of an entity.  
   - Example: A particular lion in the zoo with unique attributes.  

3. **Summary**: An entity type includes multiple entity instances.
