# Evgenii Sergeev

## Contact info:

**cell phone:** +7 904 944 5712<br>
**e-mail:** sergeevevit@gmail.com<br>
**telegram:** @sdv_oo<br>
[GitHub](https://github.com/sergeevev-git/)<br>

## About me

He has many years of experience working in service providers. Now I decided to change the direction of activity to programming, as I have always gravitated to this activity. I have the following personal and business qualities: responsibility, efficiency, learning ability, ability to work in a team, energy, high working capacity, active life position.

## My skills:

### Tech stack

-   HTML
-   CSS
-   JavaScript
-   React
-   NodeJS

-   VS Code
-   GIT
-   Docker

## Code Example

**st-mac-address** The MAC-48 address is six groups of two hexadecimal digits (0 to 9 or A to F), separated by hyphens. Your task is to check by given string inputString whether it's a MAC-48 address or not.

```js
function isMAC48Address(macAddr) {
    try {
        let arr = macAddr.split("-");
        let isMacAddr = true;
        let regex = /([A-F]|[a-f]|[0-9])/;
        arr.forEach((element) => {
            !regex.test(element[0]) || !regex.test(element[1])
                ? (isMacAddr = false)
                : (isMacAddr = isMacAddr);
        });
        return isMacAddr;
    } catch (e) {
        throw new Error(false);
    }
}
```

## Courses

### Web development

-   "Python Web Developer", Skillfactory, June 2020-present
-   "JavaScript Junior Frontend Developer", Vladilen Minin, https://vladilen.ru, July 2021-current time
-   "JavaScript + React ‑ from zero to result", Udemy, Ivan Petrichenko, September-December 2019

## Languages

-   _Russian_ - native speaker
-   _English_ - B1
