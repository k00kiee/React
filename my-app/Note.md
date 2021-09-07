# React Tutorial Note

## 処理の順番の整理
- 初期表示
ReactDOM.render  
Game.render()  
Borad.render()  
Borad.renderSquare(i)  
Square.render()  

- クリック時
Borad.handleClick(i)  
Borad.render()  
Borad.renderSquare(i)  
Square.render()  

## ブランチのテスト

