Introduction to the Timed Pretest
-----------------------------------------------------

The pretest is a timed test.  This means that you
will see a countdown of the time on the top and then
one question at a time with no feedback.  Use the arrow
keys or number keys to move between questions.  When you
have seen all the question a "Finish Exam" button will
be displayed.  Click that button to end your exam, but
only when you are done.

.. timed:: timed_intro
   :timelimit: 5
   :noresult:
   :nofeedback:
   :nopause:

   .. mchoice:: timed_intro_q1_add
      :practice: T
      :answer_a: 3
      :answer_b: 4
      :answer_c: 7
      :answer_d: 7.0
      :correct: c
      :feedback_a: Incorrect!  It will set x to 3 + 4.
      :feedback_b: Incorrect!  It will set x to 3 + 4.
      :feedback_c: It will set x to 3 + 4 = 7
      :feedback_d: Incorrect! It is adding integers so the result will be an integer

      What will the following code print?

      ::

        x = 3 + 4
        print(x)

   .. mchoice:: timed_intro_q2_str_upper
      :practice: T
      :answer_a: hi there
      :answer_b: Hi There
      :answer_c: HI there
      :answer_d: HI THERE
      :correct: d
      :feedback_a: Incorrect!  It will print the string in uppercase.
      :feedback_b: Incorrect!  It will print the string in uppercase.
      :feedback_c: Incorrect!  It will print the string in uppercase.
      :feedback_d: Correct! It will print the sting in all uppercase letters.

      What will the following code print?

      ::

        s = "hi there"
        print(s.upper())


Feedback
==================================

.. shortanswer:: p3-pre-timed-intro-sa

   Please provide feedback here. Please share any comments, problems, or suggestions.

What to do next
============================
.. raw:: html

    <p>Click on the following link to take the pretest: <b><a id="p3-pretest"><font size="+2">Pre Test</font></a></b></p>

.. raw:: html

    <script type="text/javascript" >

      window.onload = function() {

        a = document.getElementById("p3-pretest")
        a.href = "p3-pretest.html"

      };

    </script>
