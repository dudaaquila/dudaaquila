<img align="right" height="200" src= "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNnNhcW9xejczbWhhbzNxejVtbXI1eGNsYXN1MGtiNm1pbWJpM2xsNSZlcD12MV9zdGlja2Vyc19zZWFyY2gmY3Q9cw/2KFQuaBbBD0x38Yk0b/200.webp"/>

```ts
interface Developer {
  name: string;
  age: string;
  education: string;
  learning: string;
  mainLanguage: string;
  love: string;
}

const dudaaquila: Developer = {
  name: "Maria Eduarda de Áquila",
  age: "19 years",
  education: "Studying Computer Science",
  learning: "Supervised Learning, Linear Regression, Fine-Tuning",
  mainLanguage: "Python, TypeScript, Java",
  love: "Cats, Movies, RPG",
};
```

<br>

## Tools ⛏

<p align = "center">
<img src = https://img.shields.io/badge/macOS-14181C?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI0ZGODAwMCIgZD0iTTEyLjE1MiA2Ljg5NmMtLjk0OCAwLTIuNDE1LTEuMDc4LTMuOTYtMS4wNC0yLjA0LjAyNy0zLjkxIDEuMTgzLTQuOTYxIDMuMDE0LTIuMTE3IDMuNjc1LS41NDYgOS4xMDMgMS41MTkgMTIuMDkgMS4wMTMgMS40NTQgMi4yMDggMy4wOSAzLjc5MiAzLjAzOSAxLjUyLS4wNjUgMi4wOS0uOTg3IDMuOTM1LS45ODcgMS44MzEgMCAyLjM1Ljk4NyAzLjk2Ljk0OCAxLjYzNy0uMDI2IDIuNjc2LTEuNDggMy42NzYtMi45NDggMS4xNTYtMS42ODggMS42MzYtMy4zMjUgMS42NjItMy40MTUtLjAzOS0uMDEzLTMuMTgyLTEuMjIxLTMuMjItNC44NTctLjAyNi0zLjA0IDIuNDgtNC40OTQgMi41OTctNC41NTktMS40MjktMi4wOS0zLjYyMy0yLjMyNC00LjM5LTIuMzc2LTItLjE1Ni0zLjY3NSAxLjA5LTQuNjEgMS4wOXpNMTUuNTMgMy44M2MuODQzLTEuMDEyIDEuNC0yLjQyNyAxLjI0NS0zLjgzLTEuMjA3LjA1Mi0yLjY2Mi44MDUtMy41MzIgMS44MTgtLjc4Ljg5Ni0xLjQ1NCAyLjMzOC0xLjI3MyAzLjcxNCAxLjMzOC4xMDQgMi43MTUtLjY4OCAzLjU1OS0xLjcwMSIvPjwvc3ZnPg==&logoWidth=20><img src="assets/rating-macos.svg" height="28">
<img src = https://img.shields.io/badge/PyCharm-14181C?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iIzQwQkNGNCIgZD0iTTcuODMzIDYuNjY2di0uMDU1YzAtMS0uNjY3LTEuNS0xLjc3OC0xLjVINC4zODl2My4wNTVoMS43MjNjMS4xMTEgMCAxLjcyMS0uNjY2IDEuNzIxLTEuNXpNMCAwdjI0aDI0VjBIMHptMi4yMjMgMy4xNjdoNGMyLjM4OSAwIDMuODMzIDEuMzg5IDMuODMzIDMuNDQ1di4wNTVjMCAyLjI3OC0xLjc3OCAzLjUtNC4wMDEgMy41SDQuMzg5djIuOTQ1SDIuMjIzVjMuMTY3ek0xMS4yNzcgMjFoLTl2LTEuNWg5VjIxem00Ljc3OS03Ljc3N2MtMi45NDQuMDU1LTUuMTExLTIuMjIzLTUuMTExLTUuMDU3QzEwLjk0NCA1LjMzMyAxMy4wNTYgMyAxNi4xMTEgM2MxLjg4OSAwIDMgLjYxMSAzLjk0NCAxLjU1NmwtMS4zODkgMS42MWMtLjc3OC0uNzIyLTEuNTU2LTEuMTExLTIuNTU2LTEuMTExLTEuNjU4IDAtMi44NzMgMS4zNzUtMi44ODcgMy4wODQuMDE0IDEuNzA5IDEuMTc0IDMuMDgzIDIuODg3IDMuMDgzIDEuMTExIDAgMS44MzMtLjQ0NSAyLjYxLTEuMTY3bDEuMzkgMS4zODljLS45OTkgMS4xMTItMi4xNjYgMS43NzktNC4wNTQgMS43Nzl6Ii8+PC9zdmc+&logoWidth=20><img src="assets/rating-pycharm.svg" height="28">
<img src = https://img.shields.io/badge/IntelliJ_IDEA-14181C?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iIzAwRTA1NCIgZD0iTTAgMHYyNGgyNFYwem0zLjcyMyAzLjExMWg1djEuODM0aC0xLjM5djYuMjc3aDEuMzl2MS44MzRoLTV2LTEuODM0aDEuNDQ0VjQuOTQ1SDMuNzIzem0xMS4wNTUgMEgxN3Y2LjVjMCAuNjEyLS4wNTUgMS4xMTEtLjIyMiAxLjU1Ni0uMTY3LjQ0NC0uMzkuNzc3LS43MjMgMS4xMS0uMjc3LjI3OS0uNjY2LjU1Ny0xLjExLjY2OGEzLjkzMyAzLjkzMyAwIDAgMS0xLjQ0NS4yNzhjLS43NzggMC0xLjQ0NC0uMTY3LTEuOTQ0LS40NDVhNC44MSA0LjgxIDAgMCAxLTEuMjc5LTEuMDU2bDEuMzktMS41NTVjLjI3Ny4zMzQuNTU1LjU1NS44MzMuNzIyLjI3Ny4xNjcuNjExLjI3OC45NDUuMjc4LjM4OSAwIC43MjEtLjExMSAxLS4zODkuMjIxLS4yNzguMzMzLS42NjcuMzMzLTEuMjc4ek0yLjIyMiAxOS41aDlWMjFoLTl6Ii8+PC9zdmc+&logoWidth=20><img src="assets/rating-intellij.svg" height="28">
<br>
<img src = https://img.shields.io/badge/Claude-14181C?style=for-the-badge&logo=claude&logoColor=FF8000><img src="assets/rating-claude.svg" height="28">
<img src = https://img.shields.io/badge/Gemini-14181C?style=for-the-badge&logo=googlegemini&logoColor=40BCF4><img src="assets/rating-gemini.svg" height="28">
<img src = https://img.shields.io/badge/Google_Colab-14181C?style=for-the-badge&logo=googlecolab&logoColor=00E054&logoWidth=20><img src="assets/rating-colab.svg" height="28">
</p>

