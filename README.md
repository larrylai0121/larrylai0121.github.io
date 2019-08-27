# Ponddy Cookie Policy Form Example

Generic cookies warning for Ponddy Education Inc.

### CSS
```
.cookie-policy {
    position: fixed;
    bottom: 0;
    width: 100%;
    min-height: 48px;
    z-index: 99;
    text-align: center;
    background-color: #FFC05C;
}

.cookie-policy p,
.cookie-policy a {
    font-size: 16px;
    line-height: 20px;
    color: #2D3942;
    text-decoration-line: unset;
    margin: unset;
}

.cookie-policy a {
    margin: 0 16px;
}

.cookie-policy a:hover {
    color: #429EB9;
    text-decoration-line: underline;
}

.cookie-policy .cp-row {
    position: relative;
    width: calc(100% - 28px);
    padding: 14px;
    display: inline-block;
}

.cookie-policy .cp-description {
    display: inline-block;
}

.cookie-policy .cp-action {
    display: inline-block;
}

.cookie-policy button {
    background-color: #FFFFFF;
    color: #429EB9;
    border: unset;
    border-radius: 12px;
    transition: all .5s ease-in-out;
    font-size: 16px;
    padding: 4px 23.5px;
    cursor: pointer;
}

.cookie-policy button:hover {
    background-color: #429EB9;
    color: #FFFFFF;
}

@media (max-width: 880px) {
    .cookie-policy p {
        text-align: left;
    }

    .cookie-policy button {
        display: inline-block;
        position: absolute;
        right: 14px;
    }

    .cookie-policy a {
        display: inline-block;
        position: relative;
        left: 0;
        margin: 0;
    }

    .cookie-policy .cp-description {
        width: 100%;
    }

    .cookie-policy .cp-action {
        width: 100%;
        text-align: initial;
        margin-top: 24px;
    }
}
```
            
        
### HTML
```
<div class="cookie-policy">
    <div class="cp-row">
        <div class="cp-description">
            <p>We've put small files on your device to ensure you get the best experience on our website.</p>
        </div>
        <div class="cp-action">
            <a href="./cookie.html" target="_blank">Policy</a>
            <button>Accept</button>
        </div>
    </div>
</div>
```