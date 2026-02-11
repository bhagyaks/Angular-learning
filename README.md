# Angular-learning

A curated collection of Angular learning modules and example projects to explore key Angular concepts, patterns, and features.

This repository is organized into several submodules (each focusing on a specific Angular concept), making it easy to study, experiment, and reuse code for hands-on learning.

## Submodules

Each folder in this repository is a separate Angular project (or example) focused on one aspect of Angular:

angular-data-binding – Examples and exercises to understand Angular’s data binding system (interpolation, property binding, event binding, two-way binding).

angular-materials – Angular Material UI components and usage examples.

angular-signals – Examples demonstrating Angular Signals and reactivity (built-in reactive primitives).

reactive-form – Hands-on examples of reactive forms, form controls, form groups, validation, and custom validators.

These are included as Git submodules, so each can be developed independently and pulled separately from its own Git repository.

## Getting Started
Clone the repository (with submodules)

When cloning this repository, include submodules so you get all example projects:

git clone --recurse-submodules https://github.com/bhagyaks/Angular-learning.git


If you’ve already cloned without submodules:

git submodule update --init --recursive

## Running a Module

Each submodule is a standalone Angular project. To run it:

Navigate to the submodule directory:

cd angular-data-binding


Install dependencies:

npm install


Start the development server:

ng serve


Open your browser at:

http://localhost:4200


Repeat these steps for any of the other modules (angular-materials, angular-signals, reactive-form).
