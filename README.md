#### Learning to use HTML Canvas drawing 

Following [this](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage) tutorial

**Notes**
- Canvas element creates fixed size drawing surface called contexts. 2D and 3D contexts are available. `canvas.getContext("2d")`
- Unlike SVG, canvas only supports two shapes; rectangles and paths
- For rectangle
    ```
    fillRect(x, y, width, height) -> Draw filled rectangle
    strokeRect(x, y, width, height) -> Draw stroked rectangle
    clearRect(x, y, width, height) -> Clear specefied rectangular area

    ```
    
- For Paths
    ``` 
    beginPath() -> create a new path 
    closePath() -> closes the path
    stroke() -> add stroke to path
    fill() -> add fill to path
    ```