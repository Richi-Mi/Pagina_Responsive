# Pagina Responsive
```CSS
@media screen and (max-width: 360px){
    .container{
        grid-template-columns: 1fr;
        grid-template-areas: "navegacion"
                         "section"
                         "section"
                         "footer"
                         "footer"
                         "aside"; 
        grid-template-rows: 14vh repeat(2, 1fr) 6vh;
    }
    footer{
        height: 100%;
    }
    nav{
        padding: 5px;
    }
    nav div:nth-child(1){
        width: 100%;
    }
    nav div:nth-child(2){
        width: 100%;
    }
}
```