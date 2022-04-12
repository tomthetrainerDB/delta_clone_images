# delta_clone_images
Place for dot files of delta clone images
These images are useful for demonstrating delta clone operations
They are generated using graphviz, the dotfiles are included
Output as svg is useful for putting into notebooks
Basic image generation commands are
```dot -Tpng shallow_clone.dot > shallow_clone.png```
Will generate a png, you can add height and width and the like
```dot -Tsvg shallow_clone.dot > shallow_clone.svg``` will generate an svg
You could modify the dot files to add content to the graphs
