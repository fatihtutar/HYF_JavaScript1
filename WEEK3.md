Functions

some exercises to help you understand functions:

    Defining vs. Calling functions
        Defining: when you write the funciton -> function name() {}. This creates the function in memory
        Calling: using the function to compute new values -> name(). This creates a new frame and returns a new value

    Arguments
    Lexical Scope
    Return Values

Index

    completed example
    exercises
        number 1
        number 2
        number 3
        number 4
        number 5
        number 6
        number 7
        number 8

Completed Example

on pytut
parsonized

{  // completed example
  function f(param_1, param_2, param_3) {
    var result = param_2 + param_3 + param_1;
    return result;
  };

  // set values in the args to pass the assert
  let arg_1 = "x", arg_2 = "z", arg_3 = "y";
  let return_val = f(arg_1, arg_2, arg_3);

  console.assert(return_val === "zyx", "example: return_val === " + return_val);
}

TOP
Exercises
1

on pytut
parsonized

{   // 1
  function f(param_1, param_2, param_3) {
    var result = param_3 + param_1 + param_2;
    return result;
  };

  // set values in the args to pass the assert
  let arg_1 = "", arg_2 = "", arg_3 = "";
  let return_val = f(arg_1, arg_2, arg_3);

  console.assert(return_val === "zyx", "1: return_val === " + return_val);
}

2

on pytut
parsonized

{  // 2
  function f(param_1, param_2, param_3) {
    var result = param_3 + param_1 + param_2;
    return result;
  };

  // set values in the args to pass the assert
  let arg_1 = "", arg_2 = "", arg_3 = "";
  let return_val = f(arg_1, arg_2, arg_3);

  console.assert(return_val === "yxz", "2: return_val === " + return_val);
}

3

on pytut
parsonized

{  // 3
  function f(param_1, param_2, param_3) {
    var _ = param_2;
    param_2 = param_1;
    param_1 = _;
    var result = param_3 + param_1 + param_2;
    return result;
  };

  // set values in the args to pass the assert
  let arg_1 = "", arg_2 = "", arg_3 = "";


  let return_val = f(arg_1, arg_2, arg_3);

  console.assert(return_val === "yxz", "3: return_val === " + return_val);
}

4

on pytut
parsonized

{  // 4
  function f(param_1, param_2, param_3) {
    var _ = param_2;
    param_2 = param_3;
    param_3 = _;
    var result = param_3 + param_1 + param_2;
    return result;
  };

  // set values in the args to pass the assert
  let arg_1 = "", arg_2 = "", arg_3 = "";
  let return_val = f(arg_1, arg_2, arg_3);

  console.assert(return_val === "xyz", "4: return_val === " + return_val);
}

5

on pytut
parsonized

{  // 5
   function f(param_1, param_2, param_3) {
    var result = param_3 + param_1 + param_2;
    return result;
   };

   let x = "x", y = "y", z = "z";
   let return_val = f(/* pass x, y & z in the right order */);

   console.assert(return_val === "xyz", "5: return_val === " + return_val);
}

6

on pytut
parsonized

{  // 6
   function f(param_1, param_2, param_3) {
    var result = param_2 + param_1 + param_3;
    return result;
   };

   let x = "x", y = "y", z = "z";


   let return_val = f(/* pass x, y & z in the right order */);

   console.assert(return_val === "xzy", "6: return_val === " + return_val);
}

7

on pytut
parsonized

{  // 7
   function f(param_1, param_2, param_3) {
    var result = /* arrange the params to pass the assert */;
    return result;
   };

   let arg_1 = "z", arg_2 = "y", arg_3 = "x";
   let return_val = f(arg_1, arg_2, arg_3);

   console.assert(return_val === "xzy", "7: return_val === " + return_val);
}

8

on pytut
parsonized

{  // 8
   function f(param_1, param_2, param_3) {
    var result = /* arrange the params to pass the assert */;
    return result;
   };

   let arg_1 = "z", arg_2 = "y", arg_3 = "x";
   let return_val = f(arg_1, arg_2, arg_3);

   console.assert(return_val === "yxz", "8: return_val === " + return_val);
}




