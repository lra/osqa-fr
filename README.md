This is a WIP french translation of OSQA

To test it, put it in the following folder of your OSQA installation:

    locale/fr/LC_MESSAGES

And launch the command:

    django-admin.py compilemessages

To regenerate the django.po file with the new messages included in the latest
revision of OSQA, use the following command:

    django-admin.py makemessages -l fr
