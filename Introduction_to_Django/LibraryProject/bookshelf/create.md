Python 3.12.4 (main, Jun  6 2024, 18:26:44) [GCC 11.4.0] on linux
Type "help", "copyright", "credits" or "license" for more information.
(InteractiveConsole)
>>> from bookshelf.models import Book
>>> new_book = Book.objects.create(
... title="1984",
... author="George Orwell",
... publication_year=1949
... )
>>> all_books = Book.objects.all()
>>> for book in all_books:
...     print(book.title, book.author, book.publication_year)
... 
1984 George Orwell 1949
>>> 
>>> 
>>> 