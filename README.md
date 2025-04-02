/* Slow Motion Fade-in Animation */
@keyframes slowFadeIn {
    0% {
        opacity: 0;
        transform: translateY(50px);
    }
    100% {
        opacity: 1;
        transform: translateY(0);
    }
}

/* Apply the animation to the entire container */
.container {
    animation: slowFadeIn 3s ease-in-out; /* Slow fade-in over 3 seconds */
}

/* Optional: Apply animation for any other elements you want */
.service-item {
    animation: slowFadeIn 3s ease-in-out;
}
