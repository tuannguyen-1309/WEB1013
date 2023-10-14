_Selector phân vùng_ là selector chỉ chọn các thẻ ở trong một vùng cụ
thể nào đó trên trang web.
* Có 3 cách phân vùng
    + _Selector1_.__Selector2{}__
        • Chọn các thẻ thỏa mãn cả selector1 và selector2. 
        • Ví dụ: h1.abc{} chọn các thẻ <h1 class=“abc”>
    + _Selector1_ __Selector2{}__
        • Chọn các thẻ thỏa mãn selector2 là hậu duệ của các thẻ thỏa mãn selector1. 
        • Ví dụ: div h1{} chọn các thẻ <h1> nằm trong <div>
    + _Selector1_>__Selector2{}__
        • Chọn các thẻ thỏa mãn selector2 là con của các thẻ thỏa mãn selector1. 
        • Ví dụ: .abc>h1{} chọn các thẻ <h1> con của <tag class=“abc”>
