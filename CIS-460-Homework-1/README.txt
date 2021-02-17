(8 pts) In mat4.h, there are several declarations of the operator* function. One declaration is vec4 operator*(const vec4 &v) 
const (line 89), while another is vec4 operator*(const vec4 &v, const mat4 &m) (line 106). Explain the mathematical difference
 in the output of these functions. Additionally, explain how these functions differ in scope from a code standpoint.
    - the first implmentaion vec4 operator*(const vec4 &v) 
        