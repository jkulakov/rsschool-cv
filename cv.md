# My CV

## Ivan Kulakov
---

## Contacts:

* Email: codykulakov@gmail.co
* Discord: iMaverick
* GitHub: jKulakov

---
## About myself

I'm 32 year old man from Saint-Petersburg. I want to learn Front-end in RSSchool for change my current job.

---

## Skills

* Git/Github
* HTML
* CSS
* JS (basic)
* Avacode / Photoshop
* PHP & MySQL (basic)

---
## Code Examples
```
let subMenu = document.getElementsByClassName("menu_sub");
	let menuExistSub = [];


for(let i = 0; i < subMenu.length; i++){
	let parentList = subMenu[i].parentElement;
	menuExistSub[i] = parentList.querySelector("a.menu__link");

	menuExistSub[i].onclick = function() {

		if(subMenu[i].className == "menu menu_sub menu_active"){
			subMenu[i].className = "menu menu_sub";
			console.log('1')
			return false
		} else {

		for(let z = 0; z < subMenu.length; z++) {
			subMenu[z].className = "menu menu_sub";
		}
		subMenu[i].className = "menu menu_sub menu_active";
		return false

	}

}
}
```
---

## Education

* Netology
    * [Frontend-разработчик с нуля](https://netology.ru/programs/front-end)
* Udemy
    * [JavaScript + React - с нуля до результата](https://www.udemy.com/course/javascript_full/)
    
---
## Language
* Russian
* English (B1)