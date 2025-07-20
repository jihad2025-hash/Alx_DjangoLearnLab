# Update operation in Django shell

```python
from bookshelf.models import Book

book = Book.objects.first()
book.title = "Nineteen Eighty-Four"
book.save()

print(book.title)
# Output: Nineteen Eighty-Four
