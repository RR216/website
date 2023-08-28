<!-- Start of text -->
<div class="illustrationWrapper">
    <div class="illustration"></div>
</div>
<div class="headingArea">
    <h1>
        <span class="label">preferred name</span>
        Rachel Wang
    </h1>
    <p>
        Student at Stanford University<br>
        Aspiring software engineer
    </p>
</div>

<ul class="names">
    <li>
        <span class="label">legal name</span>
        Yixing Wang
    </li>
    <li>
        <span class="label">pronounced as</span>
        [ <b>ee</b>-sh<em>ing</em> ]
    </li>
</ul>

<nav>
    <ul>
        <li><a href="/">About</a></li>
        <li><a href="/">Contact</a></li>
        <li><a href="/">Projects</a></li>
    </ul>
</nav>



<!-- Start of styling-->
<style lang="scss">
    :global(:root) {
        --_gap: 22px;
    }
    
    .label {
        font-family: "Inter", "sans-serif";
        color: var(--color-label);
        font-size: var(--fontSize-p);
        font-weight: 500;
        line-height: 1em;
    }

    .illustrationWrapper {
        display: flex;
        justify-content: flex-end;
        padding-bottom: 50px;

        .illustration {
            height: 300px;
            width: 500px;
            background-color: grey;
        }
    }

    .headingArea {
        display: flex;
        justify-content: space-between;
        align-items: last baseline;
        gap: 50px;
        padding-bottom: var(--_gap);

        h1 {
            display: flex;
            flex-direction: column;
            line-height: 1em;
        }

        p {
            text-align: end;
            font-size: var(--fontSize-p);
            font-weight: 500;
            color: var(--color-p);
        }
    }

    .names {
        li {
            font-weight: 400;
            font-size: var(--fontSize-name);
            &:first-child {
                padding-bottom: calc(0.2em + var(--_gap));
            }
            span.label {
                display: block;
                padding-bottom: 0.5em;
            }
        }
    }

    nav {
        padding-top: 100px;
        ul {
            display: flex;
            justify-content: space-between;
            li a {
                font-size: var(--fontSize-name);
                font-weight: 400;
            }
        }
    }
    
</style>