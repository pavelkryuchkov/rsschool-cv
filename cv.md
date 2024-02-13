# Pavel Kryuchkov

## Contacts

- **Location:** Moscow, Russia

## About me

I want to become a front-end web developer and find new exciting and interesting job.

## Skills

- HTML
- CSS
- JavaScript

## Code Example

**[Write Number in Expanded Form](https://www.codewars.com/kata/5842df8ccbd22792a4000245) from Codewars:** You will be given a number and you will need to return it as a string in Expanded. For example:

```javascript
expandedForm(12); // Should return '10 + 2'
expandedForm(42); // Should return '40 + 2'
expandedForm(70304); // Should return '70000 + 300 + 4'
```

NOTE: All numbers will be whole numbers greater than 0.

```javascript
function expandedForm(num) {
  let res = [];
  let numLen = String(num).length;
  for (digit of String(num)) {
    if (digit === '0') {
      numLen--;
      continue;
    }
    res.push(digit.padEnd(numLen--, '0'));
  }
  return res.join(' + ');
}
```

## Languages

- Russian Native
- English Intermediate
