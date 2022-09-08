# rsschool-cv

https://xtadeushx.github.io/rsschool-cv/cv

# Aleksandr Cherkasov

## Junior Front-End Developer (React)

##### Contact Info

- **Email**: alekscherkasov13@gmail.com

- **Telegram**: @aleksa cherkasov

- **LincedIn**: Alexandr Cherkasov

##### Summary

My goal is to work remotely for a company.
To be apert of a good company

##### Skills

###### HTML5 CSS3 JavaScript

###### Bootstrap 4

###### SCSS

###### Figma

###### Git

###### React

###### Redux

###### Typescript

##### Code examples

_//Complete the function that takes an odd integer (0 < n < 1000000) which is the difference between two consecutive perfect squares, and return these squares as a string in the format "bigger-smaller"_

```
const findSquares = num => {
    let min, max
    min = Math.floor(num / 2)
    max = num - min
    return `${Math.pow(max, 2)}-${Math.pow(min, 2)}`;
}
```

_//9 --> "25-16" //5 --> "9-4" //7 --> "16-9"_
