Download Link: https://assignmentchef.com/product/solved-cpsc-121-lab-4
<br>
Functions Create a program that:

<ol>

 <li>Declare a string and assign it an arbitrary starting value of <strong>your </strong>choosing</li>

 <li>Display the current contents of <strong>your </strong>string, then displays the following menu. If a function returns a string, it should replace the contents of <strong>your </strong>string, otherwise display the resulting information and leave the string unchanged. Function headers are provided; they should be used <strong>as-is </strong>in the manner appropriate<strong>.</strong>

  <ol>

   <li>string getInput()

    <ol>

     <li>MUST use getline (with cin)

      <ol>

       <li>Due to differences in treatment of the 
 character when we hit enter, cin.ignore may have to be used to fix the input buffer</li>

      </ol></li>

     <li>Reads user input from cin and stores it in the string being used. Contents will set initial state for the string next loop through program.</li>

    </ol></li>

   <li>string printBetween(int a, int b, int step = 1)

    <ol>

     <li>Will return a string containing all numbers between a and b, including a and b, counting <strong>up</strong></li>

     <li>G. a = 6, b = 3, output = “3456” (don’t use spaces)

      <ol>

       <li>If only two values are provided in the function call, assumes step of 1</li>

      </ol></li>

    </ol></li>

  </ol></li>

</ol>

<ul>

 <li>Order is unassumed, but data is displayed counting up</li>

</ul>

<ol>

 <li>string nonalnum_removed(string input)

  <ol>

   <li>Returns the string provided as input with all characters that are neither digits nor alphabetic removed

    <ol>

     <li>Will probably involve function isalnum (slides/internet for references)</li>

     <li>If a string, str, has its length changed, any saved results from str.length() calls will be STALE, meaning they no longer reflect our data</li>

    </ol></li>

   <li>string alphabet_numberified(string input)

    <ol>

     <li>Returns the string provided as input, except with (only) alphabetic characters converted to their character codes within the string

      <ol>

       <li>“11a11” would become “119711”</li>

      </ol></li>

     <li>int sumDigits(string digitString)

      <ol>

       <li>Attempts to read each character as a digit, and returns the sum</li>

       <li>Inclusion of non-digit characters should result in a notification (via cout) of the character that could not be summed up</li>

      </ol></li>

     <li>void saveString(string savedStr)

      <ol>

       <li>Prints the current string’s contents to a file named &lt;your lab filename&gt;.txt

        <ol>

         <li>You can overwrite the previous contents</li>

        </ol></li>

       <li>Asks the user if they would like to return to step 2, or exit.</li>

      </ol></li>

    </ol></li>

  </ol></li>

</ol>


