# Learn from Chai or Code

## Install
```bash
npm install learn-from-chai-or-code
```

## Usage
```javascript

const chai = require('chai');

const expect = chai.expect;

const { add } = require('learn-from-chai-or-code');

describe('add', () => {
  it('should add two numbers', () => {
    expect(add(1, 2)).to.equal(3);
  });
});
```

## License
MIT
```