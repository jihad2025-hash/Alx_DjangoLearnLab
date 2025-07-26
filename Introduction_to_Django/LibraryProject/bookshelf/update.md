
---

### 📄 `update.md`

```markdown
# Update operation in Django shell

```python
from bookshelf.models import Book

# Retrieve the book
book = Book.objects.first()

# Update the book title
book.title = "Nineteen Eighty-Four"
book.save()

print(book.title)
# Output: Nineteen Eighty-Four
