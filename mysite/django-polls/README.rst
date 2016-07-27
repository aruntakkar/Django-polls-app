
 =====
 Polls
 =====

 Polls is simple Django app to conduct web-based polls. For each
 question, visitors can choose between a fixed number of answers.

 Detailed documentation is in the "docs" directory.

 Quick Start:
 ____________

 1. Add "polls" to your INSTALLED_APPS setting like this:

    INSTALLED_APPS = [
        ...
        'polls',
    ]

2. Include the polls URLconf in your project urls.py like this::

    url(r'^polls/', include('polls.url')),

3. Run 'Python manage.py migrate' to create the polls model.

4. Start the development server and visit http://127.0.0.1:8000/admin/
to create a poll (you'll need the Admin app enabled.)

5. Visit http://127.0.0.1:8000/polls/ to participate in the poll.
