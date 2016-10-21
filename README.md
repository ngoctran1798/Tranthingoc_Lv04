Trần Thị Ngọc  
**Báo cáo học Array**  
[Dữ liệu kiểu Mảng](#Mảng)  
[Mảng một chiều](#Mảng một chiều)  
[Mảng nhiều chiều](#Mảng nhiều chiều)   
<a name = Mảng><a\>  
###I.Mảng:  
**Định nghĩa:**  
      Mảng được hiểu là một tập hợp các giá trị có cùng kiểu dữ liệu nằm liên tiếp nhau trong bộ nhớ máy tính.  
      Mảng được coi như một biến mảng và tên mảng được đặt theo quy tắc đặt tên biến.  
    *Mảng có những thành phần sau:*  
      -Kiểu dữ liệu của các phần tử trong mảng.    
      -Tên mảng.  
      -Số chiều và kích thước của mỗi chiều.  
**Cú pháp:**  
`<kiểu dữ liệu  ><tên mảng><danh sách các chiều của mảng>;`  
<a name = Mảng một chiều><a\>  
###II.Mảng một chiều.  
*Nếu xét dưới góc độ toán học, mảng 1 chiều giống như một vector. Mỗi phần tử của mảng một chiều có giá trị không phải là một mảng khác.*   
**1.Khai báo mảng với số phần tử xác định (khai báo tường minh).**    
**Cú pháp:**  
`< Kiểu> <Tên mảng ><[số phần tử]>;`    
    *Ý nghĩa:*    
        - Tên mảng: đây là một cái tên đặt đúng theo quy tắc đặt tên của danh biểu. Tên này cũng mang ý nghĩa là tên biến mảng.  
        - Số phần tử: là một hằng số nguyên, cho biết số lượng phần tử tối đa trong mảng là bao nhiêu (hay nói khác đi kích thước của mảng là gì).  
        - Kiểu: mỗi phần tử của mảng có dữ liệu thuộc kiểu gì.  
        - Ở đây, ta khai báo một biến mảng gồm có số phần tử phần tử, phần tử thứ nhất là tên mảng [0], phần tử cuối cùng là tên mảng[số phần tử -1].  
**Ví dụ**  
`int a[10];`  
**2.Khai báo mảng với số phần tử không xác định (khai báo không tường minh).**    
**Cú pháp:**    
`<Kiểu> <Tên mảng> <[]>;`   
        *Khi khai báo, không cho biết rõ số phần tử của mảng, kiểu khai báo này thường được áp dụng trong các trường hợp: vừa khai báo vừa gán giá trị, khai báo mảng là tham số hình thức của hàm.*  
    **a. Vừa khai báo vừa gán giá trị**  
    **Cú pháp:**  
`<Kiểu> <Tên mảng> []= {Các giá trị cách nhau bởi dấu phẩy};`  
     *Nếu vừa khai báo vừa gán giá trị thì mặc nhiên C sẽ hiểu số phần tử của mảng là số giá trị mà chúng ta gán cho mảng trong cặp dấu {}. Chúng ta có thể sử dụng hàm sizeof() để lấy số phần tử của mảng như sau:*  
`Số phần tử=sizeof(tên mảng)/ sizeof(kiểu)`  
    **b.Khai báo mảng là tham số hình thức của hàm, trong trường hợp này ta không cần chỉ định số phần tử của mảng là bao nhiêu.**    
Truy xuất từng phần tử của mảng  
Mỗi phần tử của mảng được truy xuất thông qua **Tên biến mảng** theo sau là **chỉ số** nằm trong **cặp dấu ngoặc vuông [ ]**. Chẳng hạn *a[0]* là *phần tử đầu tiên* của mảng a được khai báo ở trên. Chỉ số của phần tử mảng là một biểu thức mà giá trị là **kiểu số nguyên**.
Với cách truy xuất theo kiểu này, **Tên biến mảng[Chỉ số]** có thể coi như là một biến có kiểu dữ liệu là **kiểu** được chỉ ra trong khai báo biến mảng.  

<a name= Mảng nhiều chiều><a\>  
###III.Mảng nhiều chiều:  
*Mảng nhiều chiều là mảng có từ 2 chiều trở lên. Điều đó có nghĩa là mỗi phần tử của mảng là một mảng khác.
Người ta thường sử dụng mảng nhiều chiều để lưu các ma trận, các tọa độ 2 chiều, 3 chiều…*   
**Ví dụ: mảng hai chiều.**    
**Khai báo mảng 2 chiều tường minh**  
**Cú pháp:**  
`<Kiểu> <Tên mảng><[Số phần tử chiều 1]><[Số phần tử chiều 2]>`    
**Khai báo mảng 2 chiều không tường minh**    
Để khai báo mảng 2 chiều không tường minh, ta vẫn phải chỉ ra số phần tử của chiều thứ hai (chiều cuối cùng).   
**Cú pháp:**   
`<Kiểu> <Tên mảng> <[]><[Số phần tử chiều 2]>;`    
Cách khai báo này cũng được áp dụng trong trường hợp vừa khai báo, vừa gán trị hay đặt mảng 2 chiều là tham số hình thức của hàm.  
Truy xuất từng phần tử của mảng 2 chiều  
Ta có thể truy xuất một phần tử của mảng hai chiều bằng cách viết ra **tên mảng** theo sau là hai chỉ số đặt trong hai cặp dấu ngoặc vuông. Chẳng hạn ta viết m[2][3].  
Với cách truy xuất theo cách này, **Tên mảng[Chỉ số 1][Chỉ số 2]** có thể coi là 1 biến có kiểu được chỉ ra trong khai báo biến mảng.  
    






        




 


'



