.footer-subscribe {
position: relative;
margin-left: auto
}

.footer-form-container {
display: flex;

}

.footer-form-container input {
font-weight: 400;
font-size: 16px;
line-height: 1.25;

    margin: 0;
    padding: 15px 16px;
    width: 358px;
    height: 50px;
    background-color: transparent;
    color: var(--hero-text-color);

    border: 1px solid rgba(255, 255, 255, 0.3);
    box-sizing: border-box;
    border-radius: 4px;
    margin-right: 12px;

    &::placeholder{
     font-family: 'Roboto';
    font-style: normal;
    font-weight: 400;
    font-size: 16px;
    line-height: 1.25;
    letter-spacing: var(--main-letter-spacing);


    color: rgba(255, 255, 255, 0.6);
    }

}

.footer-form-title {
font-weight: 700;
line-height: 1.14;
text-transform: uppercase;
display: block;
margin-bottom: 20px;

    color: var(--hero-text-color);

}

.footer-form-button {

    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 10px 28px;
    height: 50px;
    width: 200px;

    font-weight: 700;
    font-size: 16px;
    line-height: 1.88;
    letter-spacing: 0.06em;
    color: var(--hero-text-color);

    background-color: var(--focus-color);

    border-radius: 4px;
    border: 2px solid var(--focus-color);
    cursor: pointer;

    transition: background-color var(--main-transition),
    box-shadow var(--main-transition);

    &:hover,
    &:focus {
    background-color: var(--hero-button-fh-color);
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
    }

}

.footer-form-icon {
fill: currentColor;
display: block;
margin-left: 10px;
}
