Introduction
-----------------------------------------------------

Please read the following, watch the videos, and try to solve the problems.


Solving Mixed-up Code Problems
==================================

If you see a problem like the one below you will need to put the mixed-up
code in the correct order on the right side. You
may need to indent the blocks as well.  There may also be extra blocks that are not
needed in a correct solution that you can leave on the left side. Click the "Check" button
to check your solution.

See the video below for an example.

.. youtube:: Rf7oWHlo-e0
    :divid: iwgex1-parsons1-p3
    :optional:
    :width: 650
    :height: 415
    :align: center

Try to solve the following mixed-up code problem.  This problem doesn't require any indentation.

.. parsonsprob:: intro-simple-parsons-no-indent-p3
   :numbered: left
   :adaptive:
   :practice: T
   :order: 3, 1, 2, 0

   Drag the blocks from the left and put them in the correct order on the right. The text in each block
   defines the order.
   -----
   First block
   =====
   Second block
   =====
   Third block

Try to solve the following mixed-up code problem. This problem requires indentation.

.. parsonsprob:: intro-simple-parsons-indent-p3
   :numbered: left
   :adaptive:
   :practice: T
   :order: 3, 1, 2, 0

   Drag the blocks from the left and put them in the correct order on the right with the correct indentation.
   The text in each block defines the order and indentation.
   -----
   First block
   =====
   Second block
   =====
       Third block that needs to be indented

Try to solve the following mixed-up code problem. This problem requires indentation and has extra blocks that are not needed in a correct solution.

.. parsonsprob:: intro-simple-parsons-indent-with-dist-p3
   :numbered: left
   :adaptive:
   :practice: T
   :order: 3, 1, 2, 0

   Drag the blocks from the left and put them in the correct order on the right with the correct indentation.
   There is an extra block that is not needed in the correct solution.
   -----
   First block
   =====
   Second block
   =====
   Extra block that is not needed #paired: This block is not needed
   =====
       Third block that needs to be indented

The mixed-up code problems have a "Help me" button at the bottom of the
problem. Once you have checked at least three incorrect solutions you can
click the button for help.  It will remove an incorrect code block, if you used
one in your solution, or combine two blocks into one if there are more
than three blocks left.

See the video below for an example.

.. youtube:: QejZ7u642IU
    :divid: iwgex1-parsons2-p3
    :optional:
    :width: 650
    :height: 415
    :align: center

Solving Write Code Problems
==============================

If you see a problem like the one below, you will need to write code.  The problem
will have unit tests that you can run to check that your code is working
correctly.  Click on the "Run" button to compile and run your code.  Look after
the code area for compiler errors and/or unit test results.

See the video below for an example.

.. youtube:: piPz0kh8gMk
    :divid: iwgex1-code-p3
    :optional:
    :width: 650
    :height: 415
    :align: center

Finish writing the code for the following problem.

.. activecode:: intro-sample-write-code-p3
    :practice: T
    :autograde: unittest

    Write a function called ``double(num)`` that takes a number ``num`` and
    returns the number times 2. For example, ``double(2)`` should return 4 and
    ``double(-1)`` should return -2.  Look below the code to check for any
    compiler errors or the results
    from the test cases.  Be sure to ``return`` the result.
    ~~~~
    def double(num):
        # write code here

    print(double(2))
    print(double(-1))

    ====
    from unittest.gui import TestCaseGui
    class myTests(TestCaseGui):

        def testOne(self):
            self.assertEqual(double(2),4,"double(2)")
            self.assertEqual(double(3),6,"double(3)")
            self.assertEqual(double(-1),-2,"double(-1)")
            self.assertEqual(double(0),0,"double(0)")
            self.assertEqual(double(11),22,"double(11)")

    myTests().main()

Feedback
==================================

.. shortanswer:: p3-intro-sa

   Please provide feedback here. Please share any comments, problems, or suggestions.


What to do next
============================

.. raw:: html

    <p>Click on the following link to go the practice problems: <a id="p3-practice"><font size="+2">Practice</font></a></p>

.. raw:: html

    <script type="text/javascript" >

      window.onload = function() {

        a = document.getElementById("p3-practice")

        // randomly pick one of two relative urls
        var v = Math.floor(Math.random() * 9) + 1;
        if (v % 2 == 0)
        {
              a.href = "p3-write.html"
        }
        else
        {
               a.href = "p3-parsons.html"
        }

        };
    </script>
