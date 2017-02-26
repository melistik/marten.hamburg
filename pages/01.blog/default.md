---
sitemap:
    changefreq: monthly
    priority: 1.03
content:
    items: '@self.descendants'
    order:
        by: date
        dir: desc
    limit: 8
    pagination: true
feed:
    description: 'Happiness is not a destination. It is a way of life.n'
    limit: 5
pagination: true
---