# Delete operation in Django shell

```python
from bookshelf.models import Book

book = Book.objects.first()
book.delete()

print(Book.objects.all())
# Output: <QuerySet []>
