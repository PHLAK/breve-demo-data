---
title: Markdown Examples
link: Markdown
weight: 10
---

Here's some example content, written in markdown.

[[TOC]]

# Paragraphs & Headers

I'm a test paragraph, please ignore me. Nunc congue lacus vitae metus vehicula,
et viverra ex pharetra. Pellentesque vehicula nisi neque, et tincidunt urna
ultricies non.

## Second Level Header
Nulla facilisi. Phasellus lobortis, risus ac fringilla tincidunt, mi neque consequat
lectus, in semper sem tellus ut ante.

### Third Level Header
 
Mauris pulvinar massa nec lacus vestibulum, sed molestie leo tincidunt. Aliquam
bibendum sem mauris, vitae elementum ipsum condimentum sit amet.

#### Fourth Level Header

Maecenas nec sem sit amet diam sollicitudin placerat lobortis vel libero.

# Tables

| Foo     | Bar     | Baz | Qux  |
| ------- | ------- | :-: | :--: |
| Alpha   | Delta   |  1  |  ✅️  |
| Bravo   | Echo    |  2  |  ❌️  |
| Charlie | Foxtrot |  3  |  ✅️  |

# Code Highlighting

## PHP

```php
class DeepThought {
    public function calculateAnswer(string $question): mixed
    {
        return match ($question) {
            case 'What is the answer to life, the universe and everything?' => 42,
            case 'Where do you want for lunch?' => "I don't know, what do you want?",
            case 'Are we there yet?' => 'No.',
            default => throw new UnknownQuestionException
        }
    }    
}
```

## JavaScript

```javascript
function isPoetic(poem) {
    if (poem.authoredByVogon) {
        return false; // Vogon poetry is never poetic
    }

    return true;
};
```

## Python

```python
class Marvin:
    def __init__(self):
        self.mood = "depressed"

    def predict_odds(self):
        return "Probability of success: 0.00000000042%. We might as well give up."
```

# Lists

## Ordered

1. Step one...
2. Step two...
3. Step three...

## Unordered

  - Foo
  - Bar
  - Baz

## Checklist

  - [X] Milk
  - [ ] Eggs
  - [ ] Bread

# Alerts

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
> 
> This is a test of a multi-paragraph alert.
