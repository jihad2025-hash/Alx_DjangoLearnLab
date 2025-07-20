# Retrieve operation in Django shell

```python
from bookshelf.models import Book

book = Book.objects.first()
print(book.title)
print(book.author)
print(book.publication_year)
# Output:
# 1984
# George Orwell
# 1949
