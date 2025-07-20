# Retrieve operation in Django shell

```python
from bookshelf.models import Book

# Retrieve the first book
book = Book.objects.first()

# Print book details
print(book.title)
print(book.author)
print(book.publication_year)
