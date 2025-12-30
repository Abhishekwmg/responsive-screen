#CSS Responsive Design NOTES:
.container {
    --max-width: 1110px;
    --padding: 1rem;

    width: min(var(--max-width, 100%));
    margin-inline: auto;
} 

//The above block of code is responsive for forcing the container to have a maximum width of 1110 PX when the device is lower than 1110 px
// and it will take 100% of the viewport when the viewport is lower than 1110px, making it responsive