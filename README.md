<before CSS flexbox>
vs extension : emmet (요즘은 vscode에 내장되어 있음)
display
    block : next에 배치 못함
    inline : width, height를 못가짐.
    inline-block : inline + width, height
margin right -> float
간격을 계산해서 값을 적어야 하므로 반응형 layout을 구현하기 어려움.
-> flexbox 나오게 됨.

<flexbox>
    container(parent)에 지정하고 child에 적용.
    반응형 Layout이 적용됨.
    display : flex;
    justify-content: 가로 방향으로 어떻게 배치할지...
