![preview|690x388](/screenshots/example.png)
<br>


# install 

```bash

npm i @rn0x/hijri_calendar

```
# example


```js
import Hijri_calendar from '@rn0x/hijri_calendar'

let filename = './example.png'
let title = 'أذكار '
let text = 'اللّهم اغفر لي، وإهدني، وأرزقني، وعافني، أعوذ بالله من ضيق المقام يوم القيامة'


await Hijri_calendar(title, text, filename).then(e => {
    console.log(e); // return - filename - today - Hijri - Gregorian
});

//or

let calendar = await Hijri_calendar(title, text, filename);

console.log(calendar);  // return - filename - today - Hijri - Gregorian

```


