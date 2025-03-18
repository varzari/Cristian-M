<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SVG - Pájaro</title>
</head>
<body>

    <h1>¡Un pájaro dibujado con SVG!</h1>
    
    <svg width="200" height="200" xmlns="http://www.w3.org/2000/svg">
        <!-- Cuerpo del pájaro -->
        <ellipse cx="100" cy="100" rx="60" ry="40" fill="yellow" />
        
        <!-- Ala -->
        <path d="M 40 100 Q 20 60, 80 80 Q 40 100, 60 120" fill="orange" />
        
        <!-- Cabeza -->
        <circle cx="100" cy="60" r="20" fill="yellow" />
        
        <!-- Ojo -->
        <circle cx="110" cy="55" r="4" fill="black" />
        
        <!-- Pico -->
        <polygon points="120,60 140,55 120,50" fill="orange" />
        
        <!-- Patas -->
        <line x1="80" y1="130" x2="80" y2="150" stroke="orange" stroke-width="2"/>
        <line x1="120" y1="130" x2="120" y2="150" stroke="orange" stroke-width="2"/>
        <line x1="80" y1="150" x2="70" y2="160" stroke="orange" stroke-width="2"/>
        <line x1="120" y1="150" x2="130" y2="160" stroke="orange" stroke-width="2"/>
    </svg>

</body>
</html>
