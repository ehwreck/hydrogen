# About Hydrogen
Hygrogen is a template for creating customizable react applications.
- All reusable components are located in `/src/components`
  - Each components has it's own directory with one of the following files:
    - *.component.jsx
    - *.styles.css
    - *.spec.jsx
- All redux slices are located in `/src/redux/slices`
- Redux is utilized to store state utilized in many of the reusable components. An example is the current path which is used in both the header navigation menu & footer navigation menu.
