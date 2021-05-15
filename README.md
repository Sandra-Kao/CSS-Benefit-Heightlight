# CSS-Benefit-Heightlight

Please see Codepen:

https://codepen.io/K-SY/pen/PopNrZE

![image](https://user-images.githubusercontent.com/63223781/118347709-cc677500-b577-11eb-91dc-318e58ef5184.png)



``` css
:root {
    --color-gray-darker  : #787878;
    --gray-darkest       : #323233;
    --vivid-blue-darker  : #006498;
    --vivid-blue-lightest: #daeef9;
}

* {
    margin : 0;
    padding: 0;
}

.benefit-heightlight {
    padding: 48px 50px;
}

.benefit-heightlight__wrapper {
    margin-top: 24px;
    display   : flex;
}

.benefit-heightlight__item {
    width: calc((100%-100px - (3-1) *20px) /3);
}

.benefit-heightlight__item:not(:last-child) {
    margin-right: 20px;
}

.benefit-heightlight__img {
    margin-right: 10px;
    width       : 80px;
    height      : 80px;
}

.benefit-heightlight__title {
    margin-top : 14px;
    font-size  : 20px;
    font-weight: bold;
    line-height: 1.6;
    color      : var(--black);
}

.benefit-heightlight__list {
    text-decoration: none;
}

.benefit-heightlight__list-item {
    font-size  : 14px;
    line-height: 1.43;
    color      : var(--color-gray-darker);
}```
