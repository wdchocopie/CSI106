# Data Storage
----
# Logic Operation
* Refer to basic operation on individual bits / 2 corresponding bits in patterns \(bitwise operation\)
* 1 = true, 0 = false
* 4 basic operation: And, Or, Xor, Not
   * And: &&
   * Or: ||
   * Not: !
   * Xor: ^
**Image**

----
# Shift operation
* Move bits in patterns
* 2 categories:
   * Logical shift operations - does not represent sign number
      * Logical shift
      * logical circular shift
   * Arithmetic shift operations

----
# Logical shift
* >>: move to right 
* <<: move to left 
* Lost data from the end, append 0 at the start

----
# Logical Circular Shift
* >>: reuse srart bit
* <<: append 0 at the start
* The rest are the same with normal logical shift

----
# Arithmetic shift operation
* Same with circular shift
* <<: multiply an interger by 2
* >>: divide an interger by 2

----
# Arithmetic operation
* A - B = A + (2 Complement of B)

