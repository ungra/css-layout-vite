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
    container(parent)에 지정하고 child에 적용됨.
    반응형 Layout이 적용됨.
    display : flex;
    justify-content: 가로 방향으로 어떻게 배치할지...

    flex-direction : flex의 방향. default값은 row;

<flexbox axis>
    main axis : 주축
    cross axis : 교차축
    둘다 flex-direction에 영향을 받음.
    ex) flex-direction: row면 main axis는 가로(left -> right), cross axis는 세로(top -> bottom)

    justify-content : main axis에서 아이템을 배치하는 rule. space-between, space-around를 가장 많이 사용.

    align-items: cross axis에서 아이템을 배치하는 rule.
