# Retrieve operation in Django shell

```python
from bookshelf.models import Book

# Retrieve the book using get
book = Book.objects.get(title="1984")

# Print book details
print(book.title)  # Output: 1984
print(book.author)
print(book.publication_year)