<p align="center"><sub>★ Nível de Conhecimento (0 to 5) &nbsp;·&nbsp; ♥ Favorite</sub></p>

<br>

## Languages ✉

<p align = "center">
<img src = https://img.shields.io/badge/Python-14181C?style=for-the-badge&logo=python&logoColor=00E054><img src="assets/rating-python.svg" height="28">
<img src = https://img.shields.io/badge/TypeScript-14181C?style=for-the-badge&logo=typescript&logoColor=40BCF4><img src="assets/rating-typescript.svg" height="28">
<img src = https://img.shields.io/badge/Java-14181C?style=for-the-badge&logo=openjdk&logoColor=FF8000><img src="assets/rating-java.svg" height="28">
</p>

<br>


## Find me! ✮

<p align="center">
<a href="https://www.linkedin.com/in/SEU_USUARIO/"><img src=https://img.shields.io/badge/LinkedIn-14181C?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iIzQwQkNGNCIgZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYy0xLjE0NCAwLTIuMDYzLS45MjYtMi4wNjMtMi4wNjUgMC0xLjEzOC45Mi0yLjA2MyAyLjA2My0yLjA2MyAxLjE0IDAgMi4wNjQuOTI1IDIuMDY0IDIuMDYzIDAgMS4xMzktLjkyNSAyLjA2NS0yLjA2NCAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+&logoWidth=20></a><a href="https://letterboxd.com/SEU_USUARIO/"><img src=https://img.shields.io/badge/Letterboxd-14181C?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PGNpcmNsZSBjeD0iNiIgY3k9IjEyIiByPSI1LjUiIGZpbGw9IiNGRjgwMDAiLz48Y2lyY2xlIGN4PSIxOCIgY3k9IjEyIiByPSI1LjUiIGZpbGw9IiM0MEJDRjQiLz48Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSI1LjUiIGZpbGw9IiMwMEUwNTQiLz48L3N2Zz4=&logoWidth=20></a><a href="https://www.duolingo.com/profile/SEU_USUARIO"><img src=https://img.shields.io/badge/Duolingo-14181C?style=for-the-badge&logo=duolingo&logoColor=00E054></a>
</p>

<br>

<p align="center">
<img src="assets/cat.svg" width="96" alt="pixel cat">
<br>
<sub>meow.</sub>
</p>
