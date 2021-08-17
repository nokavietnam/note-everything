

# NGUYEN LY THIET KE SOLID

## 1. Nguyen ly trach nhiem duy nhat 
-  Moi ung dung moi module chi nen dam nhiem 1 trach nhiem duy nhat, cac lop chi tap trung vao nhiem vu cua minh
+ VD: moi layer chi nen chiu 1 trach nhiem duy nhat:
+ controller thi chi nen tiep nhan du lieu va validate request
+ service: chiu trach nhiem xu ly logic
+ dao: thi chiu trach nhiem thao tac voi du lieu va


## 2. Nguyen ly dong mo
- Cac cac ung dung de dang mo rong va khong can thay doi ma nguon cua lop cu. extend neu fuction moi khong phai sua code lop cu

## 3. Nguyen ly thay the liskov
- Có thể thay thế lớp cha bằng lớp con nhưng không làm ảnh hưởng đến code
- 

## 4. Nguyen ly phan tach interface
- Các interface không nên chứa quá nhiều phương thức. Chỉ chứa những phương thức vừa đủ với nó. Tách biệt độc lập nếu cần phương thức nào thì implements interface đó
- 

## 5. Nguyen ly Dao nguoc phu thuoc
- Module high level và low level phụ thuộc và tương tác với nhau qua interface
- DI: Dependence Injection

