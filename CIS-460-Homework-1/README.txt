(8 pts) In mat4.h, there are several declarations of the operator* function. One declaration is vec4 operator*(const vec4 &v) 
const (line 89), while another is vec4 operator*(const vec4 &v, const mat4 &m) (line 106). Explain the mathematical difference
 in the output of these functions. Additionally, explain how these functions differ in scope from a code standpoint.
    - the first implmentaion vec4 operator*(const vec4 &v) const
      * memeber function perform matrix(itself) with vector multiplication with constraint-modification to object data 
      * return results out without modify object data 

    - the second implmentaion  vec4 operator*(const vec4 &v, const mat4 &m) 
      * external public function perform matrix(any mat4) vector(any vec4) multiplication 
(7 pts) In vec4.h, there are two declarations of the operator[] function. Describe a situation in which only the first function (line 25) can be used, and describe a situation in which only the second function (line 28) can be used.
