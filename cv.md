# Valery Sotnik

### Contact information:

- **Phone**: +48 731868371
- **E-mail**: *cmvaltime@gmail.com*
- **Telegram**: _@cm_val92_
- **GitHub**: [valsotnik](https://github.com/valsotnik)

### About Myself:

    I graduated from university as an mechanical engineer.
    Now I decide to change direction, the IT sphere has always been interesting to me and the time has come.
    I have good communication skills, I am stress-resistant,
    I work well in a team and am determined to absorb new knowledge.
    I have experience in the development of applications on JavaScript
    and Angular  banking application development in a team on a project.

### Skills and Proficiency:

- Angular
- JavaScript
- TypeScript
- Webpack
- HTML
- CSS/SCSS
- Git
- GitLab/GitHub
- VS Code
- Figma

### Code example:

```
	function revrot(str, sz) {
		if (sz < 1 || sz > str.length) return '';
		let rotate  = x => x.slice(1) + x.slice(0, 1);
		let reverse = x => x.split('').reverse().join('');
		let cubes = x => x.split('').reduce((a, b) => a + Math.pow(b,3), 0);
		return str.match(new RegExp('.{' + sz + '}', 'g'))
							.map(x => cubes(x) % 2 ? rotate(x) : reverse(x))
						 	.join('')}
```
