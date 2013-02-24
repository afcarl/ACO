#Ant Colony Optimization

There is a ACO-algorithm realisation on C++.
http://en.wikipedia.org/wiki/Ant_colony_optimization_algorithms

For usage you should define fitness-function, link this:
```c++
double fitness(vector <double> cords)
{
    double x = cords[0];
    double y = cords[1];
    
    return (x - 5) * (x - 5) + y * x + y * y;
}
```

For more see examples dir.