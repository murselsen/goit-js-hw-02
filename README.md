# Goit Javascript | Homework 2 [![Pages Build](https://github.com/murselsen/goit-js-hw-02/actions/workflows/pages/pages-build-deployment/badge.svg?branch=main)](https://github.com/murselsen/goit-js-hw-02/actions/workflows/pages/pages-build-deployment)

This repo was created for assignment 2 of the Goit Javascript course. Below is the assignment
tasks have descriptions and examples of their use.

## Tasks

### Mission 1: makeTransaction

This function allows you to determine whether you have enough credits to buy a certain amount of droids.
and returns the appropriate message.

**Usage:**

```js
console.log(makeTransaction(5, 3000, 23000)); // "You ordered 5 droids worth 15000 credits!"

console.log(makeTransaction(10, 5000, 8000)); // "Insufficient funds!"
```

### Mission 2: formatMessage

This function truncates the message if the message exceeds a certain length
and adds "..." at the end.

**Usage:**

```js
console.log(formatMessage('Curabitur ligula sapien', 16)); // "Curabitur ligula..."

console.log(formatMessage('Vestibulum facilisis purus nec', 20)); // "Vestibulum facilisis..."
```

### Mission 3: checkForSpam

This function checks if the given message contains spam. Message
Returns true if it contains the words "spam" or "sale", false otherwise.

```js
console.log(checkForSpam('Get best sale offers now!')); // true

console.log(checkForSpam('Latest technology news')); // false
```

### Mission 4: getShippingCost

This function returns the shipping cost to a specific country. If the country is in the list
or it will return an appropriate message.

````js
console.log(getShippingCost('Australia')); // "Shipping to Australia will cost 170 credits"

console.log(getShippingCost('Germany')); // "Sorry, there is no delivery to your country"

