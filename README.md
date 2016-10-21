# Python_Bookstore_Desktop_App
This is a desktop app supports add/update/delete/list operations to books information, just like a bookstore. 
Depend on python tkinter and sqlite3 package.

To install it to work like a desktop app, do following steps:
1. pip install py2app
2. py2applet --make-setup bookstore.py #this step will create a setup.py file
3. edit setup.py file to add DATA_FILES = ['books.db']
4. python3 setup.py py2app

See screenshot for the UI.
