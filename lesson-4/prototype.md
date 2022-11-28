#### Practice 1:
  - Viết 1 constructor tên `Airplane` nhận vào 1 argument `name`
  - Các instances của `Airplane` khi khởi tạo mặc định sẽ có 1 method `isFlying` có value là false
  - Xử lý để các instances của `Airplane` có các method `takeOff()` và `land()`, trong đó:
    + Nếu airplane cất cánh (gọi `takeOff()`), khi đó `isFlying()` sẽ được set thành `true`
    + Nếu airplan hạ cánh (gọi `land()`), khi đó `isFlying()` sẽ được set thành `false`

#### Practice 2:
  - Write a Person Constructor that initializes `name` and `age` from arguments.
  - All instances of Person should initialize with an empty `stomach` array.
  - Give instances of Person the ability to `.eat("someFood")`:
      + When eating an edible, it should be pushed into the `stomach`.
      + The `eat` method should have no effect if there are 10 items in the `stomach`.
  - Give instances of Person the ability to `.poop()`:
      + When an instance poops, its `stomach` should empty.
  - Give instances of Person a method `.toString()`:
      + It should return a string with `name` and `age`. Example: "Mary, 50"
