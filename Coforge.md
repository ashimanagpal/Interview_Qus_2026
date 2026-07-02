🚀 Coforge React JS Interview Questions – Round 1

1) Explain how React's reconciliation algorithm works internally. How does the Virtual DOM minimize DOM manipulations?

2)Explain the difference between useMemo, useCallback, and React.memo with real-world scenarios.

3)Compare useEffect, useLayoutEffect, and useInsertionEffect. When should each be used?

4) How would you implement role-based authentication and authorization in React?

5) How would you implement infinite scrolling with server-side pagination and caching?

6)Explain Redux Toolkit internally. How does it allow direct state mutation while maintaining immutability?

7) How would you manage shared state across multiple micro-frontends?

8) Why does React sometimes delay rendering until after multiple state updates? How does the Event Loop contribute to React's batching mechanism?.
 
9) Write a polyfill for Promise.allSettled()

10) console.log("A");
asyncfunctionfoo() {
console.log("B");
awaitPromise.resolve();
console.log("C");
awaitPromise.resolve();
console.log("D");
}
foo();
Promise.resolve().then(() => {
console.log("E");
});
setTimeout(() => {
console.log("F");
}, 0);
console.log("G");

11) functioncreateCounter() {
letcount=0;

functionincrement() {
count++;

if (count<3) {
increment();
 }

returncount;
 }

returnincrement;
}

constfn=createCounter();

console.log(fn());
console.log(fn());
