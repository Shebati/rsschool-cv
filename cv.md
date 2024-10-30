# Maksim Shabakhau
___
![Me](/images/me.png)

## Contacts
___
+ Location: Gomel, Belarus
+ Phone: +375 (44) 538-60-08
+ Email: pingvi.maks@mail.ru
+ GitHub: [Shebati](https://github.com/Shebati)

## About me
___
I am a proactive and adaptable professional with strong
communication skills and a proven ability to solve problems
effectively. I thrive in dynamic environments and am always
eager to learn new concepts and techniques to enhance my
expertise. My passion for continuous improvement drives
me to tackle challenges head-on, collaborate with diverse
teams, and contribute positively to organizational goals.

## Skills
___
+ JavaScript (Basic)
+ HTML
+ CSS
+ Git

## Code example
___
### Description
Finish the solution so that it takes an input n (integer) and returns a string that is the decimal representation of the number grouped by commas after every 3 digits.

Assume: 0 <= n <= 2147483647

``` javascript
function groupByCommas(n) {
    let list = String(n).split("")
    if (list.length <= 3) {
        return list.join("")
    }
    let ind = list.length % 3
    if (ind == 0) {
        ind = 3
    }
    let count = 4
    let j = 0
    for (let i = ind; i < list.length; i += count) {
        if (list.length - i + j < 3) {
            break
        }
        list.splice(i, 0, ",")
        j++
    }
    return list.join("")
}
```

## Languages:
___
+ Russian - Native
+ English - B1+