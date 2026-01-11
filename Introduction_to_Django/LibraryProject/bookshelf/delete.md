Python 3.12.4 (main, Jun  6 2024, 18:26:44) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
(InteractiveConsole)
>>> from bookshelf.models import Book
>>> # Fetching the book record 
>>> book = Book.objects.get(title="Nineteen Eighty-Four")
>>> # Deleting the record 
>>> book.delete()
(1, {'bookshelf.Book': 1})
>>> 