# goit-markup-hw-08

.company-box {
padding-top: 60px;
padding-bottom: 60px;
}

.company {
&\_\_header {
margin-bottom: 30px;
font-family: 'Roboto';
font-style: normal;
font-weight: 700;
font-size: 28px;
line-height: 33px;
text-align: center;
letter-spacing: 0.03em;
color: $colorText;
}
}

.company-list {
&\_\_link {
border: 1px solid #afb1b8;
border-radius: 4px;
display: flex;
justify-content: center;
align-items: center;
width: 100%;
height: 100%;
color: #afb1b8;

    transition: color 250ms $cube;

}

&\_\_logo {
fill: currentColor;
}
}

@media screen and (max-width: 479px) {
.list-box {
display: flex;
justify-content: center;
}
.company-list {
&\_\_element:not(:last-child) {
margin-bottom: 30px;
}
}
}

@media screen and (max-width: 767px) {
.company-list {
&\_\_link {
width: 210px;
padding: 16px 52px;
}
}
}

@media screen and (min-width: 480px) and (max-width: 767px) {
.company-box {
max-width: 480px;
margin-left: auto;
margin-right: auto;
}
.company-list {
display: flex;
justify-content: center;
flex-wrap: wrap;
&\_\_element {
&:nth-child(2n) {
margin-left: 30px;
}

      &:not(:nth-last-child(-n + 2)) {
        margin-bottom: 30px;
      }
    }

}
}

@media screen and (min-width: 768px) and (max-width: 1199px) {
.company-list {
display: flex;
flex-wrap: wrap;
&\_\_element {
width: 226px;
height: 92px;
&:not(:nth-child(3n + 3)) {
margin-right: 30px;
}

      &:not(:nth-last-child(-n + 3)) {
        margin-bottom: 30px;
      }
    }

}
}

@media screen and (min-width: 1200px) {
.company-box {
padding-top: 94px;
padding-bottom: 94px;
}
.company**header {
margin-bottom: 50px;
font-size: 36px;
line-height: 1.17;
}
.company-list {
display: flex;
flex-wrap: nowrap;
&**element {
width: 170px;
height: 92px;
&:not(:last-child) {
margin-right: 30px;
}
}
}
}

.company-list**element .company-list**link:hover,
.company-list**element .company-list**link:focus {
color: $colorBlue;
border-color: $colorBlue;
}

.company-list**element:hover,
.company-list**element:focus {
color: $colorBlue;
border-color: $colorBlue;
}
