# Pasto

# Proposed Design Pattern
    Microservice Architecture Design Pattern

# Proposed Technologies
    1. Backend: Django
    2. Database: PostgreSQL
    3. Web: Angular/ React
    4. Mobile: Flutter

# Main Modules
1. Auth Module

        This must allow users to register, login, reset password, and do social media login.
2. Blog Module

       Users can share their experiences, and comment to each others there. similliar to a one facebook group form
3. Shop Module

       The cheif users are able to send offers for the inquiries, and the users can request an order from the cheif.

       The orders system is operated offline, and it is just updated throught the system, this allows the users to rate the cheifs and the review dishes.
4. Ingredients Matching Module

        In this module, the user is able to select the categories that they want, and the ingredients that they have, in order to recommend dishes for them.


# Requirements Gathering Example for PASTO

Here's a comprehensive requirements gathering document for your PASTO (Platform for Advanced Sharing of Teaching and Online recipes) application:

# 1. Project Overview


Project Name: PASTO

Purpose: A platform connecting food enthusiasts with recipe creators and culinary instructors

Target Audience: Home cooks, professional chefs, culinary instructors, food bloggers

# 2. Stakeholders

End Users: People searching for recipes, learning cooking techniques

Vendors: For now, Chefs only

Administrators: Platform managers ensuring quality and compliance

# 3. User Roles and Permissions

## 3.1 Admin Role

        1. Full access to user management
        
        2. Content moderation capabilities
        
        3. System configuration access
        
        4. Analytics and reporting access
        
        5. Manage ingredients database

        6. Add/Edit/Delete ingredients and recipes

## 3.2 Vendor Role

        1. Select Available Recipes
        
        2. Manage personal shop items
        
        3. Access to customer reviews and engagement metrics
        
        4. Blog post creation and management

        5. Manage orders

        6. Rate buyers

        7. Buy Credit Balance

## 3.3 User Role

        1. Browse and search recipes
        
        2. Save favorites and create collections
        
        3. Post cooking request
        
        4. Purchase items from shops
        
        5. Rate and review content
        
        6. Comment on blog posts


# 4. Functional Requirements

## 4.1 User Authentication and Profiles

        1. Email and social media registration
        
        2. Role-based access control
        
        3. Profile customization
        
        4. Password reset functionality
        
        5. Activity history

## 4.2 Recipe Management

        1. Recipe creation with rich text editor
        
        2. Ingredient listing with quantities
        
        3. Step-by-step instructions with images
        
        4. Dietary tags and categories
        
        5. Cooking time and difficulty indicators
        
        6. Rating and review system

## 4.3 Ingredient-Based Recipe Search

        1. Search by available ingredients
        
        2. Filter by dietary restrictions
        
        3. Filter by preparation time
        
        4. Sort by rating/popularity
        
        5. Save search preferences

## 4.4 Blog System

        1. Rich text editor with image support
        
        2. Comment functionality
        
        3. Social sharing options
        
        4. Related recipes linking
        
        5.Content categorization

## 4.5 Shop Integration

        1. Shopping cart functionality
        
        2. Order tracking


# Non-Functional Requirements

## 5.1 Performance

        1. Page load time under 2 seconds
        
        2. Support for 1000+ concurrent users
        
        3. Search results returned in under 1 second
        
        4. Support mobile and desktop devices

## 5.2 Security

        1. HTTPS for all connections
        
        2. Secure password storage (hashing)
        
        3. Protection against SQL injection
        
        4. CSRF protection
        
        5. Regular security audits

## 5.3 Scalability

    1. Horizontal scaling capability
    
    2. Database optimization for large datasets
    
    3. Caching strategy for popular content
    
    4. CDN for media content

## 5.4 Usability

        1. Mobile-responsive design
        
        2. Intuitive navigation
        
        3. Accessible to users with disabilities (WCAG 2.1 AA)
        
        4. Multilingual support (English, Spanish initially)

# 6. Data Requirements

## 6.1 User Data

        1. Profile information
        
        2. Payment details (encrypted)
        
        3. Usage history
        
        4. Preferences and dietary restrictions

## 6.2 Recipe Data

        1. Title, description, images
        
        2. Ingredients with quantities
        
        3. Preparation steps
        
        4. Metadata (time, difficulty, servings)
        
        5. Categories and tags

## 6.3 Vendor Data

        1. Professional information
        
        2. Availability schedule
        
        3. Teaching history
        
        4. Rating and reviews














