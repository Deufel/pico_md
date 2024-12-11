# Personal fork of pico css, not intended to knock your socks off. 
* NOTE: I only use CSS so I stripped this down to only include the CSS*

# Change Log (to do)

/* Pico variable Over Rides */
:root {
    --pico-font-family: var(--pico-font-family-sans-serif);
    --pico-font-family-sans-serif: "Quicksand", Inter, system-ui, "Segoe UI",
        Roboto, Oxygen, Ubuntu, Cantarell, Helvetica, Arial, "Helvetica Neue",
        sans-serif, var(--pico-font-family-emoji);

    --pico-font-size: 87.5%;
    /* Original: 100% */
    --pico-line-height: 1.25;
    /* Original: 1.5 */
    --pico-form-element-spacing-vertical: 0.5rem;
    /* Original: 1rem */
    --pico-form-element-spacing-horizontal: 1rem;
    /* Original: 1.25rem */
    --pico-border-radius: 0.375rem;
    /* Original: 0.25rem */

    /* Scroll bar testing = need to fix corner  */
    ::-webkit-scrollbar {
        width: 0.75em;
        height: 0.75em;
    }

    ::-webkit-scrollbar-track {
        background: var(--pico-muted-border-color);
        border-radius: 100vw;
        margin-block: 0.5em;
    }

    ::-webkit-scrollbar-thumb {
        background-color: var(--pico-primary-background);
        border-radius: 100vw;
        border: 2px solid transparent;
        background-clip: content-box; /* Add this */
    }
}

/* Pico is better with this I think have not found any place where this is bad... */
fieldset,
[role="group"],
[role="search"] {
    margin-bottom: 0;
}
