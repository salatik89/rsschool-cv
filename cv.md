# Evgenii Nalimov
## Contacts:
* ### GitHub: [salatik89](https://github.com/salatik89/rsschool-cv/)
* ### Discord: blackcat3799
* ### Email: salatyk23@gmail.com
## About Me:
I am 35 years old, I am studying to be an automation tester, I like doing this. That is why I want to learn JS.
## Skills: 
* Git
* Playwright(Basic)
* Selenium
## Code Examples:
```
export const getHrefAndTextInAtribute = async (page: Page, href: string, index: number) => {
  const getHref = String(await page.locator(`[href^="${href}"]`).nth(index).getAttribute('href'));
  const name = await page.locator(`[href="${getHref}"]`).innerText();
  const url = `${getHref}`.substring(1);
  const id = getHref.replace(`${href}`, "");
  const data = {
    name,
    url,
    id,
  };
  return data;
};
```
## Education:
* ###[JS / Front-end Pre-school(in process)](https://rs.school/courses/javascript-preschool-ru)
## Languages:
* ### Russian
* ### English: level A2
