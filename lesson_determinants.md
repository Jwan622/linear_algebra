### Quick lesson on determinants

Determinants are a useful mathematical form which allow us to work with vectors in three dimensions more easily.

A determinant is a two-dimensional array which calculates out to a single number. It looks like this: . To compute this determinant's value, we multiply a and d and then subtract bc. A 3x3 determinant's value is harder to compute.

![lesson_determinants_1](lesson_determinants_1)

To compute a 3x3 determinant, we take the upper-left member and multiply it by the determinant that remains if you cross out all the members in the same row or column as the upper-left member. In this case, we are left with the determinant |e f / h i|. The same is done with the negative of the upper-middle number, multiplying it by the determinant left after crossing out all members in a line with the upper-middle member. Finally, the upper-right member is also multiplied by the lower-left 2x2 determinant. These three products are added together to find the value of the entire 3x3 determinant.

### Vector Cross Products

A vector cross product is another way of "multiplying" three dimensional vectors. To take the cross product of u = (a,b,c) and v = (d,e,f) we use the determinant  where i = (1,0,0), j = (0,1,0) and k = (0,0,1). The resulting vector has some unique properties:

**Properties of Cross Products**:
1. u x v is perpendicular to both u and v	v x u = -(u x v)
2. |u x v| = |u||v| sin A, if A = the angle between u and v	|u x v| is the area of the parallelogram formed by u and v
