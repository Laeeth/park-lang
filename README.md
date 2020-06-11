# park-lang
Park programming language

1. Install docker
2. Clone this repo
3. cd park-lang
4. docker run -v $(pwd):/mnt/park -w /mnt/park -it toymachine/park-lang /bin/park examples/hello.prk

## Hello World
```javascript
function main()
{
    print("Hello World!")
}
```

## Basics
```javascript
function main()
{
    let a = 1 /* integer */
    let b = 2 
    let c = true /* bool */
    let d = false 
    let e = "Hello" /* string */
    let f = "World!"

    print(a + b)
    print(c == d)
    print(e + " " + f)
}
```
