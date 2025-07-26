
---

### 📄 `delete.md`

```markdown
# Delete operation in Django shell

```python
from bookshelf.models import Book

# Retrieve and delete the book
book = Book.objects.first()
book.delete()

# Confirm deletion
print(Book.objects.all())
# Output: <QuerySet []>

