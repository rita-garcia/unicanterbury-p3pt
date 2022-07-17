Self-efficacy Survey 1
-----------------------------------------------------

Think about yourself and your learning when answering the following questions.

==============

.. poll:: p3-CS-self-efficacy-1
    :option_1: Strongly disagree
    :option_2: Disagree
    :option_3: Neither agree nor disagree
    :option_4: Agree
    :option_5: Strongly agree
    :results: instructor

    Generally I have felt secure about attempting computer programming problems.

.. poll:: p3-CS-self-efficacy-2
    :option_1: Strongly disagree
    :option_2: Disagree
    :option_3: Neither agree nor disagree
    :option_4: Agree
    :option_5: Strongly agree
    :results: instructor

    I am sure I could do advanced work in computer science.

.. poll:: p3-CS-self-efficacy-3
    :option_1: Strongly disagree
    :option_2: Disagree
    :option_3: Neither agree nor disagree
    :option_4: Agree
    :option_5: Strongly agree
    :results: instructor

    I am sure that I can learn programming.

.. poll:: p3-CS-self-efficacy-4
    :option_1: Strongly disagree
    :option_2: Disagree
    :option_3: Neither agree nor disagree
    :option_4: Agree
    :option_5: Strongly agree
    :results: instructor

    I think I could handle more difficult programming problems.

.. poll:: p3-CS-self-efficacy-5
    :option_1: Strongly disagree
    :option_2: Disagree
    :option_3: Neither agree nor disagree
    :option_4: Agree
    :option_5: Strongly agree
    :results: instructor

    I can get good grades in computer science.

.. poll:: p3-CS-self-efficacy-6
    :option_1: Strongly disagree
    :option_2: Disagree
    :option_3: Neither agree nor disagree
    :option_4: Agree
    :option_5: Strongly agree
    :results: instructor

    I have a lot of self-confidence when it comes to programming.

For the next questions please select the answer that best
matches your familiarity, experience, and confidence
about the specified concept(s).

.. poll:: p3-prog-se-var-7
    :option_1: I am unfamiliar with these concepts
    :option_2: I know what they mean, but havevn't used them in a program
    :option_3: I have used these concepts in a program, but am not confident about my ability to use them
    :option_4: I am confident in my ability to use these concepts in simple programs
    :option_5: I am confident in my ability to use these concepts in complex programs
    :results: instructor

    Variables and assignments like ``a = 3``

.. poll:: p3-prog-se-str-8
    :option_1: I am unfamiliar with this concept
    :option_2: I know what it means, but havevn't used it in a program
    :option_3: I have used this concept in a program, but am not confident about my ability to use it
    :option_4: I am confident in my ability to use this concepts in simple programs
    :option_5: I am confident in my ability to use this concepts in complex programs
    :results: instructor

    Strings like ``str = "hello world"``

.. poll:: p3-prog-se-loop-9
    :option_1: I am unfamiliar with this concept
    :option_2: I know what it means, but havevn't used it in a program
    :option_3: I have used this concept in a program, but am not confident about my ability to use it
    :option_4: I am confident in my ability to use this concept in simple programs
    :option_5: I am confident in my ability to use this concept in complex programs
    :results: instructor

    Loops/Iteration like ``for n in nums:``

.. poll:: p3-prog-se-cond-10
    :option_1: I am unfamiliar with this concept
    :option_2: I know what it means, but havevn't used it in a program
    :option_3: I have used this concept in a program, but am not confident about my ability to use it
    :option_4: I am confident in my ability to use this concept in simple programs
    :option_5: I am confident in my ability to use this concept in complex programs
    :results: instructor

    Conditionals/Selection Statements like ``if x < 3:``

.. poll:: p3-prog-se-func-11
    :option_1: I am unfamiliar with this concept
    :option_2: I know what it means, but havevn't used it in a program
    :option_3: I have used this concept in a program, but am not confident about my ability to use it
    :option_4: I am confident in my ability to use this concept in simple programs
    :option_5: I am confident in my ability to use this concept in complex programs
    :results: instructor

    Functions like ``def get_odd(nums)``

.. poll:: p3-prog-se-list-dic-12
    :option_1: I am unfamiliar with these concepts
    :option_2: I know what they mean, but havevn't used them in a program
    :option_3: I have used these concepts in a program, but am not confident about my ability to use them
    :option_4: I am confident in my ability to use these concepts in simple programs
    :option_5: I am confident in my ability to use these concepts in complex programs
    :results: instructor

    Lists like ``a = ["red", "green"]`` and dictionaries like ``d = {"red": 2, "green": 3}``.

Thanks for filling this survey and let us know you better!

What to do next
============================
.. raw:: html

    <p>Click on the following link to start practice: <b><a id="fl-next">Practice</a></b></p>

.. raw:: html

    <script type="text/javascript" >

      window.onload = function() {

        a = document.getElementById("fl-next")

        // randomly pick one of two relative urls
        var v = Math.floor(Math.random() * 9) + 1;
        if (v % 2 == 0)
        {
              a.href = "fl-toggle.html"
        }
        else
        {
               a.href = "fl-write.html"
        }

        };
    </script>
