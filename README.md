# epai2session2
Session 2 assignment of EPAi2.0


test_function_name_had_cap_letter - changed the cap letter in Function reserved_Function

Something and SomethingNew are cyclically referenced, so they have to be forcefully emptied.
Used gc.collect() for garbage collection

Why is compare_string_new better than compare_string_old? The latter function checks character by character and returns a True / False 
depending on the string inputted. In the former function the string is interned so Python remembers the memory location and is able to 
reference the same in a mch faster fashion. We also use sets which help in saving time.


Commented out the sleep function as it is not required
