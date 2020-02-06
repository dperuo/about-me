.. ATTENTION::
   We DEPRECIATED this version of the playbook on 2020-02-06. Please use our `version on Gitbook <https://playbook.derekperuo.net>`_.

**Last Update: 2019-07-31**

Derek's Playbook
================

.. _Hanno: http://playbook.hanno.co/
.. _thoughtbot: http://playbook.thoughtbot.com/

Hello and welcome to my playbook. It details how I to build projects. It's a living document that updates often. Hat tips to `thoughtbot`_ and `Hanno`_ for the idea.


Use Systems and Checklists
--------------------------

Use `good defaults <https://en.wikipedia.org/wiki/Convention_over_configuration>`_. Use systems and checklists. Use common architectures and style guides for all projects.


Keep Things Simple and Easy to Understand
-----------------------------------------

Look for simple, elegant solutions. Look for future-proof solutions. Subtract and delete before adding new code. The best solutions `look like magic <https://www.youtube.com/watch?v-r2CbbBLVaPk>`_ and should `Just Work™️ <https://en.wikipedia.org/wiki/Principle_of_least_astonishment>`_.



Done Is Better Than Perfect
---------------------------

Perfection takes too long. Iterate `often <https://www.youtube.com/watch?v-jHyU54GhfGs>`_. Keep the `feedback loop <https://en.wikipedia.org/wiki/OODA_loop>`_ as short as possible. `Disagree and commit <https://www.amazon.jobs/principles>`_ when needed.



Work Autonomously, Take Ownership
---------------------------------

No blame. No excuses. Say what you mean, mean what you say, don't be mean when you say it. Deliver as promised. Trust your team to do the same.



Ask Questions, Give Answers
---------------------------

Communicate with your team. Ask questions, share answers. Avoid silos. Spread knowledge fast. Trust your team to do the same.



Don't Repeat Yourself
---------------------

Don't reinvent the wheel. Start with existing options and iterate from there.



Automate Everything
-------------------

Automate everything. This lets you focus on `deep work <http://calnewport.com/blog/2012/11/21/knowledge-workers-are-bad-at-working-and-heres-what-to-do-about-it/>`_.



Code Should Do One Thing Well
-----------------------------

Code should follow `Unix philosophy <https://en.wikipedia.org/wiki/Unix_philosophy>`_:

#. Each thing does one thing well.
#. Each thing is self-contained.
#. Larger, more complex things build on top of smaller, simpler things.
#. Things can work together using a simple API.


Code Should Be Explicit
-----------------------

The purpose of your code should be clear, direct, and easy to grok without searching the rest of the codebase. Avoid implied code. Leave no room for confusion or doubt about what your code does.



Make Code Clear at the Point of Use
-----------------------------------

Include all the words needed to avoid ambiguity. Design methods and properties to be clear and concise. When evaluating a design, reading a declaration is seldom sufficient; always examine a use case to make sure it looks clear in context.



Use Parameter Defaults When Possible
------------------------------------

Any parameter with a single commonly-used value is a candidate for a default.



Use Coding Patterns When Possible
---------------------------------

`Don't Repeat Yourself`_.



Use the Best Tool for the Job
-----------------------------

Don't put `square pegs in round holes <https://en.wikipedia.org/wiki/Square_peg_in_a_round_hole>`_. Use the right tool for the task at hand.



Avoid Excessive Brevity
-----------------------

Although code can be compact, it is an anti-pattern to write the smallest possible code with the fewest characters. Brevity, where it occurs, is a side-effect of features in the programming language that naturally reduce boilerplate.



Avoid Obscure Terms
-------------------

Don’t say “epidermis” if “skin” will do. `Terms of art <https://en.wiktionary.org/wiki/term_of_art>`_ are an essential communication tool, but should only be used to capture crucial meaning that would otherwise be lost. If you do use a term of art:

- **Don't Surprise an Expert**: People already familiar with the term will be surprised and probably angered if we appear to have invented a new meaning for it.

- **Don't Confuse a Beginner**: People trying to learn the term is likely to do a web search and find its traditional meaning.



Avoid Abbreviations
-------------------

Abbreviations are hard to grok. Use `Descriptive And Meaningful Phrases <https://medium.com/mutual-of-omaha-digital-experience-and-design-team/damp-programming-reviving-readability-d84647cc5b2e>`_ instead.



Keep the End User in Mind
-------------------------

Users should be the heroes of their own stories. Actions should have a narrative with well-defined beginnings, middles, and ends. `Don't make users think <http://www.uxbooth.com/articles/10-usability-lessons-from-steve-krugs-dont-make-me-think/>`_. Reward users when they succeed. The best narratives `adapt to the user <http://www.uxbooth.com/articles/progressive-content/>`_.
