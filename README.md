# Donut Collision Polygon 2D for Godot
_by @angrykoala_    
A donut-shaped collision shape for Godot.

This plugin creates new Node types for donut collision shapes for 2D collisions.

_Donut_    
![Donut Example](screenshots/donut_example.png)

_Donut Rectangle_    
![Donut Rectangle](screenshots/donut_rectangle.png)

## Instructions
The asset can be downloaded from [Godot Asset Library](https://godotengine.org/asset-library/asset/1087) or [GitHub](https://github.com/angrykoala/godot-donut-collision-polygon-2d)

1. Add the folder `donut_collision_polygon2D` to `addons/`.
2. Activate the plugin in [Godot](https://docs.godotengine.org/en/stable/tutorials/plugins/editor/installing_plugins.html).
3. Create any collision or physics 2D node (e.g. `Area2D` or `RigidBody2D`).
4. Add a `DonutCollisionPolygon2D` or `DonutCollisionRectangle2D` as child. 
![Tree Example](screenshots/tree_example.png)

## Properties

* **Donut**
  * **radius**: Defines the radius of the donut. This will be the circumference at the **center** of the donut.
  * **width**: The width of the donut.
  * **quality**: The number of points to use **per circumference**. The total points count will be `quality*2+1`. 
* **Donut Rectangle**
  * **size**
  * **width**

## License
Made by [@angrykoala](https://github.com/angrykoala). [MIT License](LICENSE)
