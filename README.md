tremor
======

Declarative SVG tremor

'''html
<div>
    <svg xmlns="http://www.w3.org/2000/svg" version="1.1" width="300px" height="300px">
        <image x="100" y="100" width="100" height="100" xlink:href="http://upload.wikimedia.org/wikipedia/commons/c/cb/Footnote.svg">
            <animateTransform
                begin="mouseover" end="mouseout"
                attributeName="transform" type="rotate"
                values="0 150 150;5 150 150;0 150 150"
                dur="150ms" repeatCount="indefinite"
                fill="remove"
            />
        </image>
    </svg>
</div>
