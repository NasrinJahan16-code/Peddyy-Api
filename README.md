# Project name: Peddy - Pet Adoption Site
Welcome to Peddy, a pet adoption site where users can browse, like, and adopt pets. 

# Live Link:pet-website.surge.sh

# How to use:
#Navbar:  Navigate through the platform and access pet adoption categories.

#Adopt Your Best Friend Section:**
1. View pets in a grid layout by category.
2. Like pets to save them in a separate section.
3. View pet details via a modal window.
#Footer section

# APIs Used
1. Fetch All Pets: Retrieves a list of all pets available for adoption.
GET https://openapi.programming-hero.com/api/peddy/pets

2. Fetch Pet Details by ID: Fetches detailed information for a specific pet.
GET https://openapi.programming-hero.com/api/peddy/pet/:pet-id

3. Fetch All Pet Categories: Fetches a list of all pet categories available (e.g., dogs, cats, etc.).
GET https://openapi.programming-hero.com/api/peddy/categories

4. Fetch Pets by Category: Fetches pets from a specific category (e.g., dogs, cats).
GET https://openapi.programming-hero.com/api/peddy/category/:categoryName 
