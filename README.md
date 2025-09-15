<!DOCTYPE html>
<html>
    <head>
        <script src="https://aframe.io/releases/1.0.0/aframe.min.js"></script>
    </head>
    <body>
        <a-scene>
        <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
        <a-camera>
    <a-cursor></a-cursor>
        </a-camera>
   <a-sphere
    position="0 1 -5"
    radius="0.5"
    color="#803d8c"
    animation__1="
        property: position;
        from: 0 0 0;
        to: 1 0 -7;
        dur:4500
        loop: true
    "
    animation__2="
    property: scale;
    from:1;
    to: 0;
    startEvents:click
    "
    ></a-sphere>
    <a-sphere
    position="0 1 -5"
    radius="0.5"
    color="#803d8c"
    
    animation="
        property: position;
        from: 0 1 -5;
        to: 1 1 -5;
        loop: true
    "
    animation__2="
    property: scale;
    from:1;
    to: 0;
    startEvents:click
    "
     ></a-sphere>
     <a-sphere
    position="0 1 -5"
    radius="0.5"
    color="#803d8c"
    
    animation="
        property: position;
        from: 8 1 -5;
        to: 1 1 -5;
        dur;200
        loop: true
    "
    animation__2="
    property: scale;
    from:1;
    to: 0;
    startEvents:click
    "
       <a-sphere  
    position="0 1 -5"
    radius="0.5"
    color="#803d8c"
     
     ></a-sphere>
     <a-sphere
    position="0 1 -5"
    radius="0.5"
    color="#803d8c"
    
    animation="
        property: position;
        from: 8 1 -5;
        to: -5 1 -5;
        dur:4500
        loop: true
    "
    animation__2="
    property: scale;
    from:1;
    to: 0;
    startEvents:click
    "
       <a-sphere  
    position="0 1 -5"
    radius="0.5"
    color="#803d8c"
    
    
></a-sphere>
        </a-scene>
    </body>
</html>
