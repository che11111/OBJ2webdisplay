# OBJ2webdisplay

A simple OBJ model display webpage

### Configuration Example:
```html
<script>
    // Basic configuration
    const modelConfig = {
        models: {
            'example': 'Example Model',
            //'model-1 (folder name)':'model-1 (display name)',
            //'model-2 (folder name)':'model-2 (display name)'
        },
        currentModel: null
    };
</script>
```
### Example: 
Create a `model - 1` folder in the `obj` directory at the same level as `index.html`

place the `textured_output.obj` file, `textured_output.mtl` file, and corresponding texture files in this folder

You need to name both the obj file and the mtl file of the model as `textured_output`

Otherwise, you need to change the code in the Html. 
