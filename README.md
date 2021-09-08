# assignment2-Pinninti
# Harshika Pinninti
######  Switzerland
It is one of my favourite place since childhood . **Switzerland** is known for being one of the most beautiful and serene place on earth. The Swiss seem to understand the __true meaning of serenity__ when it comes to world peace as well. The country is famous for being one of the most neutral countries in the world. I would like to explore many places in the switzerland

***
# Directions to Travel 
1. Travel from Missouri to kansas Airport by Car or cab
2. Take a flight from Kansas to the chicago
3. Take the connecting flight from chicago to Switzerland
   1. Take a Taxi
   2. Travel to the near by Hotel
   3. Travel to the clock tower
4. These are the steps to travel from Missouri to SwitzerLand


   Items to take For the Enjoyment
 - Sunglasses
 - Dresses
 - Board Games
 - Novels


[Aboutme](AboutMe.md)

***
# Table
Table describes the food items that are famous in india
|**Food**|__Location__|**Cost**|
| --- | --- | --- |
|Biryani|Hyderabad| $4 |
|Bongulo chicken |vizag| $3 |
| kulfi | warangal| $1|

***
# Pithy Quotes

>You know, Hobbes, some days even my lucky rocketship underpants don't help. *Bill Watterson*

> We can still choose where we go from there. *Stephen Chbosky*

***
# Code Fencing
>Orientation of an ordered triplet of points in the plane can be counterclockwise , clockwise , collinear . If orientation of (p1, p2, p3) is collinear, then orientation of (p3, p2, p1) is also collinear.  If orientation of (p1, p2, p3) is clockwise, then orientation of (p3, p2, p1) is counterclockwise and vice versa is also true.

Link to the Oriented area of a triangle :
<https://www.geeksforgeeks.org/orientation-3-ordered-points/>

```
 int signed_area_parallelogram(point2d p1, point2d p2, point2d p3) {
    return cross(p2 - p1, p3 - p2);
}

double triangle_area(point2d p1, point2d p2, point2d p3) {
    return abs(signed_area_parallelogram(p1, p2, p3)) / 2.0;
}

bool clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) < 0;
}

bool counter_clockwise(point2d p1, point2d p2, point2d p3) {
    return signed_area_parallelogram(p1, p2, p3) > 0;
}  
```

Link for the source code

<https://cp-algorithms.com/geometry/oriented-triangle-area.html>
    