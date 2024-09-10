<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Voronoi Diagram of Cholera Deaths</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            color: #333;
        }
        .diagram {
            text-align: center;
            margin-top: 20px;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        .description {
            font-size: 16px;
            margin-top: 10px;
        }
    </style>
</head>
<body>

    <h1>Voronoi Diagram of Cholera Deaths and Pumps</h1>

    <p class="description">
        This plot displays a Voronoi diagram based on the locations of pumps in the 1854 cholera outbreak. 
        The black points represent deaths due to cholera, and the red points represent the pump locations. 
        The Voronoi cells show the area closest to each pump.
    </p>

    <div class="diagram">
        <img src="voronoi_diagram.png(1)" alt="Voronoi Diagram of Pumps and Deaths">
    </div>

</body>
</html>
