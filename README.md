# Seasons of Code : Computational Geometry

**Amisha**

**19b090003**

Compuatational Geomtery was initially used for pattern recognintion. It has also been used often to describe algorithms for manipulating curves and surfaces in solid modeling. Though it is widely being used in design and analysis of algorithms, in this project, I will try to mainly focus on Applications of Computational Geometry in Geographic Information System(GIS). Because of its history, the field of computational geometry has focused mostly on problems in 2-dimensional space and to a lesser extent in 3-dimensional space. When problems are considered in multi-dimensional spaces, it is usually assumed that the dimension of the space is a small constant (say, 10 or lower). However, it is a limitation of Computational Geometry that it mostly deals with flat and straight surfaces, but it is possible to approximate curved objects with piecewise planar polygons or polyhedra. This assumption has freed computational geometry to deal with the combinatorial elements of most of the problems, as opposed to dealing with numerical issues. This is one of the things that makes computational geometry fun to study, you do not have to learn a lot of analytic or differential geometry to do it.  The key resources, which I have been using so far for pre-requisites, include [these notes](https://www.cs.umd.edu/~mount/754/Lects/754lects.pdf)(geometrical), and [this paper](https://drive.google.com/file/d/1nq6BZpW2AxExW-1O0gUp1v6kQoQvxl29/view?usp=sharing) (algorithms). 

Some topics, that I have studied so far (mostly graph theory), include :
- Convex hulls : A geometric set is convex if for every two points in the set, the line segment joining them is also in the set. One of the first problems identified in the field of computational geometry is that of computing the smallest convex shape, called the convex hull, that encloses a set of points.

![image](https://user-images.githubusercontent.com/82266064/114300808-9732b780-9adf-11eb-9773-04459d920655.png)

- Intersections : Determining whether complex objects intersect often reduces to determining which individual pairs of primitive entities (e.g., line segments) intersect.

![image](https://user-images.githubusercontent.com/82266064/114301839-0dd1b400-9ae4-11eb-91b9-a33eac625663.png)

- Triangulation and Partitioning: Triangulation is a catchword for the more general problem of subdividing a complex domain into a disjoint collection of ???simple??? objects. The simplest region into which one can decompose a planar object is a triangle (a tetrahedron in 3-d and simplex in general).

![image](https://user-images.githubusercontent.com/82266064/114301782-d6fb9e00-9ae3-11eb-94ce-3424313193b0.png)
                                            ![image](https://user-images.githubusercontent.com/82266064/114301894-4c676e80-9ae4-11eb-896f-f8392012f76c.png)
                                            
 The input to a compuatational geometry problem usually includes a set of points, lines or both of them; and the output is usually a response to some query, say if there is a pair of lines, which intersect, or the convex hull for the given points. Now, we will see some general applications of Computational Gemoetry in GIS. Please refer to this link for [detailed report](https://drive.google.com/file/d/14Em5E6tpJbPT1OANqynj8NEKvKx0IEV9/view?usp=sharing)
 

