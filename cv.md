## Edvard Astapovich

### Contacts:
**Tbilisi**

_edvardastapovich@gmail.com_

### About me:
_I am 30 years old. I am from Belarus, now I live in Tbilisi. My goal is to become a JS developer. Now I work in digital cartography. I am an engineer by education, so I am interested in the technical side of the digital world. I want to develop in this direction._

### Skills
_Git, HTML, CSS, preprocessors SCSS ans SASS, framework Bootstrap, JS._

### Code examples
```
const baseCurrencies = ['USD', 'EUR'];
const additionalCurrencies = ['UAH', 'RUB', 'CNY'];

let both = [];
	baseCurrencies.forEach(function(item, i, baseCurrencies) {
		both.push(item);
	});
	additionalCurrencies.forEach(function(item, i, additionalCurrencies) {
		both.push(item);
	})

function availableCurr(arr, missingCurr) {
	let result = 'Доступные валюты:\n';
	if (arr.length === 0) {
		return "Нет доступных валют"
	} else {
		arr.forEach(function(item, i, baseCurrencies) {
			if (item !== missingCurr) {
				result += `${item}\n`
			}
		});
	}
	return result;
}

console.log(availableCurr(both, 'UAH'));
``` 

### Work experience
_I don't have experience as a JS developer yet_

### Education 
* Engineer-geologist. Belarusian State University, 2015
* Fundamentals of web technologies. IT-Academy, 2021
* GIT basics. Udemy, 2022
* RS School. JS/FE PRE-SCHOOL 2022Q2 (JAVASCRIPT)
* Web-development 2022. Udemy

### Languages 
_Russian. Native speaker_
_Belarusian language. Native speaker_
_English. Level B1_
_Polski. Level A2_