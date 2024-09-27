# Lecture 1: Relational Algebra

## Key Concepts:
- **Relational Algebra:** A procedural query language that works with relations (sets of tuples).
- **Basic Operations:** Selection (σ), Projection (π), Union (∪), Set Difference (-), Cartesian Product (×), and Rename (ρ).

## Operators:
1. **Selection (σ):** Filters rows based on a given predicate.
   - Example: σ_age > 25 (SELECT rows where age is greater than 25)
   
2. **Projection (π):** Selects specific columns from a table.
   - Example: π_name, age (SELECT only name and age columns)
   
3. **Union (∪):** Combines the results of two queries.
   - Example: `R ∪ S`
   
4. **Set Difference (-):** Returns tuples that are in one relation but not in the other.
   - Example: `R - S`
   
5. **Cartesian Product (×):** Combines each tuple from the first relation with every tuple in the second relation.
   - Example: `R × S`

