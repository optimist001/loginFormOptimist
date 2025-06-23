# Project Title

login form | optimist


## Table of Contents

- [new term](#installation)
- [Contributing](#contributing)

## what I learnt

this project exposed me to new techniques. I learnt to use backdrop filter at the time of designing this form, backdrop filter is a new term to me. Backdrop filter aloows you to apply graphical effect such as blurring to the area behing an element. below is the code snippet:

    backdrop-filter: blur(25px);


also, i learnt to apply a curvy part to the top right and left corner of the header title which makes it look sleak and beautiful. check below the way i implement it - 

    .form-head::after{
        content: "";
        width: 20px;
        height: 20px;
        background-color: transparent;
        position: absolute;
        top: 0;
        left: -20px;
        border-top-right-radius: 50%;
        box-shadow: 10px 0 0 0 var(--primary);
    }

    .form-head::before{
        content: "";
        width: 20px;
        height: 20px;
        background-color: transparent;
        position: absolute;
        top: 0;
        right: -20px;
        border-top-left-radius: 50%;
        box-shadow: -10px 0 0 0 var(--primary);
    }




## Contributing

I will gladly welcome any Contributions from bosses or my contemporary in the room. Please open an issue or submit a pull request. Thanks.

