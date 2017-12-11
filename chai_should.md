JS Mocha Test

``` Mocha & Chai Should

var assert = require("assert");
var expect = require('chai').expect;
var should = require('chai').should();
var $ = require('jquery')


describe("Array", function() {
  describe("#indexOf()", function() {
    it("should return -1 when the value is not present", () => {
      var arr = [1, 2, 3, 4, 5]
      var newArr = [...arr]
      arr.should.to.deep.equal(newArr)
      // expect(arr).to.deep.equal(newArr)
    });
  });
});

describe('ObjectEqual', function() {
  describe('#ObjectEqual()', function() {
    it('two object should equal', () => {
      var foo = {
        age: 18,
        name: 'foo',
      }
      var bar = {
        age: 18,
        name: 'bar',
      }
      // foo.should.to.deep.equal(bar)
      // foo.should.include('foo')
      foo.name.should.to.include('foo');

      var age1 = 18
      var age2 = 18

      let person = {}
      person.should.to.be.empty;
      age1.should.to.equal(age2)
      age1.should.to.be.a('number')
    });
  })
});

describe("年齡", function() {
  describe("#AgePlus()", function() {
    it("年齡要可以正確加總", () => {
      var expected = 20
      var actual = 20
      assert.equal(expected, actual)
    });
  });
});


describe('Test Instanceof', () => {
  describe('#InstanceOf()', () => {
    it('Person必需是Class', () => {
      let person = {}
      person.should.to.be.an.instanceOf(Object)

    })
  })
})

describe('Test Array have Length', () => {
  describe('#ArrayLength()', () => { 
    it('Any Array should have length', () => {
      let arr = [1, 2, 3, 4]
      arr.should.have.lengthOf(4)
    })
  })
})
```
