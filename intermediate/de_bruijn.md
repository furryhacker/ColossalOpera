# Title

Calculating De Bruijn sequences

# Difficulty

Intermediate

# Description

In combinatorial mathematics, a *k-ary* De Bruijn sequence *B(k, n)* of order *n*, named after the Dutch mathematician Nicolaas Govert de Bruijn, is a cyclic sequence of a given alphabet *A* with size *k* for which every possible subsequence of length *n* in *A* appears as a sequence of consecutive characters exactly once.

Each *B(k, n)* has length *k^n*.

A De Bruijn sequence *B(2, 2)* (with alphabet *0* and *1*) is therefore:

    00010111

Similarly, *B("abcd", 2)* (with alphabet "a", "b", "c", and "d") is therefore:

    aabacadbbcbdccdd

For those sequences of length, every bigram is represented in the result. 

# Input Description

You'll be given two inputs *k* and *n*, the first is an integer or a a string of unique characters, the second is the length of the subsequences to ensure are encoded.

# Output Description

Your program should emit a string that encodes the De Bruijn sequence.

# Input

    5 3
    2 4
    abcde 4

# Output

The outputs expected for those (in order) are:

    00010020030040110120130140210220230240310320330340410420430441112113114122123124132133134142143144222322423323424324433343444
    0000100110101111
    aaaabaaacaaadaaaeaabbaabcaabdaabeaacbaaccaacdaaceaadbaadcaaddaadeaaebaaecaaedaaeeababacabadabaeabbbabbcabbdabbeabcbabccabcdabceabdbabdcabddabdeabebabecabedabeeacacadacaeacbbacbcacbdacbeaccbacccaccdacceacdbacdcacddacdeacebacecacedaceeadadaeadbbadbcadbdadbeadcbadccadcdadceaddbaddcadddaddeadebadecadedadeeaeaebbaebcaebdaebeaecbaeccaecdaeceaedbaedcaeddaedeaeebaeecaeedaeeebbbbcbbbdbbbebbccbbcdbbcebbdcbbddbbdebbecbbedbbeebcbcbdbcbebcccbccdbccebcdcbcddbcdebcecbcedbceebdbdbebdccbdcdbdcebddcbdddbddebdecbdedbdeebebeccbecdbecebedcbeddbedebeecbeedbeeeccccdccceccddccdeccedcceecdcdcecdddcddecdedcdeececeddcedeceedceeeddddeddeededeeee

# Notes

Have an idea for a challenge? Please share it on /r/dailyprogrammer_ideas. 