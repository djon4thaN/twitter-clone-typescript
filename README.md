# Social Media Interface Modeling (TypeScript)

## Description

This project consists of a front-end structure inspired by a social media platform, developed using TypeScript with a focus on component-based architecture, code organization, and separation of responsibilities.

It simulates core features of a social platform, such as user interactions, posts, and reactions, emphasizing reusable components and maintainable code structure.

---

## Objective

The main objective of this project is to strengthen skills in:

- TypeScript and static typing  
- Component-based architecture  
- Code organization and scalability  
- Separation of concerns  
- Front-end structure aligned with real-world applications  

---

## Project Structure

```
src/
 ├── databases/
 │   ├── like.ts
 │   ├── tweets.ts
 │   └── user.ts
 ├── models/
 │   ├── base.ts
 │   ├── dislike.ts
 │   ├── like.ts
 │   ├── reaction.ts
 │   ├── tweet.ts
 │   └── user.ts
 └── index.ts
```

### Core Modules

- **Models**: Define the main entities and business logic (users, tweets, reactions)  
- **Databases**: Simulate data persistence for application behavior testing  
- **Index**: Entry point coordinating application flow  

---

## Features

- Post feed structure simulation  
- User interaction modeling (likes, dislikes, reactions)  
- Reusable and modular components  
- Clear separation between data and logic layers  

---

## Technologies

- TypeScript  
- Node.js  

---

## Architectural Notes

This project follows a modular and component-oriented structure, focusing on:

- Separation between data and domain logic  
- Reusability of components  
- Maintainable and readable code  
- Foundation for scalable front-end applications  

Although simplified, the structure reflects concepts used in real-world and enterprise-level systems.

---

## Relevance for Enterprise Systems

This project demonstrates important concepts applicable to enterprise environments:

- Structured and modular application design  
- Clear separation of responsibilities  
- Readability and maintainability  
- Front-end architecture aligned with scalable systems  

---

## Notes

This is an academic project focused on practicing front-end architecture and code organization. It does not represent a complete production-ready application.

---

## How to Run

1. Install dependencies:

```
npm install
```

2. Compile the project:

```
npx tsc
```

3. Run the project:

```
node dist/index.js
```
