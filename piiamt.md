Fizzbuzz by Piia:

----------------------------
Set initial "number" to 1
----------------------------
              |
+-------------+
|             |
|             V
|            / \
|           /   \
|   /if "number"       \
|   \is divisible by 2 /----No---+
|          \    /                |
|            \ /                 |
|             |                  |
|             Yes                |
|             |                  |
|             V                  |
|   ---------------------        |
|     Print "Fizz"               |
|   ---------------------        |
|             |                  |
|             |        /\        |
|             V       /  \       V
|          /   if "number" is       \
|          \   divisible by 3       /----------No-----+
|                    \   /                            | 
|                      \/                             |
|                       |                             |
|                       Yes                           |
|                       |                    --------------------------
|                       V                      print the "number"
|    ---------------------------             --------------------------
|      print "Buzz"                                   |
|    ---------------------------                      |
|                  |                                  |
|                  V                                  V
|               -----------------------------------------
|                    set number 
|                    to "number"+1
|               -----------------------------------------
|                                    |
+------------------------------------+