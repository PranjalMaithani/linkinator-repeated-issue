- `npm install`
- `npm start`
- `npm run linkinator` to run linkinator

pageA has 2 broken links:

- /broken123
- /broken456

pageB has 2 broken links

- /broken123
- /broken789

The /broken123 link is a common broken link in the 2 pages. When I run linkinator it is not informing me of `/broken123` in pageB

```
pageA/index.html
  [404] broken123
  [404] broken456
pageB/index.html
  [404] broken789
```

This is the output I'm getting
