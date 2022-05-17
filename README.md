.menu-button{
display: flex;
justify-content: center;
align-items: center;
padding: 0;
margin-left: auto;
background-color: var(--hero-text-color);
border: none;
cursor: pointer;
transition: fill var(--main-transition);

    &:hover,
    &:focus{
        fill: var(--focus-color);

    }
    @media screen and (min-width: 768px) {
        display: none;}

}
.menu-close-button{
position: absolute;
top: 10px;
right: 15px;
}
.mobile-menu{
@media screen and (max-width: 768px) {
opacity: 0;
position: absolute;
z-index: 999;
top: 0;
transform: translateY(100%);
left: 0;
padding: 48px 40px;
width: 100%;
height: 796px;
background-color: var(--hero-text-color);

        &.is-open{
            opacity: 1;
            // display: block;
            transform: translateY(0);
        }
        }

}
