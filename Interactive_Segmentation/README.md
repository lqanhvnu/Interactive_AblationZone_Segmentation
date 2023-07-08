# Interactive ablation zone segmentation
In this folder, we will provide instructions for interactive ablation zone segmentation using the combination of the nnUNet framework and RITM:
```.bash
# This command runs the demo of interacitve ablation zone segmentation
python demo.py
# You can try the demo in CPU-only mode
python demo.py --cpu
```
**Controls**:

| Key                                                           | Description                        |
| ------------------------------------------------------------- | ---------------------------------- |
| <kbd>Left Mouse Button</kbd>                                  | Place a positive click             |
| <kbd>Right Mouse Button</kbd>                                 | Place a negative click             |
| <kbd>Ctrl</kbd> + <br> <kbd>Scroll Wheel</kbd>    | Load a new slide
| <kbd>Shift</kbd> + <br> <kbd>Scroll Wheel</kbd>    | Zoom in/out 